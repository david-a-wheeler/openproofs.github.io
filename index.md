# OpenProofs

An “open proof” exists when all required source code, proofs of that
source code, and all required tools to verify and update the code and proofs
are open source software (OSS).

This enables anyone to *legally* examine, critique, improve, and collaborate
to improve the software and its proofs. In short, open proofs
expands the ideas of OSS to high assurance software.

This website explains what open proofs are, and is also intended to
(eventually) list examples of open proofs.

See [our modification instructions](./modify.md) to learn how to contribute
to this site!

Here is a very incomplete list of known Open Proofs:

* [SPARK 2014 re-implementation of the TweetNaCl crypto library ](https://github.com/rod-chapman/SPARKNaCl)
"This library is a compact reference implementation of the NaCl crypto library. It was originally inspired by the TweetNaCl implementation, but offers a completely automated static proof of type-safety (and some correctness properties), reasonable performance, and (unlike TweetNaCl) is readable owing to the large number of explanatory comments and contracts in the code." The source code is released under 2-clause BSD. The software is implemented and verified using SPARK Ada.  The proofs are auto-active and complete (meaning all VCs prove automatically by CVC4, Z3 or Alt-Ergo, which are all available as OSS).
