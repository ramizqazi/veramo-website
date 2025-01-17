---
id: core-types.icredentialissuer.createverifiablecredential
title: ICredentialIssuer.createVerifiableCredential() method
hide_title: true
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## ICredentialIssuer.createVerifiableCredential() method

Creates a Verifiable Credential. The payload, signer and format are chosen based on the `args` parameter.

<b>Signature:</b>

```typescript
createVerifiableCredential(args: ICreateVerifiableCredentialArgs, context: IssuerAgentContext): Promise<VerifiableCredential>;
```

## Parameters

| Parameter | Type                                                                               | Description                                                                                  |
| --------- | ---------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| args      | [ICreateVerifiableCredentialArgs](./core-types.icreateverifiablecredentialargs.md) | Arguments necessary to create the Presentation.                                              |
| context   | [IssuerAgentContext](./core-types.issueragentcontext.md)                           | This reserved param is automatically added and handled by the framework, \*do not override\* |

<b>Returns:</b>

Promise&lt;[VerifiableCredential](./core-types.verifiablecredential.md)&gt;

- a promise that resolves to the [VerifiableCredential](./core-types.verifiablecredential.md) that was requested or rejects with an error if there was a problem with the input or while getting the key to sign

## Remarks

Please see [Verifiable Credential data model](https://www.w3.org/TR/vc-data-model/#credentials)
