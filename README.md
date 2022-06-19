# Propagator

A prototype implementation of a data transfer system working as a proof of concept of the [Identity Propagation and Assertions](https://github.com/umalabs/identity-propagation-and-assertions) architecture. Propagator is a gRPC API-to-API data transfer system that resembles how the MTA-to-MTA SMTP transmission works. You can send any message, e.g., an order, from the sender's API to an arbitrary recipient's API; vice-versa, you can receive a message from any sender's API.

## Features

1. mTLS/JWT provides the client and user authenticity.
2. TLS provides confidentiality and integrity of data in transit.
3. The client or server can push and pull data.

## Usage Example

TBD
