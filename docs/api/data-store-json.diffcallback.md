---
id: data-store-json.diffcallback
title: DiffCallback type
hide_title: true
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## DiffCallback type

> This API is provided as a preview for developers and may change based on feedback that we receive. Do not use this API in a production environment.

A callback method that is called when the data stored in a [VeramoJsonCache](./data-store-json.veramojsoncache.md) is updated.

<b>Signature:</b>

```typescript
export type DiffCallback = (
  oldState: Partial<VeramoJsonCache>,
  newState: Partial<VeramoJsonCache>,
) => Promise<void>
```

<b>References:</b> [VeramoJsonCache](./data-store-json.veramojsoncache.md)
