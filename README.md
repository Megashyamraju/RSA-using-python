Python-RSA Implementation
PyPI

This is a Python implementation of the RSA Algorithm. Made in Python 3.7.

Just for learning, we have how to code properly the implementation of RSA Algorithm in Python, and how to deal with a project. Help is always welcomed.

Steps

Create a project on your personal GitHub.
GitHub Local ssh-agent
Upload the project with the local Bayer ssh-keys.
Show the creation of the ssh-keygen and the classes.
Show RSA-algoris.
Show the features.
Pure-Python RSA implementation
GitHub Documentation

Generator SSH keys

ssh.com
Medium
ssh-keygen -t rsa -b 4096 -C
ssh-keygen -t ed25519 -b 4096 -C
Hash Generator
Mythbusters Demo GPU versus CPU
Lifetimes of cryptographic hash functions

RSA algorithm

Take two distinct, large primes p and q.
Ideally these have a similar byte-length.
Multiply p and q and store the result in n.
Find the totient for n using the formula: 𝜑(𝑛) = (𝑝−1)⋅(𝑞−1).
Take an e coprime that is greater, than 1 and less than n.
Find d using the formula 𝑑⋅𝑒 ≡ 1 mod 𝜑(𝑛).
At this point, the pair (e, n) is the public key and the private key (d, n) is the private key.

Features

Create a private and public keys.
Messages Encryption
Messages Decrypted
