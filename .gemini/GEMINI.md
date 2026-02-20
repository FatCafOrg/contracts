# @factcaf-org/contracts

This project contains protocol buffer definitions and generated TypeScript contracts for FatCaf microservices.

## Project Context
- **Name:** @factcaf-org/contracts
- **Framework:** NestJS (via `ts-proto`)
- **Main Goal:** Define and generate shared types for authentication and other services.

## Development Workflow
- **Protocol Buffers:** Defined in the `proto/` directory.
- **Generated Code:** Output to the `gen/` directory using `ts-proto`.

## Commands
- `npm run generate`: Re-generates TypeScript files from proto definitions.

## Project Guidelines
- Do not manually edit files in the `gen/` directory.
