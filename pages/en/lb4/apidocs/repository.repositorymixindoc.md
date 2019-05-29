---
lang: en
title: 'API docs: repository.repositorymixindoc'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
permalink: /doc/en/lb4/apidocs.repository.repositorymixindoc.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/repository](./repository.md) &gt; [RepositoryMixinDoc](./repository.repositorymixindoc.md)

## RepositoryMixinDoc class

A dummy class created to generate the tsdoc for the members in repository mixin. Please don't use it.

The members are implemented in function <a href="#RepositoryMixin">RepositoryMixin</a>

<b>Signature:</b>

```typescript
export declare class RepositoryMixinDoc 
```

## Constructors

|  Constructor | Modifiers | Description |
|  --- | --- | --- |
|  [(constructor)(args)](./repository.repositorymixindoc.(constructor).md) |  | Constructs a new instance of the <code>RepositoryMixinDoc</code> class |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [component(component)](./repository.repositorymixindoc.component.md) |  | Add a component to this application. Also mounts all the components repositories. |
|  [dataSource(dataSource, name)](./repository.repositorymixindoc.datasource.md) |  | Add the dataSource to this application. |
|  [getRepository(repo)](./repository.repositorymixindoc.getrepository.md) |  | Retrieve the repository instance from the given Repository class |
|  [migrateSchema(options)](./repository.repositorymixindoc.migrateschema.md) |  | Update or recreate the database schema for all repositories.<!-- -->\*\*WARNING\*\*: By default, <code>migrateSchema()</code> will attempt to preserve data while updating the schema in your target database, but this is not guaranteed to be safe.<!-- -->Please check the documentation for your specific connector(s) for a detailed breakdown of behaviors for automigrate! |
|  [mountComponentRepository(component)](./repository.repositorymixindoc.mountcomponentrepository.md) |  | Get an instance of a component and mount all it's repositories. This function is intended to be used internally by component() |
|  [repository(repo)](./repository.repositorymixindoc.repository.md) |  | Add a repository to this application. |

