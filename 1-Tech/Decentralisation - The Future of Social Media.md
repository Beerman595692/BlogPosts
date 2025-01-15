---
created: 2025-01-14T21:40
updated: 2025-01-14T22:41
---
As of writing this Eugen Rochko the CEO of Mastodon has given over the mastodon project to a non-profit foundation stating "affirming the intent that Mastodon should not be owned or controlled by a single individual." - [Citation ](https://www.theverge.com/2025/1/13/24342603/mastodon-non-profit-ownership-ceo-eugen-rochko)

As Zuck and Musk turn their platforms into MAGA breeding grounds. Never has decentralised social media been more important. Platforms that can't be bought by nutcase, doesn't sell your data to advertisers and doesn't promote rage bait and engagement farming. That put the community and user safety above all else.

The main ways of doing it a through systems such as Peer 2 Peer, Blockchain technology, ActivityPub and new comer AT protocol. 

# Activity Pub

ActivityPub is a web protocol that allows for server to server communication. Basically you have a server running mastodon for example, it can communicate with other servers running mastodon or any other service that supports activitypub. Such Lemmy(an ap version of reddit), Peertube (an ap version of yourtube) or pixelfed (an ap version of Instagram). In other words someone could make a Peertube channel and you could follow them with your mastodon account and see their videos in your mastodon feed. No need to create a separate Peertube account.

Moderation is managed by the individual servers. If you don't like how a server is managed, you can migrate to a new one with losing your followers or following. 

Server also have the option to defederated. Donald Trump's truth social uses activity pub, so many mastodon instances could just defederate with it so no posts from truth social would make it's way onto their servers.

# AT Protocol 

The **Authenticated Transfer Protoco** or AT proto seems to address some of activitypub's shortcomings. Such when migrating servers you lose your posts and if your mastodon instance shuts down you lose all your data.

With the AT protocol you Host a Personal Data Server or PDS for short. This PDS stores all your data, your posts, your likes, who you follow, who follows you. 