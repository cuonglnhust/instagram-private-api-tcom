> **[instagram-private-api-tcom](../README.md)**

[Globals](../README.md) / ["feeds/media-comments.feed"](../modules/_feeds_media_comments_feed_.md) / [MediaCommentsFeed](_feeds_media_comments_feed_.mediacommentsfeed.md) /

# Class: MediaCommentsFeed

## Hierarchy

  * [Feed](_core_feed_.feed.md)‹*[MediaCommentsFeedResponse](../interfaces/_responses_media_comments_feed_response_.mediacommentsfeedresponse.md)*, *[MediaCommentsFeedResponseCommentsItem](../interfaces/_responses_media_comments_feed_response_.mediacommentsfeedresponsecommentsitem.md)*›

  * **MediaCommentsFeed**

## Index

### Constructors

* [constructor](_feeds_media_comments_feed_.mediacommentsfeed.md#constructor)

### Properties

* [id](_feeds_media_comments_feed_.mediacommentsfeed.md#id)

### Accessors

* [items$](_feeds_media_comments_feed_.mediacommentsfeed.md#items$)
* [state](_feeds_media_comments_feed_.mediacommentsfeed.md#state)

### Methods

* [deserialize](_feeds_media_comments_feed_.mediacommentsfeed.md#deserialize)
* [isMoreAvailable](_feeds_media_comments_feed_.mediacommentsfeed.md#ismoreavailable)
* [items](_feeds_media_comments_feed_.mediacommentsfeed.md#items)
* [observable](_feeds_media_comments_feed_.mediacommentsfeed.md#observable)
* [request](_feeds_media_comments_feed_.mediacommentsfeed.md#request)
* [serialize](_feeds_media_comments_feed_.mediacommentsfeed.md#serialize)
* [toPlain](_feeds_media_comments_feed_.mediacommentsfeed.md#toplain)

### Object literals

* [attemptOptions](_feeds_media_comments_feed_.mediacommentsfeed.md#attemptoptions)

## Constructors

###  constructor

\+ **new MediaCommentsFeed**(`client`: [IgApiClient](_core_client_.igapiclient.md)): *[MediaCommentsFeed](_feeds_media_comments_feed_.mediacommentsfeed.md)*

*Inherited from [Repository](_core_repository_.repository.md).[constructor](_core_repository_.repository.md#constructor)*

*Defined in [core/repository.ts:6](https://github.com/cuonglnhust/instagram-private-api-tcom/blob/master/src/core/repository.ts#L6)*

**Parameters:**

Name | Type |
------ | ------ |
`client` | [IgApiClient](_core_client_.igapiclient.md) |

**Returns:** *[MediaCommentsFeed](_feeds_media_comments_feed_.mediacommentsfeed.md)*

## Properties

###  id

• **id**: *string*

*Defined in [feeds/media-comments.feed.ts:6](https://github.com/cuonglnhust/instagram-private-api-tcom/blob/3e16058/src/feeds/media-comments.feed.ts#L6)*

## Accessors

###  items$

• **get items$**(): *`Observable<Item[]>`*

*Inherited from [Feed](_core_feed_.feed.md).[items$](_core_feed_.feed.md#items$)*

*Defined in [core/feed.ts:18](https://github.com/cuonglnhust/instagram-private-api-tcom/blob/master/src/core/feed.ts#L18)*

**Returns:** *`Observable<Item[]>`*

___

###  state

• **set state**(`body`: [MediaCommentsFeedResponse](../interfaces/_responses_media_comments_feed_response_.mediacommentsfeedresponse.md)): *void*

*Defined in [feeds/media-comments.feed.ts:12](https://github.com/cuonglnhust/instagram-private-api-tcom/blob/3e16058/src/feeds/media-comments.feed.ts#L12)*

**Parameters:**

Name | Type |
------ | ------ |
`body` | [MediaCommentsFeedResponse](../interfaces/_responses_media_comments_feed_response_.mediacommentsfeedresponse.md) |

**Returns:** *void*

## Methods

###  deserialize

▸ **deserialize**(`data`: string): *void*

*Inherited from [Feed](_core_feed_.feed.md).[deserialize](_core_feed_.feed.md#deserialize)*

*Defined in [core/feed.ts:79](https://github.com/cuonglnhust/instagram-private-api-tcom/blob/master/src/core/feed.ts#L79)*

**Parameters:**

Name | Type |
------ | ------ |
`data` | string |

**Returns:** *void*

___

###  isMoreAvailable

▸ **isMoreAvailable**(): *boolean*

*Inherited from [Feed](_core_feed_.feed.md).[isMoreAvailable](_core_feed_.feed.md#ismoreavailable)*

*Defined in [core/feed.ts:87](https://github.com/cuonglnhust/instagram-private-api-tcom/blob/master/src/core/feed.ts#L87)*

**Returns:** *boolean*

___

###  items

▸ **items**(): *`Promise<MediaCommentsFeedResponseCommentsItem[]>`*

*Overrides [Feed](_core_feed_.feed.md).[items](_core_feed_.feed.md#abstract-items)*

*Defined in [feeds/media-comments.feed.ts:31](https://github.com/cuonglnhust/instagram-private-api-tcom/blob/3e16058/src/feeds/media-comments.feed.ts#L31)*

**Returns:** *`Promise<MediaCommentsFeedResponseCommentsItem[]>`*

___

###  observable

▸ **observable**(`semaphore?`: function, `attemptOptions?`: `Partial<AttemptOptions<any>>`): *`Observable<Item[]>`*

*Inherited from [Feed](_core_feed_.feed.md).[observable](_core_feed_.feed.md#observable)*

*Defined in [core/feed.ts:21](https://github.com/cuonglnhust/instagram-private-api-tcom/blob/master/src/core/feed.ts#L21)*

**Parameters:**

▪`Optional`  **semaphore**: *function*

▸ (): *`Promise<any>`*

▪`Optional`  **attemptOptions**: *`Partial<AttemptOptions<any>>`*

**Returns:** *`Observable<Item[]>`*

___

###  request

▸ **request**(): *`Promise<MediaCommentsFeedResponse>`*

*Overrides [Feed](_core_feed_.feed.md).[request](_core_feed_.feed.md#abstract-request)*

*Defined in [feeds/media-comments.feed.ts:18](https://github.com/cuonglnhust/instagram-private-api-tcom/blob/3e16058/src/feeds/media-comments.feed.ts#L18)*

**Returns:** *`Promise<MediaCommentsFeedResponse>`*

___

###  serialize

▸ **serialize**(): *string*

*Inherited from [Feed](_core_feed_.feed.md).[serialize](_core_feed_.feed.md#serialize)*

*Defined in [core/feed.ts:75](https://github.com/cuonglnhust/instagram-private-api-tcom/blob/master/src/core/feed.ts#L75)*

**Returns:** *string*

___

###  toPlain

▸ **toPlain**(): *`Object`*

*Inherited from [Feed](_core_feed_.feed.md).[toPlain](_core_feed_.feed.md#toplain)*

*Defined in [core/feed.ts:83](https://github.com/cuonglnhust/instagram-private-api-tcom/blob/master/src/core/feed.ts#L83)*

**Returns:** *`Object`*

## Object literals

###  attemptOptions

### ▪ **attemptOptions**: *object*

*Inherited from [Feed](_core_feed_.feed.md).[attemptOptions](_core_feed_.feed.md#attemptoptions)*

*Defined in [core/feed.ts:10](https://github.com/cuonglnhust/instagram-private-api-tcom/blob/master/src/core/feed.ts#L10)*

###  delay

• **delay**: *number* = 60000

*Defined in [core/feed.ts:11](https://github.com/cuonglnhust/instagram-private-api-tcom/blob/master/src/core/feed.ts#L11)*

###  factor

• **factor**: *number* = 1.5

*Defined in [core/feed.ts:12](https://github.com/cuonglnhust/instagram-private-api-tcom/blob/master/src/core/feed.ts#L12)*

###  jitter

• **jitter**: *true* = true

*Defined in [core/feed.ts:16](https://github.com/cuonglnhust/instagram-private-api-tcom/blob/master/src/core/feed.ts#L16)*

###  maxAttempts

• **maxAttempts**: *number* = 10

*Defined in [core/feed.ts:13](https://github.com/cuonglnhust/instagram-private-api-tcom/blob/master/src/core/feed.ts#L13)*

###  maxDelay

• **maxDelay**: *number* = 300000

*Defined in [core/feed.ts:15](https://github.com/cuonglnhust/instagram-private-api-tcom/blob/master/src/core/feed.ts#L15)*

###  minDelay

• **minDelay**: *number* = 60000

*Defined in [core/feed.ts:14](https://github.com/cuonglnhust/instagram-private-api-tcom/blob/master/src/core/feed.ts#L14)*