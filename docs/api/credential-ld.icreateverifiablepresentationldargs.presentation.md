---
id: credential-ld.icreateverifiablepresentationldargs.presentation
title: ICreateVerifiablePresentationLDArgs.presentation property
hide_title: true
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## ICreateVerifiablePresentationLDArgs.presentation property

> This API is provided as a preview for developers and may change based on feedback that we receive. Do not use this API in a production environment.

The json payload of the Presentation according to the [canonical model](https://www.w3.org/TR/vc-data-model/#presentations).

The signer of the Presentation is chosen based on the `holder` property of the `presentation`

`@context`, `type` and `issuanceDate` will be added automatically if omitted.

<b>Signature:</b>

```typescript
presentation: PresentationPayload
```
