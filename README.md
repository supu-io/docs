# supu.io : docs

1. [Introduction](#introduction)
2. [Subprojects](#subprojects)
3. [Tools & Utilities](#tools-utilities)
4. [Developer's documentation](#developers-documentation)

This is the documentation for *supu.io*, a curated and community driven list
of technical talks.

## Introduction

supu.io is not a single piece of software. It is more a platform based on a
microservices paradigm and designed to minimize the complexity of the system
and maximize the decoupling between its components.

Please, make sure you read our [architecture](architecture/architecture.md) documents
to see how these different pieces of software, called *microservices*, work
together to keep the system up & running, and their

[configuration & deployment](developers/deploy.md) before you start building or hacking
in one component by yourself.

* [Project's Roadmap](roadmap.md)
* [Platform Arquitecture](architecture/architecture.md)
* [What we have now](architecture/architecture.md#what-we-have-now)
* [What we want to build](architecture/architecture.md#what-we-want-to-build)

## Subprojects

For a simpler work organization, the [team](http://supu.io/about) behind
supu.io, usually group these components into subprojects according on its
main purpose.

supu.io current & active subprojects are:

* [api](subprojects/api.md) : Public APIs.
* [core](subprojects/core.md) : Business Logic & core libraries.

## Tools & Utilities

* [cli](tools/cli.md) : Manage supu.io from the command line.

## Developer's documentation

Are you willing to help on the development of supu.io? This is the section
you're looking for:

* [Development guidelines](developers/guidelines.md)
* [Deployment & Configuration](developers/deploy.md)
* [Requirements](developers/deploy.md#requirements)
* [Database creation](developers/deploy.md#database-creation)
* [Full-Text index creation](developers/deploy.md#full-text-index-creation)
* [Step by Step deployment guide]()


