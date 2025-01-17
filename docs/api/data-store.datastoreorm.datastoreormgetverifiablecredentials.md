---
id: data-store.datastoreorm.datastoreormgetverifiablecredentials
title: DataStoreORM.dataStoreORMGetVerifiableCredentials() method
hide_title: true
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## DataStoreORM.dataStoreORMGetVerifiableCredentials() method

> This API is provided as a preview for developers and may change based on feedback that we receive. Do not use this API in a production environment.

<b>Signature:</b>

```typescript
dataStoreORMGetVerifiableCredentials(args: FindArgs<TCredentialColumns>, context: AuthorizedDIDContext): Promise<Array<UniqueVerifiableCredential>>;
```

## Parameters

| Parameter | Type                                                                                                 | Description |
| --------- | ---------------------------------------------------------------------------------------------------- | ----------- |
| args      | [FindArgs](./core-types.findargs.md)&lt;[TCredentialColumns](./core-types.tcredentialcolumns.md)&gt; |             |
| context   | [AuthorizedDIDContext](./core-types.authorizeddidcontext.md)                                         |             |

<b>Returns:</b>

Promise&lt;Array&lt;[UniqueVerifiableCredential](./core-types.uniqueverifiablecredential.md)&gt;&gt;
