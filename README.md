# jose

A JOSE implementation in Python

[![Build Status](https://travis-ci.org/mpdavis/jose.svg?branch=master)](https://travis-ci.org/mpdavis/jose) [![Coverage Status](https://coveralls.io/repos/mpdavis/jose/badge.svg)](https://coveralls.io/r/mpdavis/jose)

## Principles

This is a JOSE implementation that is meant to be simple to use, both on and off of AppEngine.

## Algorithms

The following algorithms are currently supported.

Algorithm Value | Digital Signature or MAC Algorithm
----------------|----------------------------
HS256 | HMAC using SHA-256 hash algorithm
HS384 | HMAC using SHA-384 hash algorithm
HS512 | HMAC using SHA-512 hash algorithm
RS256 | RSASSA using SHA-256 hash algorithm
RS384 | RSASSA using SHA-384 hash algorithm
RS512 | RSASSA using SHA-512 hash algorithm

## Thanks

This library is based heavily on the work of the guys over at [PyJWT](https://github.com/jpadilla/pyjwt).
