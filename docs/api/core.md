---
id: core
title: core package
hide_title: true
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## Veramo Core

Provides [Agent](./core.agent.md) implementation

## Classes

| Class                                        | Description                                                                                                                                                                                                                                                                                                                                  |
| -------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Agent](./core.agent.md)                     | <p>Provides a common context for all plugin methods.</p><p>This is the main entry point into the API of the DID Agent Framework. When plugins are installed, they extend the API of the agent and the methods they provide can all use the common context so that plugins can build on top of each other and create a richer experience.</p> |
| [ValidationError](./core.validationerror.md) | <p>Represents a Schema validation error.</p><p>This can occur when a method of the agent is invoked with certain parameters or the returned value doesn't match the declared plugin schema.</p>                                                                                                                                              |

## Functions

| Function                                      | Description                                                                                      |
| --------------------------------------------- | ------------------------------------------------------------------------------------------------ |
| [createAgent(options)](./core.createagent.md) | Helper function to create a new instance of the [Agent](./core.agent.md) class with correct type |
