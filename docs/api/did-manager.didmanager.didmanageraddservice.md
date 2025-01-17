---
id: did-manager.didmanager.didmanageraddservice
title: DIDManager.didManagerAddService() method
hide_title: true
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## DIDManager.didManagerAddService() method

Adds a service to a DID Document

<b>Signature:</b>

```typescript
didManagerAddService({ did, service, options }: IDIDManagerAddServiceArgs, context: IAgentContext<IKeyManager>): Promise<any>;
```

## Parameters

| Parameter                 | Type                                                                                             | Description |
| ------------------------- | ------------------------------------------------------------------------------------------------ | ----------- |
| { did, service, options } | [IDIDManagerAddServiceArgs](./core-types.ididmanageraddserviceargs.md)                           |             |
| context                   | [IAgentContext](./core-types.iagentcontext.md)&lt;[IKeyManager](./core-types.ikeymanager.md)&gt; |             |

<b>Returns:</b>

Promise&lt;any&gt;

identifier provider specific response. Can be txHash, etc,
