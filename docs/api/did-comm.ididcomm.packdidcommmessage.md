---
id: did-comm.ididcomm.packdidcommmessage
title: IDIDComm.packDIDCommMessage() method
hide_title: true
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## IDIDComm.packDIDCommMessage() method

> This API is provided as a preview for developers and may change based on feedback that we receive. Do not use this API in a production environment.

Packs a [IDIDCommMessage](./did-comm.ididcommmessage.md) using one of the [DIDCommMessagePacking](./did-comm.didcommmessagepacking.md) options.

<b>Signature:</b>

```typescript
packDIDCommMessage(args: IPackDIDCommMessageArgs, context: IAgentContext<IDIDManager & IKeyManager & IResolver>): Promise<IPackedDIDCommMessage>;
```

## Parameters

| Parameter | Type                                                                                                                                                                                           | Description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| --------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| args      | [IPackDIDCommMessageArgs](./did-comm.ipackdidcommmessageargs.md)                                                                                                                               | an [IPackDIDCommMessageArgs](./did-comm.ipackdidcommmessageargs.md) object. \* args.message - [IDIDCommMessage](./did-comm.ididcommmessage.md) - the message to be packed \* args.packing - [DIDCommMessagePacking](./did-comm.didcommmessagepacking.md) - the packing method \* args.keyRef - Optional - string - either an <code>id</code> of a <code>kid</code> of a [IKey](./core-types.ikey.md) that will be used when <code>packing</code> is <code>jws</code> or <code>authcrypt</code>. \* args.options - [IDIDCommOptions](./did-comm.ididcommoptions.md) - optional options |
| context   | [IAgentContext](./core-types.iagentcontext.md)&lt;[IDIDManager](./core-types.ididmanager.md) &amp; [IKeyManager](./core-types.ikeymanager.md) &amp; [IResolver](./core-types.iresolver.md)&gt; | This method requires an agent that also has [IDIDManager](./core-types.ididmanager.md), [IKeyManager](./core-types.ikeymanager.md) and [IResolver](./core-types.iresolver.md) plugins in use. When calling this method, the <code>context</code> is supplied automatically by the framework.                                                                                                                                                                                                                                                                                          |

<b>Returns:</b>

Promise&lt;[IPackedDIDCommMessage](./did-comm.ipackeddidcommmessage.md)&gt;

a Promise that resolves to an object containing the serialized packed `message` string

This API may change without a BREAKING CHANGE notice.
