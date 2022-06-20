# Awesome Argon2 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
Curated list of awesome argon2 related things

## Contents

- [Libraries](#libraries)
  - [Java](#java)
  - [Web](#web)
- [Tools](#tools)
- [Articles](#articles)
- [Papers](#papers)

## Libraries

### Java

- [argon2-jvm - Argon2 bindings for Java with / without pre built Argon2](https://github.com/phxql/argon2-jvm)

  JVM bindings for Argon2. Includes packages with and without Argon2 binaries.

### Web

- [argon2-browser - Argon2 library compiled for browser runtime](https://github.com/antelle/argon2-browser)

  Multiple versions of Argon2 (including WASM) for the browser.

## Tools

- [Argon2 calibration tool](https://github.com/bburman/Twelve21.PasswordStorage)

  Tool for parameter calibration. Releases are available at fork https://github.com/proohit/Argon2CalibratorTool/releases.

- [kratos](https://github.com/ory/kratos)

  Identity server software using Argon2. Includes a CLI to calibrate Argon2 parameters.

- [Argon2 Online](https://argon2.online/)

  Tool to calculate and verify hashes directly in the browser.

## Articles

- [Password Hashing: Scrypt, Bcrypt and ARGON2](https://medium.com/analytics-vidhya/password-hashing-pbkdf2-scrypt-bcrypt-and-argon2-e25aaf41598e)

  Small introduction in and comparison of bcrypt, scrypt and argon2.

- [What's Up Argon2? The Password Hashing Winner A Year Later - JP Aumasson](https://www.youtube.com/watch?v=Sc3aHMCc4h0)

  Motivation of and introduction in Argon2.

- [Java Password Hashing with Argon2](https://mkyong.com/java/java-password-hashing-with-argon2/)

  Article describing different ways to use Argon2 in Java.

## Papers

- [Argon2: the memory-hard function for password hashing and other applications](https://github.com/P-H-C/phc-winner-argon2/blob/master/argon2-specs.pdf)

  Original Argon2 publishing paper.

- [Argon2](https://www.password-hashing.net/submissions/specs/Argon-v3.pdf)

  A longer version of the original paper, but may have outdated concepts. Use carefully. When in doubt always use original paper.

- [Alwen, J.; Blocki, J.: Towards Practical Attacks on Argon2i and Balloon Hashing: 2017 IEEE European Symposium on Security and Privacy (EuroS&P). IEEE, S. 142–157, 2017](https://ieeexplore.ieee.org/document/7961977)

  Documented attack on Argon2i.
