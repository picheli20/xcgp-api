---
title: Boolean
---

The `Boolean` scalar type represents `true` or `false`.

## Schema definition
```graphql
scalar Boolean
```

## Required by
* [Achievement](graphql/schema/achievement.md): An achievement
* [AchievementChain](graphql/schema/achievementchain.md): An achievement chain is a group of achievements
* [Bonus](graphql/schema/bonus.md): A bonus
* [Card](graphql/schema/card.md): A card
* [Country](graphql/schema/country.md): A country
* [Currency](graphql/schema/currency.md): A currency
* [Game](graphql/schema/game.md): A game.
* [LobbyCategoryLayout](graphql/schema/lobbycategorylayout.md): Layout for a lobby category.
* [Page](graphql/schema/page.md): An arbitrary piece of content with a blog-like structure. It can be used for things like blog posts, news articles, simple landing pages, user success stories, etc.
* [PageInfo](graphql/schema/pageinfo.md): Information about pagination in a connection.
* [Promotion](graphql/schema/promotion.md): A promotion for a particular template (space). Each template needs to be requested and it can have multiple titles, descriptions, images, CTAs, etc depending on where the promotions will be shown.
* [Query](graphql/schema/query.md)
* [UpdateUserInput](graphql/schema/updateuserinput.md): Input for updating a user
* [User](graphql/schema/user.md): A user
* [__Directive](graphql/schema/__directive.md): A Directive provides a way to describe alternate runtime execution and type validation behavior in a GraphQL document.

In some cases, you need to provide options to alter GraphQL's execution behavior in ways field arguments will not suffice, such as conditionally including or skipping a field. Directives provide this by describing additional information to the executor.
* [__EnumValue](graphql/schema/__enumvalue.md): One possible value for a given Enum. Enum values are unique values, not a placeholder for a string or numeric value. However an Enum value is returned in a JSON response as a string.
* [__Field](graphql/schema/__field.md): Object and Interface types are described by a list of Fields, each of which has a name, potentially a list of arguments, and a return type.
* [__Type](graphql/schema/__type.md): The fundamental unit of any GraphQL Schema is the type. There are many kinds of types in GraphQL as represented by the `__TypeKind` enum.

Depending on the kind of a type, certain fields describe information about that type. Scalar types provide no information beyond a name and description, while Enum types provide their values. Object and Interface types provide the fields they describe. Abstract types, Union and Interface, provide the Object types possible at runtime. List and NonNull types compose other types.
