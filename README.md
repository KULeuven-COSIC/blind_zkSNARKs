# Blind zkSNARKs
This repository contains all codes and assets regarding blind zkSNARKs. You can find:
1. **Proof of Decryption:** We implemented the proof-of-decryption protocol presented in our [paper] (https://eprint.iacr.org/2024/1684) in C. We leveraged basic primitives used in [Lazer](https://eprint.iacr.org/2024/1846), a library for lattice-based zero-knowledge proofs, and thoroughly extended it to construct our proof of decryption for [GBFV](https://eprint.iacr.org/2024/1587) ciphertexts.
   
3. **Performance estimation for Blind Fractal ([Magma](http://magma.maths.usyd.edu.au/magma/) scripts)**


### Learning materials
* Paper: [Blind zkSNARKs for Private Proof Delegation and Verifiable Computation over Encrypted Data](https://eprint.iacr.org/2024/1684)
* Blog post: [Blind zkSNARKs](https://www.esat.kuleuven.be/cosic/blog/blind-zksnarks/)
* Video: [Nexus Speaker Series: Jannik Spiessens](https://www.youtube.com/watch?v=TPnmoeOf2w8)


### Proof of Decryption
The main source code related to verifiable decryption can be found in:  

- Folder `proof-of-decryption/vdec`
- Folder `proof-of-decryption/scripts`


### Team:
* [Jannik Spiessens](https://www.esat.kuleuven.be/cosic/people/person/?u=u0165611)
* [Jiayi Kang](https://jiayikang2.github.io/)
* [Mariana Gama](https://mmargama.github.io/)
* [Emad Heydari Beni](https://heydari.be)
* [Frederik Vercauteren](https://www.esat.kuleuven.be/cosic/people/person/?u=u0031924)


### Acknowledgement
We thank Robin Geelen for helping us use the GBFV implementation and Vadim Lyubashevsky and Patrick Steuer for helping us use the Lazer library. This work was supported in part by the European Research Council (ERC) under the European Union’s Horizon 2020 research and innovation programme (grant agreement ISOCRYPT - No. 101020788) and by CyberSecurity Research Flanders with reference number VR20192203. A large part of the codebase is copied verbatim from [Lazer](https://eprint.iacr.org/2024/1846), produced by IBM Research Europe.
