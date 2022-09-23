[nodejsscript](../README.md) / [\_\_fetch](../modules/_fetch.md) / AbortError

# Class: AbortError

[__fetch](../modules/_fetch.md).AbortError

## Hierarchy

- `Error`

  ↳ **`AbortError`**

## Table of contents

### Methods

- [captureStackTrace](fetch.AbortError.md#capturestacktrace)

### Properties

- [prepareStackTrace](fetch.AbortError.md#preparestacktrace)
- [stackTraceLimit](fetch.AbortError.md#stacktracelimit)
- [type](fetch.AbortError.md#type)
- [name](fetch.AbortError.md#name)
- [[toStringTag]](fetch.AbortError.md#[tostringtag])
- [message](fetch.AbortError.md#message)
- [stack](fetch.AbortError.md#stack)

### Constructors

- [constructor](fetch.AbortError.md#constructor)

## Methods

### captureStackTrace

▸ `Static` **captureStackTrace**(`targetObject`, `constructorOpt?`): `void`

Create .stack property on a target object

#### Parameters

| Name | Type |
| :------ | :------ |
| `targetObject` | `object` |
| `constructorOpt?` | `Function` |

#### Returns

`void`

#### Inherited from

Error.captureStackTrace

#### Defined in

node_modules/@types/node/globals.d.ts:4

## Properties

### prepareStackTrace

▪ `Static` `Optional` **prepareStackTrace**: (`err`: `Error`, `stackTraces`: `CallSite`[]) => `any`

#### Type declaration

▸ (`err`, `stackTraces`): `any`

Optional override for formatting stack traces

**`See`**

https://v8.dev/docs/stack-trace-api#customizing-stack-traces

##### Parameters

| Name | Type |
| :------ | :------ |
| `err` | `Error` |
| `stackTraces` | `CallSite`[] |

##### Returns

`any`

#### Inherited from

Error.prepareStackTrace

#### Defined in

node_modules/@types/node/globals.d.ts:11

___

### stackTraceLimit

▪ `Static` **stackTraceLimit**: `number`

#### Inherited from

Error.stackTraceLimit

#### Defined in

node_modules/@types/node/globals.d.ts:13

___

### type

• **type**: `string`

#### Defined in

node_modules/node-fetch/@types/index.d.ts:212

___

### name

• **name**: ``"AbortError"``

#### Overrides

Error.name

#### Defined in

node_modules/node-fetch/@types/index.d.ts:213

___

### [toStringTag]

• **[toStringTag]**: ``"AbortError"``

#### Defined in

node_modules/node-fetch/@types/index.d.ts:214

___

### message

• **message**: `string`

#### Inherited from

Error.message

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1041

___

### stack

• `Optional` **stack**: `string`

#### Inherited from

Error.stack

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1042

## Constructors

### constructor

• **new AbortError**(`message?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `message?` | `string` |

#### Inherited from

Error.constructor

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1046