---
id: did-comm.ididcommtransport
title: IDIDCommTransport interface
hide_title: true
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## IDIDCommTransport interface

> This API is provided as a preview for developers and may change based on feedback that we receive. Do not use this API in a production environment.

Common interface for transports that can be used in the [DIDComm](./did-comm.didcomm.md) module.

<b>Signature:</b>

```typescript
export interface IDIDCommTransport
```

## Properties

| Property                                 | Type   | Description                                                                                                                              |
| ---------------------------------------- | ------ | ---------------------------------------------------------------------------------------------------------------------------------------- |
| [id](./did-comm.ididcommtransport.id.md) | string | <b><i>(BETA)</i></b> Identifier of this transport that can be used in case the message thread supports reusing the transport connection. |

## Methods

| Method                                                                            | Description                                                                                                                                                    |
| --------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [isServiceSupported(service)](./did-comm.ididcommtransport.isservicesupported.md) | <b><i>(BETA)</i></b> Returns <code>true</code> if this transport is suitable for the provided DID Document service section, otherwise <code>false</code>.      |
| [send(service, message)](./did-comm.ididcommtransport.send.md)                    | <b><i>(BETA)</i></b> Sends the provided raw message (without further processing) to the service endpoint defined in the provided DID Document service section. |