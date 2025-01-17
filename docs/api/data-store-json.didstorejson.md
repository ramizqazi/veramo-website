---
id: data-store-json.didstorejson
title: DIDStoreJson class
hide_title: true
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## DIDStoreJson class

> This API is provided as a preview for developers and may change based on feedback that we receive. Do not use this API in a production environment.

An implementation of [AbstractDIDStore](./did-manager.abstractdidstore.md) that uses a JSON object to store the relationships between DIDs, their providers and controllers and their keys and services as they are known and managed by a Veramo agent.

An instance of this class can be used by [DIDManager](./did-manager.didmanager.md) as the data storage layer.

This class must be initialized with a [VeramoJsonStore](./data-store-json.veramojsonstore.md), which serves as the JSON object storing data in memory as well as providing an update notification callback to persist this data. For correct usage, this MUST use the same [VeramoJsonStore](./data-store-json.veramojsonstore.md) instance as the one used by [KeyManager](./key-manager.keymanager.md).

This API may change without a BREAKING CHANGE notice.

<b>Signature:</b>

```typescript
export declare class DIDStoreJson extends AbstractDIDStore
```

<b>Extends:</b> [AbstractDIDStore](./did-manager.abstractdidstore.md)

## Constructors

| Constructor                                                                 | Modifiers | Description                                                                           |
| --------------------------------------------------------------------------- | --------- | ------------------------------------------------------------------------------------- |
| [(constructor)(jsonStore)](./data-store-json.didstorejson._constructor_.md) |           | <b><i>(BETA)</i></b> Constructs a new instance of the <code>DIDStoreJson</code> class |

## Methods

| Method                                                                        | Modifiers | Description          |
| ----------------------------------------------------------------------------- | --------- | -------------------- |
| [deleteDID({ did })](./data-store-json.didstorejson.deletedid.md)             |           | <b><i>(BETA)</i></b> |
| [getDID({ did, alias, provider, })](./data-store-json.didstorejson.getdid.md) |           | <b><i>(BETA)</i></b> |
| [importDID(args)](./data-store-json.didstorejson.importdid.md)                |           | <b><i>(BETA)</i></b> |
| [listDIDs(args)](./data-store-json.didstorejson.listdids.md)                  |           | <b><i>(BETA)</i></b> |
