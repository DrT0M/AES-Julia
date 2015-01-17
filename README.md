# AES-Julia
AES in native Julia, along with file encryption/decryption utilities

AES.jl
======
Advanced Encryption Standard - NIST FIPS PUB 197.

* ECB mode file encryption - file_encrypt("original_file.txt","encrypted_128.aes",128,"password")
* ECB mode file decryption - file_decrypt("encrypted_128.aes","original_file.txt",128,"password")
* AES 16 byte block encryption - aes_encrypt
* AES 16 byte block decryption - aes_decrypt
* AES key scheduling - aes_set_key
* AES key storage - aes_context

See runtests.jl for more examples.
