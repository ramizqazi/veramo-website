---
id: core.createagent
title: createAgent() function
hide_title: true
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## createAgent() function

Helper function to create a new instance of the [Agent](./core.agent.md) class with correct type

<b>Signature:</b>

```typescript
export declare function createAgent<T extends IPluginMethodMap, C = Record<string, any>>(
  options: IAgentOptions & {
    context?: C
  },
): TAgent<T> & {
  context?: C
}
```

## Parameters

| Parameter | Type                                                                  | Description                 |
| --------- | --------------------------------------------------------------------- | --------------------------- |
| options   | [IAgentOptions](./core-types.iagentoptions.md) &amp; { context?: C; } | Agent configuration options |

<b>Returns:</b>

[TAgent](./core-types.tagent.md)&lt;T&gt; &amp; { context?: C; }

configured agent

## Remarks

Use [TAgent](./core-types.tagent.md) to configure agent type (list of available methods) for autocomplete in IDE

## Example

```typescript
import { createAgent, IResolver, IMessageHandler } from '@veramo/core'
import { AgentRestClient } from '@veramo/remote-client'
import { CredentialIssuer, ICredentialIssuer } from '@veramo/credential-w3c'
const agent = createAgent<IResolver & IMessageHandler & ICredentialIssuer>({
  plugins: [
    new CredentialIssuer(),
    new AgentRestClient({
      url: 'http://localhost:3002/agent',
      enabledMethods: ['resolveDid', 'handleMessage'],
    }),
  ],
})
```
