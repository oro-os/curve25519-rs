# Curve25519 in Pure Rust

[![Build Status](https://travis-ci.org/shekohex/curve25519-rs.svg?branch=master)](https://travis-ci.org/shekohex/curve25519-rs)

Curve25519 is a state-of-the-art Diffie-Hellman function suitable for a wide variety of applications.

Given a user's 32-byte secret key, Curve25519 computes the user's 32-byte public key.
Given the user's 32-byte secret key and another user's 32-byte public key, Curve25519 computes a 32-byte secret shared by the two users.
This secret can then be used to authenticate and encrypt messages between the two users.

See [spec](https://cr.yp.to/ecdh.html)