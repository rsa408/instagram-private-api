[instagram-private-api](../../README.md) / [index](../../modules/index.md) / PostsInsightsFeed

# Class: PostsInsightsFeed

[index](../../modules/index.md).PostsInsightsFeed

## Hierarchy

- [`Feed`](Feed.md)<[`PostsInsightsFeedResponseRootObject`](../../interfaces/index/PostsInsightsFeedResponseRootObject.md), [`PostsInsightsFeedResponseEdgesItem`](../../interfaces/index/PostsInsightsFeedResponseEdgesItem.md)\>

  ↳ **`PostsInsightsFeed`**

## Table of contents

### Constructors

- [constructor](PostsInsightsFeed.md#constructor)

### Properties

- [attemptOptions](PostsInsightsFeed.md#attemptoptions)

### Accessors

- [items$](PostsInsightsFeed.md#items$)

### Methods

- [deserialize](PostsInsightsFeed.md#deserialize)
- [isMoreAvailable](PostsInsightsFeed.md#ismoreavailable)
- [items](PostsInsightsFeed.md#items)
- [observable](PostsInsightsFeed.md#observable)
- [request](PostsInsightsFeed.md#request)
- [serialize](PostsInsightsFeed.md#serialize)
- [toPlain](PostsInsightsFeed.md#toplain)

## Constructors

### constructor

• **new PostsInsightsFeed**(`client`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `client` | [`IgApiClient`](IgApiClient.md) |

#### Inherited from

[Feed](Feed.md).[constructor](Feed.md#constructor)

#### Defined in

[src/core/repository.ts:7](https://github.com/Nerixyz/instagram-private-api/blob/0e0721c/src/core/repository.ts#L7)

## Properties

### attemptOptions

• **attemptOptions**: `Partial`<`AttemptOptions`<`any`\>\>

#### Inherited from

[Feed](Feed.md).[attemptOptions](Feed.md#attemptoptions)

#### Defined in

[src/core/feed.ts:10](https://github.com/Nerixyz/instagram-private-api/blob/0e0721c/src/core/feed.ts#L10)

## Accessors

### items$

• `get` **items$**(): `Observable`<`Item`[]\>

#### Returns

`Observable`<`Item`[]\>

#### Defined in

[src/core/feed.ts:18](https://github.com/Nerixyz/instagram-private-api/blob/0e0721c/src/core/feed.ts#L18)

## Methods

### deserialize

▸ **deserialize**(`data`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `string` |

#### Returns

`void`

#### Inherited from

[Feed](Feed.md).[deserialize](Feed.md#deserialize)

#### Defined in

[src/core/feed.ts:79](https://github.com/Nerixyz/instagram-private-api/blob/0e0721c/src/core/feed.ts#L79)

___

### isMoreAvailable

▸ **isMoreAvailable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Feed](Feed.md).[isMoreAvailable](Feed.md#ismoreavailable)

#### Defined in

[src/core/feed.ts:87](https://github.com/Nerixyz/instagram-private-api/blob/0e0721c/src/core/feed.ts#L87)

___

### items

▸ **items**(): `Promise`<[`PostsInsightsFeedResponseEdgesItem`](../../interfaces/index/PostsInsightsFeedResponseEdgesItem.md)[]\>

#### Returns

`Promise`<[`PostsInsightsFeedResponseEdgesItem`](../../interfaces/index/PostsInsightsFeedResponseEdgesItem.md)[]\>

#### Overrides

[Feed](Feed.md).[items](Feed.md#items)

#### Defined in

[src/feeds/posts-insights.feed.ts:12](https://github.com/Nerixyz/instagram-private-api/blob/0e0721c/src/feeds/posts-insights.feed.ts#L12)

___

### observable

▸ **observable**(`semaphore?`, `attemptOptions?`): `Observable`<[`PostsInsightsFeedResponseEdgesItem`](../../interfaces/index/PostsInsightsFeedResponseEdgesItem.md)[]\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `semaphore?` | () => `Promise`<`any`\> |
| `attemptOptions?` | `Partial`<`AttemptOptions`<`any`\>\> |

#### Returns

`Observable`<[`PostsInsightsFeedResponseEdgesItem`](../../interfaces/index/PostsInsightsFeedResponseEdgesItem.md)[]\>

#### Inherited from

[Feed](Feed.md).[observable](Feed.md#observable)

#### Defined in

[src/core/feed.ts:21](https://github.com/Nerixyz/instagram-private-api/blob/0e0721c/src/core/feed.ts#L21)

___

### request

▸ **request**(): `Promise`<[`PostsInsightsFeedResponseRootObject`](../../interfaces/index/PostsInsightsFeedResponseRootObject.md)\>

#### Returns

`Promise`<[`PostsInsightsFeedResponseRootObject`](../../interfaces/index/PostsInsightsFeedResponseRootObject.md)\>

#### Overrides

[Feed](Feed.md).[request](Feed.md#request)

#### Defined in

[src/feeds/posts-insights.feed.ts:17](https://github.com/Nerixyz/instagram-private-api/blob/0e0721c/src/feeds/posts-insights.feed.ts#L17)

___

### serialize

▸ **serialize**(): `string`

#### Returns

`string`

#### Inherited from

[Feed](Feed.md).[serialize](Feed.md#serialize)

#### Defined in

[src/core/feed.ts:75](https://github.com/Nerixyz/instagram-private-api/blob/0e0721c/src/core/feed.ts#L75)

___

### toPlain

▸ **toPlain**(): `Record`<`string`, `any`\>

#### Returns

`Record`<`string`, `any`\>

#### Inherited from

[Feed](Feed.md).[toPlain](Feed.md#toplain)

#### Defined in

[src/core/feed.ts:83](https://github.com/Nerixyz/instagram-private-api/blob/0e0721c/src/core/feed.ts#L83)
