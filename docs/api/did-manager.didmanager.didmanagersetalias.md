---
id: did-manager.didmanager.didmanagersetalias
title: DIDManager.didManagerSetAlias() method
hide_title: true
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## DIDManager.didManagerSetAlias() method

Sets identifier alias

<b>Signature:</b>

```typescript
didManagerSetAlias({ did, alias }: IDIDManagerSetAliasArgs, context: IAgentContext<IKeyManager>): Promise<boolean>;
```

## Parameters

| Parameter      | Type                                                                                             | Description                                                                                                                                                           |
| -------------- | ------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| { did, alias } | [IDIDManagerSetAliasArgs](./core-types.ididmanagersetaliasargs.md)                               |                                                                                                                                                                       |
| context        | [IAgentContext](./core-types.iagentcontext.md)&lt;[IKeyManager](./core-types.ikeymanager.md)&gt; | <a href="/docs/agent/plugins#executing-plugin-methods">Execution context</a>. Requires <code>agent</code> that has [IKeyManager](./core-types.ikeymanager.md) methods |

<b>Returns:</b>

Promise&lt;boolean&gt;
