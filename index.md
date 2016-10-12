---
layout: page
description: "Home"
---
# Sietse Ringers

I am a postdoctoral researcher and software engineer at the Digital Security department of the [Radboud University](http://www.ru.nl/ds/), interested in privacy enhancing technologies, cryptography, and in particular secure and privacy-friendly identity management. Before that my research involved the mathematical side of gauge theories and partial differential equations.

## Attribute-based credentials
With an attribute-based credential scheme, you can selectively show some of your properties, while keeping others to yourself (more detailed explanation [here](https://www.irmacard.org/irma/)). [Idemix](http://www.zurich.ibm.com/idemix/) is an example of such a scheme; it is used in the IRMA project. [Jaap-Henk Hoepman](http://www.cs.ru.nl/~jhh/), [Eric Verheul](http://www.cs.ru.nl/E.Verheul/) and myself have created a [new, smart-card suitable attribute-based credential scheme](files/abc.pdf).

## The IRMA project
For several years, the [IRMA project](https://www.irmacard.org) has been working on implementing attribute-based credentials on smart cards and on Android, using Idemix as underlying credential scheme. It is [open source](https://github.com/credentials/), and I have been contributing to it since June 2015; in particular on this [IRMA Android app](https://github.com/credentials/irma_android_cardemu) that can store and disclose attributes, to for example this [IRMA server](https://github.com/credentials/irma_api_server).

## PEP: Polymorphic encryption and pseudonymisation
PEP enables privacy friendly exchange of privacy sensitive medical data for specific medical research purposes, by combining advanced encryption with distributed pseudonymisation, and distribution of trusted data with fine-grained access management. The PEP project builds on the Polymorphic Encryption and Pseudonymisation technique developed by Bart Jacobs and Eric Verheul (see [the whitepaper](https://eprint.iacr.org/2016/411) or the [PEP website](http://pep.cs.ru.nl/) for more Information). Currently I am working on connecting PEP as a data transport mechanism to Radboud's [Digital Research Environment (DRE)](http://nieuws.radboudumc.nl/radboudumc-biedt-onderzoekers-digital-research-environment), an online research environment for medical researchers.

## Partially blind signature schemes
Although digital signatures already are a very versatile cryptographic primitive as is, in some situations it is desirable that (part of) the message and the resulting signature is hidden from the issuer – for example, when the issuer is not fully trusted, or when the user's privacy is at stake. In such situations one can use [(partially) blind signature schemes](https://en.wikipedia.org/wiki/Blind_signature). Wouter Lueks, [Jaap-Henk Hoepman](http://www.cs.ru.nl/~jhh/) and myself have developed a partially blind issuing protocol for [Boneh-Boyen signatures](http://link.springer.com/chapter/10.1007%2F978-3-540-24676-3_4); see [here](files/bbb.pdf). As an example of our scheme we included a (single-show) attribute-based credential scheme, offering similar efficiency but stronger security guarantees than its most well-known competitor ([U-Prove](http://research.microsoft.com/en-us/projects/u-prove/)).

## Dining cryptographers
In the [Verdict](http://dedis.cs.yale.edu/dissent/papers/verdict-abs) protocol, a group of people can share data with each other, in such a way that no can see who contributed what data. The [ipfs-dc](https://github.com/confiks/ipfs-dc) project, of which I am one of the authors, will implement this protocol on top of [IPFS](https://ipfs.io/), a distributed networking protocol that ensures data integrity.

## PhD thesis
My PhD thesis **Quantization using Jet Space Geometry and Identity Management using Credential Schemes**, which I defended on 7 October 2016 at the University of Groningen, may be found [here](/files/thesis.pdf). I have many hardcopies left; if you would like one, feel free to contact me.

## Publications
* E. Verheul, S. Ringers, and J.-H. Hoepman. **The self-blindable U-Prove scheme from FC'14 is forgeable.** In _Financial Cryptography 2016 (FC'16)_, to be published. [PDF](https://eprint.iacr.org/2015/725.pdf), [slides](files/fc-16-talk.pdf)
* S. Ringers, J.-H. Hoepman, and W. Lueks. **On linkability and malleability in self-blindable credentials.** In [_The 9th WISTP International Conference on Information Security Theory and Practice (WISTP'2015)_](http://link.springer.com/chapter/10.1007/978-3-319-24018-3_13), Heraklion, Crete, Greece, August 24-25 2015. [PDF](files/sbc-linkable.pdf)

#### Earlier publications
* A. V. Kiselev and S. Ringers. **A comparison of definitions for the Schouten bracket on jet spaces.** In _Proceedings of Sixth International Workshop “Group Analysis of Differential Equations and Integrable Systems”_, Larnaca, Cyprus, 2012. [arXiv: 1208.6196](http://arxiv.org/abs/1208.6196).
* S. Ringers, **Topologically Twisted Yang-Mills Theory on K3 Surfaces**. MSc thesis, supervised by prof. R. Dijkgraaf. [PDF](files/mscthesis.pdf).

## Contact

 * sringers at cs.ru.nl
 * mail at sietseringers.net
 * PGP: [1454E9DA/639A 6D6A D9B0 B99A E2B9  D43C 13DA 013A 1454 E9DA](https://pgp.mit.edu/pks/lookup?op=get&search=0x13DA013A1454E9DA)
