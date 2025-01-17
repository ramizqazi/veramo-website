---
id: core-types.ididmanager.didmanagergetbyalias
title: IDIDManager.didManagerGetByAlias() method
hide_title: true
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## IDIDManager.didManagerGetByAlias() method

Returns a specific identifier by alias

<b>Signature:</b>

```typescript
didManagerGetByAlias(args: IDIDManagerGetByAliasArgs): Promise<IIdentifier>;
```

## Parameters

| Parameter | Type                                                                   | Description                               |
| --------- | ---------------------------------------------------------------------- | ----------------------------------------- |
| args      | [IDIDManagerGetByAliasArgs](./core-types.ididmanagergetbyaliasargs.md) | Required. Arguments to get the identifier |

<b>Returns:</b>

Promise&lt;[IIdentifier](./core-types.iidentifier.md)&gt;

## Example

```typescript
const identifier = await agent.didManagerGetByAlias({
  alias: 'charlie',
  provider: 'did:ethr:goerli',
})
```
