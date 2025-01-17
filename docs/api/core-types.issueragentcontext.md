---
id: core-types.issueragentcontext
title: IssuerAgentContext type
hide_title: true
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## IssuerAgentContext type

> This API is provided as a preview for developers and may change based on feedback that we receive. Do not use this API in a production environment.

Represents the requirements that this plugin has. The agent that is using this plugin is expected to provide these methods.

This interface can be used for static type checks, to make sure your application is properly initialized.

<b>Signature:</b>

```typescript
export type IssuerAgentContext = IAgentContext<
  IResolver &
    Pick<IDIDManager, 'didManagerGet' | 'didManagerFind'> &
    Pick<IDataStore, 'dataStoreSaveVerifiablePresentation' | 'dataStoreSaveVerifiableCredential'> &
    Pick<IKeyManager, 'keyManagerGet' | 'keyManagerSign'>
>
```

<b>References:</b> [IAgentContext](./core-types.iagentcontext.md), [IResolver](./core-types.iresolver.md), [IDIDManager](./core-types.ididmanager.md), [IDataStore](./core-types.idatastore.md), [IKeyManager](./core-types.ikeymanager.md)
