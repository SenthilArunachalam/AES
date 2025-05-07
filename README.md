# EX-8-ADVANCED-ENCRYPTION-STANDARD ALGORITHM
# Aim:
To use Advanced Encryption Standard (AES) Algorithm for a practical application like URL Encryption.

# ALGORITHM:
AES is based on a design principle known as a substitution–permutation.
AES does not use a Feistel network like DES, it uses variant of Rijndael.
It has a fixed block size of 128 bits, and a key size of 128, 192, or 256 bits.
AES operates on a 4 × 4 column-major order array of bytes, termed the state
# PROGRAM:
~~~
char url[] = "HELLWORLD";
char key[] = "key123";

printf("Original text: %s\n", url);

xor_encrypt_decrypt(url, key);
printf("Encrypted text: %s\n", url);

xor_encrypt_decrypt(url, key);  // Decrypting back using the same function
printf("Decrypted text: %s\n", url);

return 0;
~~~
# OUTPUT:
![output](https://github.com/user-attachments/assets/435a6991-930c-4fe8-b6dd-4562d1b21cc6)


# RESULT:
The code executed successfully

