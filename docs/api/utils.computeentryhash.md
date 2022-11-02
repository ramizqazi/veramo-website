---
id: utils.computeentryhash
title: computeEntryHash() function
hide_title: true
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## computeEntryHash() function

> This API is provided as a preview for developers and may change based on feedback that we receive. Do not use this API in a production environment.

Computes a hash for a given credential or presentation. This hash is usable as an internal ID for database indexing

<b>Signature:</b>

```typescript
export declare function computeEntryHash(
  input: W3CVerifiableCredential | W3CVerifiablePresentation | IMessage,
): string
```

## Parameters

| Parameter | Type                                                                                                                                                                       | Description                                                                                               |
| --------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------- |
| input     | [W3CVerifiableCredential](./core.w3cverifiablecredential.md) &#124; [W3CVerifiablePresentation](./core.w3cverifiablepresentation.md) &#124; [IMessage](./core.imessage.md) | the Credential or Presentation whose hash is neeededThis API may change without a BREAKING CHANGE notice. |

<b>Returns:</b>

string