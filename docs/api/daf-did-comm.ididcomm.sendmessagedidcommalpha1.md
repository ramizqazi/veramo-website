---
id: daf-did-comm.ididcomm.sendmessagedidcommalpha1
title: IDIDComm.sendMessageDIDCommAlpha1() method
hide_title: true
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## IDIDComm.sendMessageDIDCommAlpha1() method

> This API is provided as a preview for developers and may change based on feedback that we receive. Do not use this API in a production environment.

This is used to create a message according to the initial [DIDComm-js](https://github.com/decentralized-identity/DIDComm-js) implementation.

<b>Signature:</b>

```typescript
sendMessageDIDCommAlpha1(args: ISendMessageDIDCommAlpha1Args, context: IAgentContext<IIdentityManager & IKeyManager & IResolver & IMessageHandler>): Promise<IMessage>;
```

## Parameters

| Parameter | Type                                                                                                                                                                                                                                                             | Description                                                                                  |
| --------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| args      | [ISendMessageDIDCommAlpha1Args](./daf-did-comm.isendmessagedidcommalpha1args.md)                                                                                                                                                                                 | Arguments necessary for sending a DIDComm message                                            |
| context   | [IAgentContext](./daf-core.iagentcontext.md) &lt;[IIdentityManager](./daf-core.iidentitymanager.md) &amp; [IKeyManager](./daf-core.ikeymanager.md) &amp; [IResolver](./daf-core.iresolver.md) &amp; [IMessageHandler](./daf-core.imessagehandler.md)<!-- -->&gt; | This reserved param is automatically added and handled by the framework, \*do not override\* |

<b>Returns:</b>

Promise&lt;[IMessage](./daf-core.imessage.md) &gt;

## Remarks

Be advised that this spec is still not final and that this protocol may need to change.