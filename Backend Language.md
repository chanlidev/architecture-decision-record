# Backend Language
## Status

Accepted

## Context

Depending on a native mobile app built using React Native, the choice of backend language is crucial for providing server-side functionality. Node.js was chosen due to its versatility, event-driven architecture, and ability to handle several concurrent connections. This solution aligns with the app's requirements for push alerts, payment transactions, and seamless data syncing with the server.

## Decision

Node.js will be used as the backend language.

## Consequences

Node.js has a non-blocking, event-driven design that is well-suited to managing several concurrent connections, such as push notifications and payment transactions. Its versatility, simplicity of integration, and extensive module library make it ideal for the retail app's scalable backend requirements.
Because Node.js is a single-threaded program, proper concurrency control takes careful consideration.
