---
id: core.iagent
title: IAgent interface
hide_title: true
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## IAgent interface

Agent that can execute methods

<b>Signature:</b>

```typescript
export interface IAgent extends IAgentBase
```

<b>Extends:</b> [IAgentBase](./core.iagentbase.md)

## Properties

| Property                            | Type                                                                     | Description |
| ----------------------------------- | ------------------------------------------------------------------------ | ----------- |
| [emit](./core.iagent.emit.md)       | (eventType: string, data: any) =&gt; Promise&lt;void&gt;                 |             |
| [execute](./core.iagent.execute.md) | &lt;A = any, R = any&gt;(method: string, args: A) =&gt; Promise&lt;R&gt; |             |