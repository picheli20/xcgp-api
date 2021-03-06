---
title: Node
---

An object with an ID

## Schema definition
```graphql
interface Node {

  # The id of the object
  id: ID!

}
```

## Required by
* [Achievement](graphql/schema/achievement.md): An achievement
* [AchievementChain](graphql/schema/achievementchain.md): An achievement chain is a group of achievements
* [Bonus](graphql/schema/bonus.md): A bonus
* [Bucket](graphql/schema/bucket.md): An bucket containing achievement progress
* [Card](graphql/schema/card.md): A card
* [Document](graphql/schema/document.md): A document
* [Feed](graphql/schema/feed.md): An entry from an external RSS or Atom feed.
* [Game](graphql/schema/game.md): A game.
* [GameSession](graphql/schema/gamesession.md): A game session
* [Limit](graphql/schema/limit.md): A limit
* [Lobby](graphql/schema/lobby.md): A lobby containing game categories.
* [LobbyCategory](graphql/schema/lobbycategory.md): A lobby category.
* [LobbyCategoryLayout](graphql/schema/lobbycategorylayout.md): Layout for a lobby category.
* [LobbyCategoryLayoutBlock](graphql/schema/lobbycategorylayoutblock.md): Block of games for a category layout
* [LobbyGame](graphql/schema/lobbygame.md): A lobby game block.
* [LobbyPromotionSpace](graphql/schema/lobbypromotionspace.md): A lobby promotion space.
* [Page](graphql/schema/page.md): An arbitrary piece of content with a blog-like structure. It can be used for things like blog posts, news articles, simple landing pages, user success stories, etc.
* [PaymentMethod](graphql/schema/paymentmethod.md): A payment method
* [Promotion](graphql/schema/promotion.md): A promotion for a particular template (space). Each template needs to be requested and it can have multiple titles, descriptions, images, CTAs, etc depending on where the promotions will be shown.
* [QnaCategory](graphql/schema/qnacategory.md): A category of questions and answers. It can be used for any kind of content that displays as a list of titles and descriptions like questions and answers, glossaries, terms and conditions, etc.
* [Query](graphql/schema/query.md)
* [Seo](graphql/schema/seo.md): An SEO entry for a document.
* [SportEvent](graphql/schema/sportevent.md): A sport event
* [Transaction](graphql/schema/transaction.md): A transaction
* [User](graphql/schema/user.md): A user
* [UserAchievement](graphql/schema/userachievement.md): An achievement belonging to a user
