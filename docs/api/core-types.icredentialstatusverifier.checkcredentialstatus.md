---
id: core-types.icredentialstatusverifier.checkcredentialstatus
title: ICredentialStatusVerifier.checkCredentialStatus() method
hide_title: true
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## ICredentialStatusVerifier.checkCredentialStatus() method

> This API is provided as a preview for developers and may change based on feedback that we receive. Do not use this API in a production environment.

Checks the status of a [Verifiable Credential](./core-types.verifiablecredential.md).

<b>Signature:</b>

```typescript
checkCredentialStatus(args: ICheckCredentialStatusArgs, context: IAgentContext<IResolver>): Promise<CredentialStatus>;
```

## Parameters

| Parameter | Type                                                                                         | Description                                                              |
| --------- | -------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------ |
| args      | [ICheckCredentialStatusArgs](./core-types.icheckcredentialstatusargs.md)                     | The credential to be checked, along with the DID document of the issuer. |
| context   | [IAgentContext](./core-types.iagentcontext.md)&lt;[IResolver](./core-types.iresolver.md)&gt; | \*RESERVED\* This is filled by the framework when the method is called.  |

<b>Returns:</b>

Promise&lt;[CredentialStatus](./core-types.credentialstatus.md)&gt;
