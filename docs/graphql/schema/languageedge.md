---
title: LanguageEdge
---

<p>An edge in a connection</p>


## Schema definition
```graphql
type LanguageEdge {

  # The item at the end of the edge
  node: Language 

  # A cursor for use in pagination
  cursor: String! 

}
```
## Required by
* [LanguageConnection](graphql/schema/languageconnection.md): A connection to a list of items.