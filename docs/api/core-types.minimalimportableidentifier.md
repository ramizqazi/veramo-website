---
id: core-types.minimalimportableidentifier
title: MinimalImportableIdentifier type
hide_title: true
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## MinimalImportableIdentifier type

Represents the minimum amount of information needed to import an [IIdentifier](./core-types.iidentifier.md).

<b>Signature:</b>

```typescript
export type MinimalImportableIdentifier = {
  keys: Array<MinimalImportableKey>
  services?: Array<IService>
} & Omit<IIdentifier, 'keys' | 'services'>
```

<b>References:</b> [MinimalImportableKey](./core-types.minimalimportablekey.md), [IService](./core-types.iservice.md), [IIdentifier](./core-types.iidentifier.md)
