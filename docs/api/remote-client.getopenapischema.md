---
id: remote-client.getopenapischema
title: getOpenApiSchema variable
hide_title: true
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## getOpenApiSchema variable

This method can be used to generate an OpenAPIv3 schema to describe how the methods of a Veramo agent can be called remotely.

<b>Signature:</b>

```typescript
getOpenApiSchema: (
  agent: IAgent,
  basePath: string,
  exposedMethods: Array<string>,
  name?: string,
  version?: string,
) => OpenAPIV3.Document
```
