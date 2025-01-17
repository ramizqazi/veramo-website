---
id: core-types.credentialstatus
title: CredentialStatus type
hide_title: true
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## CredentialStatus type

> This API is provided as a preview for developers and may change based on feedback that we receive. Do not use this API in a production environment.

Represents the result of a status check.

Implementations MUST populate the `revoked` boolean property, but they can return additional metadata that is method specific.

<b>Signature:</b>

```typescript
export type CredentialStatus = {
  revoked: boolean
  [x: string]: any
}
```
