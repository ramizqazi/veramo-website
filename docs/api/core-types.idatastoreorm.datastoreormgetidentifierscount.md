---
id: core-types.idatastoreorm.datastoreormgetidentifierscount
title: IDataStoreORM.dataStoreORMGetIdentifiersCount() method
hide_title: true
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## IDataStoreORM.dataStoreORMGetIdentifiersCount() method

> This API is provided as a preview for developers and may change based on feedback that we receive. Do not use this API in a production environment.

> Warning: This API is now obsolete.
>
> This will be removed in future versions of this plugin interface. This API may change without a BREAKING CHANGE notice.

Tries to obtain a count of [IIdentifiers](./core-types.iidentifier.md) that match the given filter. The origin of these identifiers is from any credential / presentation or message that was successfully processed by this agent.

If the same database is used for implementations of [AbstractDIDStore](./did-manager.abstractdidstore.md), then these identifiers can also come from [didManagerCreate](./core-types.ididmanager.didmanagercreate.md) or [didManagerImport](./core-types.ididmanager.didmanagerimport.md) operations.

<b>Signature:</b>

```typescript
dataStoreORMGetIdentifiersCount(args: FindIdentifiersArgs, context: AuthorizedDIDContext): Promise<number>;
```

## Parameters

| Parameter | Type                                                         | Description                                                                                                                                                                       |
| --------- | ------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| args      | [FindIdentifiersArgs](./core-types.findidentifiersargs.md)   | The filter to apply when querying                                                                                                                                                 |
| context   | [AuthorizedDIDContext](./core-types.authorizeddidcontext.md) | Can be used to signal that only a particular DID is authorized to perform this operation. This will cause the result to only contain data that this DID should be able to access. |

<b>Returns:</b>

Promise&lt;number&gt;
