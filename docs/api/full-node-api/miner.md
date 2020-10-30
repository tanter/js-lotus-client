<!-- Code generated by github.com/filecoin-shipyard/js-lotus-client/docgen. DO NOT EDIT. -->
# Miner



* [minerCreateBlock](miner.md#minercreateblock)
* [minerGetBaseInfo](miner.md#minergetbaseinfo)

## minerCreateBlock

```ts
minerCreateBlock (blockTemplate: BlockTemplate): Promise<BlockMsg>
```

**Parameters:**

* `blockTemplate`: [`BlockTemplate`](../types.md#blocktemplate)

**Returns:**

<code>Promise&lt;<a href="../types.md#blockmsg">BlockMsg</a>&gt;</code>

<small>Source: [index.d.ts, line 375, character 18](https://github.com/filecoin-shipyard/js-lotus-client-rpc/blob/master/index.d.ts#L375)</small>

## minerGetBaseInfo

```ts
minerGetBaseInfo (address: string, chainEpoch: number, tipSetKey: Cid[]): Promise<MiningBaseInfo>
```

**Parameters:**

* `address`: <code>string</code>
* `chainEpoch`: <code>number</code>
* `tipSetKey`: <code><a href="../types.md#cid">Cid</a>[]</code>

**Returns:**

<code>Promise&lt;<a href="../types.md#miningbaseinfo">MiningBaseInfo</a>&gt;</code>

<small>Source: [index.d.ts, line 376, character 18](https://github.com/filecoin-shipyard/js-lotus-client-rpc/blob/master/index.d.ts#L376)</small>