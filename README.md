# Propagator

A prototype implementation of a data transfer system working as a proof of concept of the [Identity Propagation and Assertions](https://github.com/umalabs/identity-propagation-and-assertions) architecture.

## Rationale

As businesses extend the usage of their APIs, it is becoming increasingly clear that a microservices security architecture needs to expand beyond traditional enterprise boundaries. This finding leads us to implement the [Identity Propagation and Assertions](https://github.com/umalabs/identity-propagation-and-assertions) architecture to enable access to third-party web APIs using loosely coupled microservices that allow transferring arbitrary data across security domain boundaries.

## What is Propagator?

Two microservices hosted on different domains that can replace the MTA-to-MTA SMTP transmission process.
