---
id: data-store.keystore
title: KeyStore class
hide_title: true
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## KeyStore class

An implementation of [AbstractKeyStore](./key-manager.abstractkeystore.md) that uses a TypeORM database to store the relationships between keys, their IDs, aliases and [KMS implementations](./key-manager.abstractkeymanagementsystem.md), as they are known and managed by a Veramo agent.

An instance of this class can be used by [KeyManager](./key-manager.keymanager.md) as the data storage layer.

To make full use of this class, it should use the same database as the one used by [DIDStore](./data-store.didstore.md).

<b>Signature:</b>

```typescript
export declare class KeyStore extends AbstractKeyStore
```

<b>Extends:</b> [AbstractKeyStore](./key-manager.abstractkeystore.md)

## Constructors

| Constructor                                                           | Modifiers | Description                                                  |
| --------------------------------------------------------------------- | --------- | ------------------------------------------------------------ |
| [(constructor)(dbConnection)](./data-store.keystore._constructor_.md) |           | Constructs a new instance of the <code>KeyStore</code> class |

## Methods

| Method                                                   | Modifiers | Description |
| -------------------------------------------------------- | --------- | ----------- |
| [deleteKey({ kid })](./data-store.keystore.deletekey.md) |           |             |
| [getKey({ kid })](./data-store.keystore.getkey.md)       |           |             |
| [importKey(args)](./data-store.keystore.importkey.md)    |           |             |
| [listKeys(args)](./data-store.keystore.listkeys.md)      |           |             |
