# Awesome .NET Core Cloud Microservices

A collection of articles, frameworks, libraries, principles for building modern, clean, fault-tolerant, distributed microservice architecture on top of .NET Core. 

## Contents

* [Code Architecture](#codearchitecture)
* [Code Architecture Examples](#codearchitectureexamples)
* [Starter Kits](#starterkits)
* [Application Frameworks](#ApplicationFrameworks)
* [RPC](#rpc)
* [Service Discovery](#servicediscovery)
* [Distributed Transactions](#distributedtransactions)
* [Big Data](#bigdata)
* [Fault Tolerance](#faulttolerance)
* [Monitoring](#monitoring)
* [Logging](#logging)
* [Tracing](#tracing)
* [Security](#security)

* [IDE and tools](#ideandtools)
* [CI/CD](#ciandcd)

* [Books](#books)
* [Architecture video](#video)

## Code Architecture

### DDD and CQRS

**Microsoft guidelines:**

[Tackle Business Complexity in a Microservice with DDD and CQRS Patterns](https://docs.microsoft.com/en-us/dotnet/architecture/microservices/microservice-ddd-cqrs-patterns/)

[Design a DDD-oriented microservice](https://docs.microsoft.com/en-us/dotnet/architecture/microservices/microservice-ddd-cqrs-patterns/ddd-oriented-microservice)
[Implement a microservice domain model with .NET Core](https://docs.microsoft.com/en-us/dotnet/architecture/microservices/microservice-ddd-cqrs-patterns/net-core-microservice-domain-model)

## Starter Kits

### Templates

* [NET Boxed](https://github.com/Dotnet-Boxed/Templates)
* [Caju](https://github.com/ivanpaulovich/dotnet-new-caju) Service Template to help you build evolvable and maintainable applications. It follows the Clean Architecture Principles and built on Domain-Driven Design. This tool increases productivity on developing your next microservices.
* [Clean Architecture](https://github.com/ardalis/CleanArchitecture) A solution template that can be used to build Domain-Driven Design (DDD)-based or simply well-factored, SOLID applications using ASP.NET Core.

### Examples

* [Library](https://github.com/lamondlu/Library) example microservice project using .NET Core 2.0, DDD, CQRS, Event Sourcing, Redis and RabbitMQ
* [Manga](https://github.com/ivanpaulovich/clean-architecture-manga) Sample implementation of the Clean Architecture Principles with .NET Core. Use cases as central organizing structure, decoupled from frameworks and technology details. Built with small components that are developed and tested in isolation. See Caju for template.
* [eShopOnContainers](https://github.com/dotnet-architecture/eShopOnContainers)

## Application Frameworks

* [ViennaNET](https://github.com/Raiffeisen-DGTL/ViennaNET) Framework for quickly creating enterprise microservices on .NET Core. See [https://habr.com/ru/company/raiffeisenbank/blog/494830/](https://habr.com/ru/company/raiffeisenbank/blog/494830/)

### CQRS+ES

* [Async/await first CQRS+ES and DDD framework for .NET](https://github.com/eventflow/EventFlow)
* [Opinionated eventsourcing library](https://github.com/ProximoSrl/NStore)
* [A cqrs and event sourcing framework for dotnet core using akka.net](https://github.com/Lutando/Akkatecture)

### State Machine

* [A simple library for creating state machines in C# code](https://github.com/dotnet-state-machine/stateless)

### Feature toggles

* [Unleash FeatureToggle Client for .Net https://github.com/Unleash/unleash](https://github.com/stiano/unleash-client-dotnet)

### LINQ

* [A toolset for use the specification pattern in LINQ queries](https://github.com/navozenko/LinqSpecs)

## RPC

* [OpenAPI (f.k.a Swagger) Specification code generator. Supports C#, PowerShell, Go, Java, Node.js, TypeScript, Python, Ruby](https://github.com/Azure/autorest)

## Big Data

* [.NET for Apache® Spark™ makes Apache Spark™ easily accessible to .NET developers.](https://github.com/dotnet/spark)

## Monitoring

* [Backstage is an open platform for building developer portals](https://github.com/spotify/backstage)

## Logging

## Tracing

* [Tracing serverless .NET applications with AWS X-Ray](https://medium.com/@bacheric/tracing-serverless-net-applications-with-aws-x-ray-394b5e9f0d78)
* [aws-xray-dotnet-webapp](https://github.com/aws-samples/aws-xray-dotnet-webapp): An ASP.NET Web API application that has been instrumented for AWS X-Ray

* [C# client (tracer) for Jaeger https://jaegertracing.io/](https://github.com/jaegertracing/jaeger-client-csharp)

## Security

* [A cross-platform .NET Library for HashiCorp's Vault](https://github.com/VaultSharp/VaultSharp)

## IDE and Tools

* [Разработка с Docker на Windows Subsystem for Linux (WSL)](https://habr.com/ru/post/474346/)
* [A .NET Core global tool to display outdated NuGet packages in a project](https://github.com/jerriep/dotnet-outdated)
* [Thin wrapper around the "aws" command line interface for use with LocalStack](https://github.com/localstack/awscli-local)

## CI and CD

* [Generate documentation from Terraform modules in various output formats](https://github.com/segmentio/terraform-docs)

## Video

* [Avoiding Microservice Megadisasters - Jimmy Bogard](https://www.youtube.com/watch?v=gfh-VCTwMw8)
* [Data Consistency in Microservice Using Sagas](https://www.youtube.com/watch?reload=9&v=txlSrGVCK18)
* [Jimmy Bogard - Domain Driven Design: The Good Parts](https://www.youtube.com/watch?v=L3SvIKdLt88)
