---
lang: en
title: 'API docs: repository.crudconnector.exists'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
permalink: /doc/en/lb4/apidocs.repository.crudconnector.exists.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/repository](./repository.md) &gt; [CrudConnector](./repository.crudconnector.md) &gt; [exists](./repository.crudconnector.exists.md)

## CrudConnector.exists() method

Check if an entity exists for the id

<b>Signature:</b>

```typescript
exists?<IdType>(modelClass: Class<Entity>, id: IdType, options?: Options): Promise<boolean>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  modelClass | <code>Class&lt;Entity&gt;</code> | The model class |
|  id | <code>IdType</code> | The entity id value |
|  options | <code>Options</code> | Options for the operation |

<b>Returns:</b>

`Promise<boolean>`

Promise<true> if an entity exists for the id, otherwise Promise<false>

