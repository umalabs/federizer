# Propagator

Propagator, an API-to-API security framework, is a prototype implementation of the [Identity Propagation and Assertions](https://github.com/umalabs/identity-propagation-and-assertions) architecture. Propagator uses this architecture to convey the user's security context alongside messages between API consumers and API producers. The API-to-API communication resembles how the MTA-to-MTA SMTP transmission works. You can send any message, e.g., an order, from the sender's API to an arbitrary recipient's API; vice-versa, you can receive a message from any sender's API.

## Features

1. mTLS/JWT provides the client and user authenticity.
2. TLS provides confidentiality and integrity of data in transit.
3. Both the API consumer and the API producer can push and pull data.

## Capabilities Comparison

Email system MTA-to-MTA vs. API-to-API Propagator security framework.

|Capability| MTA-to-MTA<br>(SMTP-to-SMTP)   | API-to-API<br>(HTTP-to-HTTP) |
|---| -------- | ----------- |
|Main functionality| Send a message | Call an API |
|Routing| Via email addresses | Via email addresses |
|Multiple recipients| Yes | Yes |
|Data manipulation| N/A | CRUD operations |
|No sign-up at recipients| Yes | Yes |

## Sequence Diagram

![Diagram](./images/propagator_flow.svg)

## Repositories

* API-to-API Security Token Service [https://github.com/umalabs/api-to-api-sts](https://github.com/umalabs/api-to-api-sts)  
* API-to-API Gateway [https://github.com/umalabs/api-to-api-gateway](https://github.com/umalabs/api-to-api-gateway)
