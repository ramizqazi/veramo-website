---
id: data-store-json.credentialtableentry
title: CredentialTableEntry interface
hide_title: true
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## CredentialTableEntry interface

> This API is provided as a preview for developers and may change based on feedback that we receive. Do not use this API in a production environment.

This is used internally by [DataStoreJson](./data-store-json.datastorejson.md) to represent a Verifiable Credential in a way that facilitates querying using the [IDataStoreORM](./core.idatastoreorm.md) interface.

This API may change in future versions without a BREAKING CHANGE notice.

<b>Signature:</b>

```typescript
export interface CredentialTableEntry
```

## Properties

| Property                                                                             | Type                                                         | Description                            |
| ------------------------------------------------------------------------------------ | ------------------------------------------------------------ | -------------------------------------- |
| [canonicalCredential](./data-store-json.credentialtableentry.canonicalcredential.md) | [W3CVerifiableCredential](./core.w3cverifiablecredential.md) | <b><i>(BETA)</i></b>                   |
| [context](./data-store-json.credentialtableentry.context.md)                         | string\[\]                                                   | <b><i>(BETA)</i></b>                   |
| [expirationDate?](./data-store-json.credentialtableentry.expirationdate.md)          | Date                                                         | <b><i>(BETA)</i></b> <i>(Optional)</i> |
| [hash](./data-store-json.credentialtableentry.hash.md)                               | string                                                       | <b><i>(BETA)</i></b>                   |
| [id?](./data-store-json.credentialtableentry.id.md)                                  | string                                                       | <b><i>(BETA)</i></b> <i>(Optional)</i> |
| [issuanceDate?](./data-store-json.credentialtableentry.issuancedate.md)              | Date                                                         | <b><i>(BETA)</i></b> <i>(Optional)</i> |
| [issuer](./data-store-json.credentialtableentry.issuer.md)                           | string                                                       | <b><i>(BETA)</i></b>                   |
| [parsedCredential](./data-store-json.credentialtableentry.parsedcredential.md)       | [VerifiableCredential](./core.verifiablecredential.md)       | <b><i>(BETA)</i></b>                   |
| [subject?](./data-store-json.credentialtableentry.subject.md)                        | string                                                       | <b><i>(BETA)</i></b> <i>(Optional)</i> |
| [type](./data-store-json.credentialtableentry.type.md)                               | string\[\]                                                   | <b><i>(BETA)</i></b>                   |