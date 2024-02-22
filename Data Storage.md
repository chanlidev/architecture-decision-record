# Data Storage
## Status

Accepted

## Context

To support offline mode and assure data consistency, the team must decide on a data storage method. SQLite is chosen as the local database, which supports server synchronization. 

## Decision

SQLite will be utilized as the app's local database.

## Consequences

SQLite's offline support enables customers to browse goods and check order history without internet connectivity. 
SQLite may face limitations with scalability, especially as the app's data storage needs grow.