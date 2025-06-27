# Artemis Protocol

This is the protocol monorepo for the **Artemis Cubesat** project. It contains communication protocols and interfaces used for setting up communication between different subsystems of the cubesat.

## Overview

The Artemis Protocol repository serves as a centralized location for all inter-subsystem communication protocols. Each subdirectory contains the protocol implementation for a specific subsystem pair.

## Current Protocols

### PDU ↔ OBC (Teensy)
- **Location**: `pdu/`
- **Description**: Power Distribution Unit to On-Board Computer communication protocol
- **Target Platform**: Teensy 4.1 microcontroller
- **Status**: ✅ Implemented

## Project Structure

```
artemis-protocol/
├── pdu/                    # PDU ↔ OBC protocol
│   └── pdu_protocol.h     # Protocol definitions and interfaces
└── README.md              # This file
```

## Future Protocols

Additional protocols will be added as the project develops:
- OBC ↔ Communications
- OBC ↔ Payload
- And others as needed

## Usage

Each protocol subdirectory contains the necessary header files, documentation, and implementation details for that specific subsystem communication interface.

For specific protocol usage, refer to the documentation within each subdirectory.
