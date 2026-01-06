# Onboarding guide for contributors

<!-- @import "[TOC]" {cmd="toc" depthFrom=1 depthTo=6 orderedList=false} -->

<!-- code_chunk_output -->

- [Onboarding guide for contributors](#onboarding-guide-for-contributors)
  - [Legal](#legal)
  - [Technical](#technical)
    - [Rust Basics](#rust-basics)
      - [Task 1: async-echo](#task-1-async-echo)
    - [Intro to Flor](#intro-to-flor)
      - [Task 2: async-echo via Flor Components](#task-2-async-echo-via-flor-components)
      - [Task 3: async-echo with Flor Capabilities](#task-3-async-echo-with-flor-capabilities)
    - [Intro to Florete Forwarding](#intro-to-florete-forwarding)
      - [Task 4: async-echo over F-tunnels](#task-4-async-echo-over-f-tunnels)
  - [Development Environment](#development-environment)

<!-- /code_chunk_output -->

## Legal

In order to contribute code to ReteLabs open-source projects, you need to sign Contributor License Agreement.

TODO: define proper legal guide, CLA (rete-labs/onboarding#1)

## Technical

### Rust Basics

- Read [Rust Book](https://doc.rust-lang.org/book/)
- Work through [Tokio Tutorial](https://tokio.rs/tokio/tutorial)

#### Task 1: async-echo

Implement echo client-server over TCP using Tokio:
- v1: simple client and server with async client handler
- v2: bound number of accepted clients in the server
- v3: use async Stream API to generate messages in the client

### Intro to Flor

#### Task 2: async-echo via Flor Components

Use Flor Сomponent API to implement async-echo:
- client and server should be implemented as Flor components
- add deploy declarations to instantiate either client or server component in a single async-echo binary

#### Task 3: async-echo with Flor Capabilities

Use Flor Capabilities API to implement advanced async-echo.

TODO: define details of task 3 to practice Flor Capabilities API (rete-labs/onboarding#3)

### Intro to Florete Forwarding

#### Task 4: async-echo over F-tunnels

Use Florete Portal API (publish/connect capabilities) and F-tunnels (Florete Tunnels) instead of TCP streams to implement async-echo.

## Development Environment

TODO: describe setup of development environment (rete-labs/onboarding#4)
