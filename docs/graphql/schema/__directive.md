---
title: __Directive
---

A Directive provides a way to describe alternate runtime execution and type validation behavior in a GraphQL document.

In some cases, you need to provide options to alter GraphQL's execution behavior in ways field arguments will not suffice, such as conditionally including or skipping a field. Directives provide this by describing additional information to the executor.

## Schema definition
```graphql
type __Directive {

  name: String!

  description: String

  locations: [__DirectiveLocation!]!

  args: [__InputValue!]!

  onOperation: Boolean! @deprecated(reason: "Use `locations`.")

  onFragment: Boolean! @deprecated(reason: "Use `locations`.")

  onField: Boolean! @deprecated(reason: "Use `locations`.")

}
```

## Fields

* **name ([`String!`](graphql/schema/string.md))**


* **description ([`String`](graphql/schema/string.md))**


* **locations ([`[__DirectiveLocation!]!`](graphql/schema/__directivelocation.md))**


* **args ([`[__InputValue!]!`](graphql/schema/__inputvalue.md))**


* **onOperation ([`Boolean!`](graphql/schema/boolean.md))**


* **onFragment ([`Boolean!`](graphql/schema/boolean.md))**


* **onField ([`Boolean!`](graphql/schema/boolean.md))**



## Required by
* [__Schema](graphql/schema/__schema.md): A GraphQL Schema defines the capabilities of a GraphQL server. It exposes all available types and directives on the server, as well as the entry points for query, mutation, and subscription operations.
