# Crypto Standards and Recommendations

| Abbr. | Description                                              |
|-------|----------------------------------------------------------|
| FIPS  | U.S. Government Federal Information Processing Standards |
| NIST  | The National Institute of Standards and Technology       |
| PKCS  | Public Key Cryptography Standard                         |
| ANSI  | The American National Standards Institute                |



## List of Standards
The table below lists cryptography standards and recommendations classified in different groups.

| No | Code | Tittle | Comments | Status |
|:------------------------------------------:|:-------------------------:|:-----------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------:|
|: Encryption : |||
| 1 | FIPS 46-3 | Data Encryption Standard (DES) | Symmetric block cipher with a key length of 56 bits. | Withdrawn |
| 2 | NIST-SP 800-67 Rev.2      | Recommendation for the Triple Data Encryption Algorithm Block Cipher | The 3-key option of the Triple Data Encryption Algorithm (TDEA) with a key length of 168 bits. | Valid till 2030 |
| 3 | FIPS-197 | Advanced Encryption Standard (AES) | Symmetric block cipher  with key lengths of 128, 192 and 256 bits |
| 4                                          | SP 800-111                | Guide to Storage Encryption Technologies for End User Devices                                         | Providing guidance for the process of using appropriate encryption and authentication solutions to restrict access to and use of stored information                                                                                                                                                                                                | Released Nov 2007                            |
| Digital Signatures                         |                           |                                                                                                       |                                                                                                                                                                                                                                                                                                                                                    |                                              |
| 1                                          | FIPS 186-4                | Digital Signature Standard (DSS)                                                                      | Specifications of three NIST-approved digital signature algorithms: DSA, RSA, and ECDSA.                                                                                                                                                                                                                                                           | Issued Oct. 2015                             |
| 2                                          | FIPS 186-5                | Digital Signature Standard (DSS)                                                                      | Updates to its standards on digital signatures and elliptic curve cryptography to align with existing and emerging industry standards.                                                                                                                                                                                                             | Draft                                        |
| 3                                          | SP 800-102                | Recommendation for Digital Signature Timeliness                                                       | Recommendations for using time (from a Trusted Timestamp Authority) in digital signatures and verifier-supplied data that is included in the signed message.                                                                                                                                                                                       | Released Sep 2009                            |
| Hash Functions                             |                           |                                                                                                       |                                                                                                                                                                                                                                                                                                                                                    |                                              |
| 1                                          | FIPS 180-4                | Secure Hash Standard                                                                                  | SHA-1 with output length of 160-bits, and SHA-2 with output lengths from 224 to 512 bits,  approved for use with digital signature algorithms, keyed-hash message authentication codes, key derivation functions and random bit generators                                                                                                         | SHA-1 not secure                             |
| 2                                          | FIPS 202                  | SHA-3 Standard: Permutation-Based Hash and Extendable-Output Functions                                | Outputs are from 224 to 512 bits,  approved for use with digital signature algorithms, keyed-hash message authentication codes, key derivation functions and random bit generators.                                                                                                                                                                |                                              |
| 3                                          | NIST SP 107               | Recommendation for Applications Using Approved Hash Algorithms                                        | Security guidelines for achieving the required or desired security strengths when using cryptographic applications that employ the approved hash functions specified in FIPS 180-4. These include functions such as digital signatures, Keyed-hash Message Authentication Codes (HMACs) and Hash-based Key Derivation Functions (Hash-based KDFs). |                                              |
| Message Authentication Codes               |                           |                                                                                                       |                                                                                                                                                                                                                                                                                                                                                    |                                              |
| 1                                          | FIPS 198-1                | The Keyed-Hash Message Authentication Code                                                            | Specification of a mechanism for message authentication using an approved hash function.                                                                                                                                                                                                                                                           |                                              |
| 2                                          | SP 800-38B                | Recommendation for Block Cipher Modes of Operation: The CMAC Mode for Authentication                  |  The CMAC mode is constructed from an approved block cipher                                                                                                                                                                                                                                                                                        |                                              |
| 3                                          | SP 800-38D                | Recommendation for Block Cipher Modes of Operation: Galois/Counter Mode                               | Block cipher-based MAC with Galois/Counter mode                                                                                                                                                                                                                                                                                                    |                                              |
| 4                                          | SP 800-185                | SHA-3 Derived Functions: cSHAKE, KMAC, TupleHash, and ParallelHash                                    | KMAC (for KECCAK Message Authentication Code) is a variable-length message authentication code algorithm based on KECCAK; it can also be used as a pseudorandom function.                                                                                                                                                                          |                                              |
| Key Derivation Functions/Key Establishment |                           |                                                                                                       |                                                                                                                                                                                                                                                                                                                                                    |                                              |
| 1                                          | SP 800-38F                | Recommendation for Block Cipher Modes of Operation: Methods for Key Wrapping                          | Standard of use of AES and Triple-DES to protect the confidentiality and integrity of cryptographic keys                                                                                                                                                                                                                                           |                                              |
| 2                                          | SP 800-56A Rev. 3         | Recommendation for Pair-Wise Key-Establishment Schemes Using Discrete Logarithm Cryptography          | Specifications of key-establishment schemes based on the discrete logarithm problem over finite fields and elliptic curves, including several variations of Diffie-Hellman and Menezes-Qu-Vanstone (MQV) key establishment schemes.                                                                                                                |                                              |
| 3                                          | SP 800-56B Rev. 2         | Recommendation for Pair-Wise Key Establishment Schemes Using Integer Factorization Cryptography       |                                                                                                                                                                                                                                                                                                                                                    |                                              |
| 4                                          | SP 800-56C Rev. 2         | Recommendation for Key Derivation Methods in Key-Establishment Schemes                                |                                                                                                                                                                                                                                                                                                                                                    |                                              |
| 5                                          | SP 800-71                 | Key Establishment Using Symmetric Block Ciphers                                                       | The only standard for key management system is based on symmetric key cryptography, that can be resistant against quantum computing attacks                                                                                                                                                                                                        | DRAFT                                        |
| 6                                          | SP 800-108 Rev. 1         | Recommendation for Key Derivation Using Pseudorandom Functions                                        |                                                                                                                                                                                                                                                                                                                                                    | DRAFT                                        |
| 7                                          | SP 800-133 Rev. 2         | Recommendation for Cryptographic Key Generation                                                       |                                                                                                                                                                                                                                                                                                                                                    | Issued June 2020                             |
| 8                                          | SP 800-135 Rev. 2         | Transitions: Recommendation for Existing Application-Specific Key Derivation Functions                |                                                                                                                                                                                                                                                                                                                                                    |                                              |
| Key Management                             |                           |                                                                                                       |                                                                                                                                                                                                                                                                                                                                                    |                                              |
| 1                                          | SP 800-57, Part 1, Rev. 5 | Recommendation for Key Management: General                                                            | A general approach for transitioning from one algorithm or key length to another.                                                                                                                                                                                                                                                                  |                                              |
| 2                                          | SP 800-57, Part 2, Rev. 1 | Best Practices for Key Management Organizations                                                       | A guidance on how organizations should manage cryptographic keys in accordance with the federal key management policies and best practices described in SP 800-57 Part 1                                                                                                                                                                           |                                              |
| 3                                          | SP 800-57, Part 3         | Application-Specific Key Management Guidance                                                          | A guidance when using the cryptographic features of current systems.                                                                                                                                                                                                                                                                               |                                              |
| 4                                          | SP 800-131A Rev. 2        | Transitioning the Use of Cryptographic Algorithms and Key Lengths                                     | Providing cryptographic key management guidance for defining and implementing appropriate key management procedures, using algorithms that adequately protect sensitive information, and planning ahead for possible changes in the use of cryptography because of algorithm breaks or the availability of more powerful computing techniques.     |                                              |
| 5                                          | SP 800-130                | A Framework for Designing Cryptographic Key Management Systems                                        | Containing topics that should be considered by a CKMS designer when developing a CKMS design specification.                                                                                                                                                                                                                                        |                                              |
| 6                                          | SP 800-152                | A Profile for U.S. Federal Cryptographic Key Management Systems (CKMS)                                | Containing requirements for their design, implementation, procurement, installation, configuration, management, operation, and use by U. S. Federal organizations.                                                                                                                                                                                 |                                              |
| Elliptic Curve Cryptography                |                           |                                                                                                       |                                                                                                                                                                                                                                                                                                                                                    |                                              |
| 1                                          | SP 800-186                | Recommendations for Discrete Logarithm-Based Cryptography: Elliptic Curve Domain Parameters           | Elliptic curve specifications to meet security or customer requirements.                                                                                                                                                                                                                                                                           | Draft                                        |
| Random Bit Generation                      |                           |                                                                                                       |                                                                                                                                                                                                                                                                                                                                                    |                                              |
| 1                                          | SP 800-90A, Rev. 1        | Recommendation for Random Number Generation Using Deterministic Random Bit Generators                 | Specifications of mechanisms for the generation of random bits using deterministic methods. In this revision, the specification of the Dual_EC_DRBG has been removed. The remaining DRBGs (i.e., Hash_DRBG, HMAC_DRBG and CTR_DRBG) are recommended for use.                                                                                       | Issued June 2015                             |
| 2                                          | SP 800-90B                | Recommendation for the Entropy Sources Used for Random Bit Generation                                 | Recommendation specifies the design principles and requirements for the entropy sources used by Random Bit Generators, and the tests for the validation of entropy sources.                                                                                                                                                                        | Issued Jan 2018                              |
| 3                                          | SP 800-90C                | Recommendation for Random Bit Generator (RBG) Constructions                                           | Recommendation for Random Bit Generator (RBG) Constructions.                                                                                                                                                                                                                                                                                       | Issued April 2016                            |
| 4                                          | SP 800-22 Rev. 1a         | A Statistical Test Suite for Random and Pseudorandom Number Generators for Cryptographic Applications |  Discussing some aspects of selecting and testing random and pseudorandom number generators                                                                                                                                                                                                                                                        | Published 2010. Decided to revise April 2022 |
| Other Security Standards                   |                           |                                                                                                       |                                                                                                                                                                                                                                                                                                                                                    |                                              |
| 1                                          | FIPS 200                  | Minimum Security Requirements for Federal Information and Information Systems                         | FIPS 200 specifies minimum security requirements for federal information and information systems and a risk-based process for selecting the security controls necessary to satisfy the minimum requirements.                                                                                                                                       | Issued Mar 2006                              |
| 2                                          | FIPS 140-3                | Security Requirements for Cryptographic Modules                                                       | This standard is applicable to all federal agencies that use cryptographic-based security systems to protect sensitive information in computer and telecommunication systems                                                                                                                                                                       | Issued Mar 2019                              |
| Public Key Cryptography Standards (PKCS)   |                           |                                                                                                       |                                                                                                                                                                                                                                                                                                                                                    |                                              |
| 1                                          | PKCS #1                   | RSA Cryptography Standard                                                                             | Providing standards for implementing RSA algorithm-based public key cryptographic encryption schemes and digital signature schemes                                                                                                                                                                                                                 |                                              |
| 2                                          | PKCS #3                   | Diffie-Hellman Key Agreement Standard                                                                 | Describing a method for implementing the Diffie-Hellman key agreement                                                                                                                                                                                                                                                                              | outdated                                     |
| 3                                          | PKCS #5                   | Password-Based Cryptography Standard                                                                  | PKCS #5 provides a general mechanism to achieve enhanced security for password-based cryptographic primitives, covering key derivation functions, encryption schemes, message-authentication schemes, and ASN.1 syntax identifying the techniques.                                                                                                 |                                              |
| 4                                          | PKCS #6                   | Extended-Certificate Syntax Standard                                                                  | Replaced by X.509 v3 certificate                                                                                                                                                                                                                                                                                                                   | Historical                                   |
| 5                                          | PKCS #7 and RFC 3369      | CMS or Cryptographic Message Syntax                                                                   | CMS defines the syntax used to digitally sign, digest, authenticate, or encrypt arbitrary message content.                                                                                                                                                                                                                                         |                                              |
| 6                                          | PKCS #8                   | Private-Key Information Syntax Standard                                                               | A standard to store private keys to move private keys from one system to another system                                                                                                                                                                                                                                                            |                                              |
| 7                                          | PKCS #9                   | Selected Object Classes and Attribute Types                                                           | Supporting PKCS-defined attributes (e.g., to store PKCS attributes in a directory service) in directory systems based on LDAP and the X.500 family protocols                                                                                                                                                                                       |                                              |
| 8                                          | PKCS #10                  | Certification Request Syntax Standard                                                                 | PKCS #10 v1.7 specifies syntax for certificate request. When one entity wants to get a public key certificate, the entity constructs a certificate request. It sends it to a certification authority, which transforms the request into an X.509 public-key certificate.                                                                           |                                              |
| 9                                          | PKCS #11                  | Cryptographic Token Interface Standard                                                                | PKCS #11 v2.20 specifies an application programming interface (API), called “Cryptoki”, to devices that hold cryptographic information and perform cryptographic functions.                                                                                                                                                                        |                                              |
| 10                                         | PKCS #12                  | Personal Information Exchange Syntax Standard                                                         | PKCS #12 v1.0 describes a transfer syntax for personal identity information, including private keys, certificates, miscellaneous secrets, and extensions.                                                                                                                                                                                          |                                              |
| 11                                         | PKCS #15                  | Cryptographic Token Information Syntax Standard                                                       | Standard for cryptographic tokens, such as Integrated Circuit Cards (or IC cards), that  can handle authentication information such as digital certificates and capabilities, authorizations, and cryptographic keys.                                                                                                                              |                                              |


## Other Standards

There are other topics of cryptography being standardized, including:

- Pairing-based Cryptography
- Lightweight Cryptography
- Post-Quantum Cryptography
- Multi-Party Threshold Cryptography
- Privacy-Enhancing Cryptography: includes Zero-Knowledge Proof, Multi-Party Computation, Fully Homomorphic Encryption, Group and Ring signatures, Private Information Retrieve, Structured Encryption
