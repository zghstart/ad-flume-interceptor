# AD Flume Interceptor

A custom Apache Flume interceptor for ad-related data processing.

## Overview

This project provides a custom interceptor for Apache Flume that can be used to process advertising data streams. The interceptor is designed to work with Flume agents to modify, filter, or enrich events as they flow through the system.

## Project Details

- **Group ID**: com.zetyun.tiger
- **Artifact ID**: ad-flume-interceptor
- **Version**: 1.0-SNAPSHOT
- **Java Version**: 17

## Dependencies

- Apache Flume Core (1.9.0) - provided scope

## Build

To build the project, use Maven:

```bash
mvn clean package
```

## Usage

The interceptor can be configured in your Flume agent configuration file to intercept and process events flowing through Flume channels.

## License

This project is licensed under the MIT License - see the LICENSE file for details.