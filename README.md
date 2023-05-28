# RSA-Encryption-in-python
This Program encrypts as well as decrypts your messages using the RSA(Rivest,Shamir,Adleman) Algorithm whihch is the basis of a cryptosystem.A suite of cryptographic algorithms that are used for specific security services or purposes, which enables public key encryption and is widely used to secure sensitive data, particularly when it is being sent over an insecure network.

Import random library.

Define GCD

Define Multiplicative inverse of the GCD & the two co prime integers.

Define the Key pair generation for encryption & decryption of the message.

Define encytion & decryption.

# Main program
if __name__ == '__main__':
    p = 61
    q = 53

    public_key, private_key = generate_key_pair(p, q
    
    Enter the message to be encrypted.
    Print the encrypted message.
    decrypted_message = decrypt(encrypted_message, private_key)
    Print the Decrypted Message
