---
id: did-discovery.ididdiscoverydiscoverdidresult
title: IDIDDiscoveryDiscoverDidResult interface
hide_title: true
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## IDIDDiscoveryDiscoverDidResult interface

> This API is provided as a preview for developers and may change based on feedback that we receive. Do not use this API in a production environment.

DID Discovery results.

This API may change without a BREAKING CHANGE notice.

<b>Signature:</b>

```typescript
export interface IDIDDiscoveryDiscoverDidResult extends Partial<IDIDDiscoveryDiscoverDidArgs>
```

<b>Extends:</b> Partial&lt;[IDIDDiscoveryDiscoverDidArgs](./did-discovery.ididdiscoverydiscoverdidargs.md)&gt;

## Properties

| Property                                                             | Modifiers | Type                                                                              | Description                                                             |
| -------------------------------------------------------------------- | --------- | --------------------------------------------------------------------------------- | ----------------------------------------------------------------------- |
| [errors?](./did-discovery.ididdiscoverydiscoverdidresult.errors.md)  |           | Record&lt;string, string&gt;                                                      | <b><i>(BETA)</i></b> <i>(Optional)</i> A record of encountered errors   |
| [results](./did-discovery.ididdiscoverydiscoverdidresult.results.md) |           | [IDIDDiscoveryProviderResult](./did-discovery.ididdiscoveryproviderresult.md)\[\] | <b><i>(BETA)</i></b> List of discovery results from different providers |
