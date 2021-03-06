---
title: String
---

The `String` scalar type represents textual data, represented as UTF-8
character sequences. The String type is most often used by GraphQL to
represent free-form human-readable text.

## Schema definition
```graphql
scalar String
```

## Required by
* [Achievement](graphql/schema/achievement.md): An achievement
* [AchievementChain](graphql/schema/achievementchain.md): An achievement chain is a group of achievements
* [AchievementChainEdge](graphql/schema/achievementchainedge.md): An edge in a connection
* [AchievementEdge](graphql/schema/achievementedge.md): An edge in a connection
* [Bonus](graphql/schema/bonus.md): A bonus
* [BonusEdge](graphql/schema/bonusedge.md): An edge in a connection
* [Bucket](graphql/schema/bucket.md): An bucket containing achievement progress
* [Card](graphql/schema/card.md): A card
* [Country](graphql/schema/country.md): A country
* [CountryEdge](graphql/schema/countryedge.md): An edge in a connection
* [CreateUserInput](graphql/schema/createuserinput.md): Input for registering/creating a user
* [Currency](graphql/schema/currency.md): A currency
* [CurrencyEdge](graphql/schema/currencyedge.md): An edge in a connection
* [Document](graphql/schema/document.md): A document
* [DocumentEdge](graphql/schema/documentedge.md): An edge in a connection
* [Feed](graphql/schema/feed.md): An entry from an external RSS or Atom feed.
* [FeedAuthor](graphql/schema/feedauthor.md): The author of a feed entry.
* [FeedEdge](graphql/schema/feededge.md): An edge in a connection
* [Game](graphql/schema/game.md): A game.
* [GameEdge](graphql/schema/gameedge.md): An edge in a connection
* [GameSessionEdge](graphql/schema/gamesessionedge.md): An edge in a connection
* [GameTag](graphql/schema/gametag.md): A game tag that can be used to filter games
* [GameTagEdge](graphql/schema/gametagedge.md): An edge in a connection
* [Jackpot](graphql/schema/jackpot.md): A jackpot
* [JackpotEdge](graphql/schema/jackpotedge.md): An edge in a connection
* [Language](graphql/schema/language.md): A locale.
* [LanguageEdge](graphql/schema/languageedge.md): An edge in a connection
* [Limit](graphql/schema/limit.md): A limit
* [LimitEdge](graphql/schema/limitedge.md): An edge in a connection
* [Lobby](graphql/schema/lobby.md): A lobby containing game categories.
* [LobbyBlockEdge](graphql/schema/lobbyblockedge.md): An edge in a connection
* [LobbyCategory](graphql/schema/lobbycategory.md): A lobby category.
* [LobbyCategoryEdge](graphql/schema/lobbycategoryedge.md): An edge in a connection
* [LobbyCategoryLayout](graphql/schema/lobbycategorylayout.md): Layout for a lobby category.
* [LobbyCategoryLayoutBlock](graphql/schema/lobbycategorylayoutblock.md): Block of games for a category layout
* [LobbyCategoryLayoutEdge](graphql/schema/lobbycategorylayoutedge.md): An edge in a connection
* [LobbyEdge](graphql/schema/lobbyedge.md): An edge in a connection
* [LobbyGame](graphql/schema/lobbygame.md): A lobby game block.
* [LobbyPromotionSpace](graphql/schema/lobbypromotionspace.md): A lobby promotion space.
* [Location](graphql/schema/location.md): A location
* [LocationCountry](graphql/schema/locationcountry.md)
* [Page](graphql/schema/page.md): An arbitrary piece of content with a blog-like structure. It can be used for things like blog posts, news articles, simple landing pages, user success stories, etc.
* [PageEdge](graphql/schema/pageedge.md): An edge in a connection
* [PageInfo](graphql/schema/pageinfo.md): Information about pagination in a connection.
* [PaymentMethod](graphql/schema/paymentmethod.md): A payment method
* [PaymentMethodEdge](graphql/schema/paymentmethodedge.md): An edge in a connection
* [PromoSpaceButton](graphql/schema/promospacebutton.md): A promo space button
* [Promotion](graphql/schema/promotion.md): A promotion for a particular template (space). Each template needs to be requested and it can have multiple titles, descriptions, images, CTAs, etc depending on where the promotions will be shown.
* [PromotionEdge](graphql/schema/promotionedge.md): An edge in a connection
* [QnaCategory](graphql/schema/qnacategory.md): A category of questions and answers. It can be used for any kind of content that displays as a list of titles and descriptions like questions and answers, glossaries, terms and conditions, etc.
* [QnaCategoryEdge](graphql/schema/qnacategoryedge.md): An edge in a connection
* [QnaContent](graphql/schema/qnacontent.md): The content for a question and answer
* [Query](graphql/schema/query.md)
* [Screenshot](graphql/schema/screenshot.md): A game screenshot.
* [Seo](graphql/schema/seo.md): An SEO entry for a document.
* [SeoEdge](graphql/schema/seoedge.md): An edge in a connection
* [SeoLink](graphql/schema/seolink.md): A definition for an [external resource link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/link).
* [SeoMetaTag](graphql/schema/seometatag.md): A definition for a [metadata element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meta).
* [SportEvent](graphql/schema/sportevent.md): A sport event
* [SportEventEdge](graphql/schema/sporteventedge.md): An edge in a connection
* [SportEventParticipant](graphql/schema/sporteventparticipant.md): A sport event participant
* [Transaction](graphql/schema/transaction.md): A transaction
* [TransactionCredentials](graphql/schema/transactioncredentials.md): The credentials for a transaction
* [TransactionEdge](graphql/schema/transactionedge.md): An edge in a connection
* [UpdateUserInput](graphql/schema/updateuserinput.md): Input for updating a user
* [User](graphql/schema/user.md): A user
* [UserAchievement](graphql/schema/userachievement.md): An achievement belonging to a user
* [UserAchievementEdge](graphql/schema/userachievementedge.md): An edge in a connection
* [Win](graphql/schema/win.md): A win
* [WinEdge](graphql/schema/winedge.md): An edge in a connection
* [__Directive](graphql/schema/__directive.md): A Directive provides a way to describe alternate runtime execution and type validation behavior in a GraphQL document.

In some cases, you need to provide options to alter GraphQL's execution behavior in ways field arguments will not suffice, such as conditionally including or skipping a field. Directives provide this by describing additional information to the executor.
* [__EnumValue](graphql/schema/__enumvalue.md): One possible value for a given Enum. Enum values are unique values, not a placeholder for a string or numeric value. However an Enum value is returned in a JSON response as a string.
* [__Field](graphql/schema/__field.md): Object and Interface types are described by a list of Fields, each of which has a name, potentially a list of arguments, and a return type.
* [__InputValue](graphql/schema/__inputvalue.md): Arguments provided to Fields or Directives and the input fields of an InputObject are represented as Input Values which describe their type and optionally a default value.
* [__Type](graphql/schema/__type.md): The fundamental unit of any GraphQL Schema is the type. There are many kinds of types in GraphQL as represented by the `__TypeKind` enum.

Depending on the kind of a type, certain fields describe information about that type. Scalar types provide no information beyond a name and description, while Enum types provide their values. Object and Interface types provide the fields they describe. Abstract types, Union and Interface, provide the Object types possible at runtime. List and NonNull types compose other types.
