# Permissions
## Status

Accepted

## Context

The app needs to request and manage permissions dynamically based on user actions. Dynamic permission management is crucial for improving both user experience and privacy. The goal here is to align the app's permission requests with platform-specific requirements while ensuring that permissions are only requested when absolutely essential to maintain user trust.

## Decision

The app will seek and manage permissions dynamically in response to user activities.

## Consequences

To improve the user experience and privacy, the app will require permissions such as location access for delivery tracking, camera access for loyalty program interactions, and push notification access. Dynamic permission management guarantees that users are only prompted when necessary.
However, implementing dynamic permission logic may introduce complexity, especially for apps with intricate permission requirements.