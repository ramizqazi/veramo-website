---
id: daf-core.w3ccredential
title: W3CCredential interface
hide_title: true
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## W3CCredential interface

W3CCredential [https://github.com/decentralized-identity/did-jwt-vc](https://github.com/decentralized-identity/did-jwt-vc)

<b>Signature:</b>

```typescript
export interface W3CCredential
```

## Properties

| Property                                                           | Type                                 | Description |
| ------------------------------------------------------------------ | ------------------------------------ | ----------- |
| ["@context"](./daf-core.w3ccredential.__context_.md)               | string\[\]                           |             |
| [credentialStatus](./daf-core.w3ccredential.credentialstatus.md)   | { id: string; type: string; }        |             |
| [credentialSubject](./daf-core.w3ccredential.credentialsubject.md) | { id?: string; \[x: string\]: any; } |             |
| [expirationDate](./daf-core.w3ccredential.expirationdate.md)       | string                               |             |
| [id](./daf-core.w3ccredential.id.md)                               | string                               |             |
| [issuanceDate](./daf-core.w3ccredential.issuancedate.md)           | string                               |             |
| [issuer](./daf-core.w3ccredential.issuer.md)                       | { id: string; \[x: string\]: any; }  |             |
| [type](./daf-core.w3ccredential.type.md)                           | string\[\]                           |             |