---
layout: post
title:  "Side-Channel attack on AES algorithm"
date:   2023-01-19 14:18:06 +0200
categories: sca
---
Side-channel attacks are a class of cryptographic attacks that exploit physical characteristics of a cryptographic system, such as power consumption, electromagnetic radiation, or timing information, to obtain secret information. One well-known example of a side-channel attack is the power analysis attack, which uses measurements of the power consumption of a device to infer secret key information.

AES (Advanced Encryption Standard) is a widely used symmetric key encryption algorithm. The AES-128 variant uses a 128-bit key for encryption and decryption. The security of AES is based on the complexity of the key schedule and the number of rounds. But, it has been shown that the AES algorithm is vulnerable to side-channel attacks.

One of the most notable references for AES-128 power analysis attacks is the paper "Power Analysis Attacks: Revealing the Secrets of Smart Cards" by xxx. This paper introduced the differential power analysis (DPA) technique, which can be used to extract secret keys from AES implementations.

Another well-known research in this field is "xxx" by xxx, published in xxx. This paper introduced the Fault Analysis attack technique on AES-128 encryption algorithm. They showed that it is possible to obtain the secret key by introducing controlled faults in the encryption process.

More recently, the paper "xxx" by xxx, published in xxx, presents a comprehensive study of the power consumption of AES-128 and provides practical countermeasures against power analysis attacks.

These papers provide a good starting point for understanding the vulnerabilities of AES-128 to side-channel attacks, and various techniques and countermeasures that have been proposed to mitigate these vulnerabilities.

(to be continued)