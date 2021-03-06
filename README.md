# Hello there!

In this repository I collect my adventures in the Cryptography world.
You will find
- Medium-Highly Detailed explanations of algorithms
- Implementations in Python / Sage
- Common libraries for solving the problems
- Everything is full of resources (from Youtube videos with intuitive explanations to detailed papers on the subject)

# IMPORTANT NOTE
I **HIGHLY** recommend using nbviewer if you're reading these online: https://nbviewer.jupyter.org/github/zademn/EverythingCrypto/tree/master/  
- Github doesn't render the all mathematics inside the notebooks
- Github doesn't render images properly inside the notebooks 

## Disclaimer
- This whole repository is for educational purposes
- DO NOT USE ANY OF THE ALGORITHMS IN REAL WORLD APPLICATIONS


# Structure?

## Notebooks
- For educational and "ease to follow" purposes I decided to work in notebooks. Notebook are structured as follows:
    - Prerequisites = list of subjects/notebooks that you need to cover before attempting the subject
    - Theory = Mathematical explanation + intuitions
    - Code = Python,Sage or other library
    - Resources = List of resources for further reading
 ## PDF's
- Some basic theory in the form of pdf's here and there
    
## Directories

Directories are organized by categories
- Security theory 
    - Basic definitions and what to expect (Start with this)
- PRNG's
    - Pseudorandom generators, pseudorandom functions, a chacha20 implementation, LFSRs (+Geffe)
    
- Mathematics = Here you will find the basic structures(groups, curves, etc) and algorithms that I studied
    - Number theory - Start with this
    - Elliptic Curves - Theory
    - Discrete Logarithm Problem 
    - Elliptic curve Discrete Logarithm Problem 
    - Factorizations 
    - Lattices
    - Primality and primality tests
- Public Key = Each cryptosystem will have an introduction and a folder with vulnerabilities (NOTE: mathematical vulnerabilities (Ex: factorizations, dlp) will not be covered to avoid monotony. I assume you can connect the points) 
    - RSA + vulnerabilities
    - Diffie Hellman + vulnerabilities
    - Elgamal
- Block Ciphers
    - AES, DES
    - Block ciphers modes of operation - pdf
- Digital signatures
    - ECDSA + vulnerabilities
    - RSADSA + vulnerabilities
- Secret sharing schemes
    - General Idea and SSSS

Each directory will have a README.md that will contain the difficulty MY difficulty ranking of different subjects, attacks etc.

# How to tackle this repository?
Whatever fits your needs (Start with the security theory folder though to know what to expect)
1. Follow along with a book
2. Depth-first fashion (for people that have good foundations):
    - Pick a bigger subject
    - Study it thoroughly (from the lowest difficulty to the highest)
3. Breadth-first fashion (for starters):
    - Go through every topic at the lowest difficulty
    - Raise the difficulty and start again


# TODO 
(As of 3 Dec 2020)
- [ ] SIS, LWE
- [ ] Hashes
- [ ] Code for DES and Feistel ciphers
- [ ] Lattice theory + LLL details and implementation
- [ ] Lattice Cryptosystems
- [ ] Homomorphic encryption
    
