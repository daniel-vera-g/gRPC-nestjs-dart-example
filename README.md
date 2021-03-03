# gRPC NestJS & Dart example

> gRPC sample application using NestJS as backend and dart as client technology

Note: This repo is only meant as example for the tech stack & not to be used in production.

## Concept

1. Client makes search term request for youtube video.
2. gRPC server get's youtube video and streams it back to the client.
3. Client either only saves it(default) or uses the system video player to play the video(`-p` - Flag)

## Stack 🔧

1. [Dart](https://dart.dev/tutorials/server/cmdline) based command line application as gRPC client.
2. [NestJS](https://docs.nestjs.com/microservices/grpc)(+ NodeJs, Typescript, ...) as gRPC server.
3. [node-ytdl-core](https://github.com/fent/node-ytdl-core) to get the youtube videos.

## gRPC 🤔?

gRPC introduces himself as a "[...] high performance, open source universal RPC framework" that has the advantage of "[...] advanced streaming and connection features which help save bandwidth, do more over fewer TCP connections and save CPU usage and battery life". It has advantages like:

1. Low latency, highly scalable, distributed systems.
1. Developing mobile clients which are communicating to a cloud server.
1. Designing a new protocol that needs to be accurate, efficient and language independent.
1. Layered design to enable extension eg. authentication, load balancing, logging and monitoring etc.

[gRPC-FAQ](https://grpc.io/docs/what-is-grpc/faq/#why-would-i-want-to-use-grpc)

## TODO

> See Issue tracker