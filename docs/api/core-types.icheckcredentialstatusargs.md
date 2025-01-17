---
id: core-types.icheckcredentialstatusargs
title: ICheckCredentialStatusArgs interface
hide_title: true
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## ICheckCredentialStatusArgs interface

> This API is provided as a preview for developers and may change based on feedback that we receive. Do not use this API in a production environment.

Arguments for calling [checkCredentialStatus](./core-types.icredentialstatusverifier.checkcredentialstatus.md).

The credential whose status should be checked and the DID document of the credential issuer.

See [Credential Status](https://www.w3.org/TR/vc-data-model/#status)

This API may change without a BREAKING CHANGE notice.

<b>Signature:</b>

```typescript
export interface ICheckCredentialStatusArgs
```

## Properties

| Property                                                                               | Modifiers | Type                                                         | Description                                                                                                                                                                                      |
| -------------------------------------------------------------------------------------- | --------- | ------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [credential](./core-types.icheckcredentialstatusargs.credential.md)                    |           | [VerifiableCredential](./core-types.verifiablecredential.md) | <b><i>(BETA)</i></b> The credential whose status needs to be checked                                                                                                                             |
| [didDocumentOverride?](./core-types.icheckcredentialstatusargs.diddocumentoverride.md) |           | DIDDocument                                                  | <b><i>(BETA)</i></b> <i>(Optional)</i> The DID document of the issuer. This can be used in case the DID Document is already resolver, to avoid a potentially expensive DID resolution operation. |
