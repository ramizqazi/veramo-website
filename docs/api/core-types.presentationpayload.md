---
id: core-types.presentationpayload
title: PresentationPayload interface
hide_title: true
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## PresentationPayload interface

> This API is provided as a preview for developers and may change based on feedback that we receive. Do not use this API in a production environment.

Used as input when creating Verifiable Presentations

This API may change without prior notice.

<b>Signature:</b>

```typescript
export interface PresentationPayload
```

## Properties

| Property                                                                          | Modifiers | Type                                                                   | Description                            |
| --------------------------------------------------------------------------------- | --------- | ---------------------------------------------------------------------- | -------------------------------------- |
| ["@context"?](./core-types.presentationpayload.__context_.md)                     |           | [ContextType](./core-types.contexttype.md)                             | <b><i>(BETA)</i></b> <i>(Optional)</i> |
| [expirationDate?](./core-types.presentationpayload.expirationdate.md)             |           | [DateType](./core-types.datetype.md)                                   | <b><i>(BETA)</i></b> <i>(Optional)</i> |
| [holder](./core-types.presentationpayload.holder.md)                              |           | string                                                                 | <b><i>(BETA)</i></b>                   |
| [id?](./core-types.presentationpayload.id.md)                                     |           | string                                                                 | <b><i>(BETA)</i></b> <i>(Optional)</i> |
| [issuanceDate?](./core-types.presentationpayload.issuancedate.md)                 |           | [DateType](./core-types.datetype.md)                                   | <b><i>(BETA)</i></b> <i>(Optional)</i> |
| [type?](./core-types.presentationpayload.type.md)                                 |           | string\[\]                                                             | <b><i>(BETA)</i></b> <i>(Optional)</i> |
| [verifiableCredential?](./core-types.presentationpayload.verifiablecredential.md) |           | [W3CVerifiableCredential](./core-types.w3cverifiablecredential.md)\[\] | <b><i>(BETA)</i></b> <i>(Optional)</i> |
| [verifier?](./core-types.presentationpayload.verifier.md)                         |           | string\[\]                                                             | <b><i>(BETA)</i></b> <i>(Optional)</i> |
