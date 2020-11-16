---
id: daf-identity-manager.identitymanager.identitymanageraddkey
title: IdentityManager.identityManagerAddKey() method
hide_title: true
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## IdentityManager.identityManagerAddKey() method

Adds a key to a DID Document

<b>Signature:</b>

```typescript
identityManagerAddKey({ did, key, options }: IIdentityManagerAddKeyArgs, context: IAgentContext<IKeyManager>): Promise<any>;
```

## Parameters

| Parameter             | Type                                                                                                  | Description |
| --------------------- | ----------------------------------------------------------------------------------------------------- | ----------- |
| { did, key, options } | [IIdentityManagerAddKeyArgs](./daf-core.iidentitymanageraddkeyargs.md)                                |             |
| context               | [IAgentContext](./daf-core.iagentcontext.md) &lt;[IKeyManager](./daf-core.ikeymanager.md)<!-- -->&gt; |             |

<b>Returns:</b>

Promise&lt;any&gt;

identity provider specific response. Can be txHash, etc,