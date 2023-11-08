# mubel-api-grpc

## Introduction
This repository contains the Protocol Buffers definition for the Mubel gRPC API, enabling efficient and scalable communication between Mubel clients and the Mubel server.

## Features
- Define service interfaces in a language-neutral, platform-neutral format with Protocol Buffers.
- Leverage gRPC for low-latency, high-throughput communication.
- Automatically generate client and server code.

## Requirements
- Protocol Buffer Compiler (protoc) version 3.x
- gRPC compatible language support for client/server generation.

## Installation
Clone the repository and use the Protocol Buffer Compiler to generate your desired language stubs:

```
git clone https://github.com/helun/mubel-api-grpc.git
cd mubel-api-grpc
protoc --proto_path=api/ --<language>_out=<output_path> api/*.proto
```

## Usage
After generating the stubs, you can incorporate them into your client or server code to start making RPC calls. For example:
```java

// Java client stub usage
// TODO

```