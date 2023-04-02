# RSA Factoring Challenge
Concepts:

    Asymmetric cryptography algorithm – Public key encryption, private key decryption.
    Symmetric cryptography algorithm – Public key encryption and decryption.

Handshake:

    Hello – Client send cryptography algorithm and the SSL version it supports.
    Certificate Exchange – Server sends certificate to identify itself, and certificate public key.
    Key Exchange – The client uses Certificate public key to encrypt a new client regenerated public key (using the agreed asymmetric cryptography algorithm from step 1) and sends it to the server. The server decrypts it using its private key (using asymmetric cryptography algorithm).
    Data Exchange - This public key is now know by both client and server. It is used for subsequent requests/responses for both encryption and decryption on both client and server (symmetric cryptography algorithm)
* 0. Factorize as many numbers as possible into a product of two smaller numbers.
* 1. RSA Laboratories states that: for each RSA number n, there exist prime numbers p and q such that

