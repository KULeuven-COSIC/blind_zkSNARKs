# Verifiable Decryption for GBFV

We implemented the proof-of-decryption protocol presented in the paper in C. We leveraged basic primitives used in [Lazer](https://eprint.iacr.org/2024/1846),
a library for lattice-based zero-knowledge proofs, and thoroughly extended it to construct our proof of decryption for [GBFV](https://eprint.iacr.org/2024/1587) ciphertexts.  


### Main source code
The main source code related to verifiable decryption can be found in:  

- Folder `vdec`
- Folder `scripts`

### Software and hardware requirement
The required dependencies are exactly the same as [Lazer](https://github.com/lazer-crypto/lazer). The following hardware and software are required to build and run Lazer:

- Linux amd64 / x86-64 system
- kernel version >= 4.18
- avx512 and aes instruction set extensions
- gcc compiler >= 13.2
- make >= 4.2, cmake >= 3.26
- sagemath >= 10.2
- python3 >= 3.10, its development package and the cffi package



### How to compile and run the tests/benchmarks
You are familiar with Visual Studio Code; tasks are already configured in `.vscode` for building, debugging, and cleaning the project. Otherwise, you can run `make all`. This command also runs the code in the `vdec` folder and generates the executable binary.
