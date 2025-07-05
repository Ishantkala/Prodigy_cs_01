def caesar_cipher(text, shift):
    result = ""
    for char in text:
        if char.isalpha():
            base = ord('A') if char.isupper() else ord('a')
            new_char = chr((ord(char) - base + shift) % 26 + base)
            result += new_char
        else:
            result += char
    return result


message = input("Enter message: ")
shift = int(input("Enter shift (0-25): "))

encrypted = caesar_cipher(message, shift)
print("Encrypted message:", encrypted)


decrypted = caesar_cipher(encrypted, -shift)
print("Decrypted message:", decrypted)
