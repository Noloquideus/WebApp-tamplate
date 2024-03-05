# ARCHITECTURE
Three-tier architecture of my application

## Application layer
Level for objects and interfaces

- **Models**: Created objects are stored here
- **Abstractions**: Repository interfaces are stored here
- **Contracts**: Service interfaces are stored here
- **App**: Implementation of services

## Infrastructure layer
DbContext, Repositories and specific implementations of our repositories.

## Presentation layer
Data presentation layer, we can say that it acts as an API providing the user. In our case, there will only be controllers for your domains that present information to your end consumer.