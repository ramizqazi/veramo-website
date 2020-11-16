---
id: daf-identity-manager.identitymanager.identitymanagerremoveservice
title: IdentityManager.identityManagerRemoveService() method
hide_title: true
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## IdentityManager.identityManagerRemoveService() method

Removes a service from a DID Document

<b>Signature:</b>

```typescript
identityManagerRemoveService({ did, id, options }: IIdentityManagerRemoveServiceArgs, context: IAgentContext<IKeyManager>): Promise<any>;
```

## Parameters

| Parameter            | Type                                                                                                  | Description |
| -------------------- | ----------------------------------------------------------------------------------------------------- | ----------- |
| { did, id, options } | [IIdentityManagerRemoveServiceArgs](./daf-core.iidentitymanagerremoveserviceargs.md)                  |             |
| context              | [IAgentContext](./daf-core.iagentcontext.md) &lt;[IKeyManager](./daf-core.ikeymanager.md)<!-- -->&gt; |             |

<b>Returns:</b>

Promise&lt;any&gt;

identity provider specific response. Can be txHash, etc,