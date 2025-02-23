[nodejsscript](../README.md) / [s](../modules/s.md) / [child](../modules/s.child.md) / SpawnOptions

# Interface: SpawnOptions

[s](../modules/s.md).[child](../modules/s.child.md).SpawnOptions

## Hierarchy

- [`CommonSpawnOptions`](s.child.CommonSpawnOptions.md)

  ↳ **`SpawnOptions`**

  ↳↳ [`SpawnOptionsWithoutStdio`](s.child.SpawnOptionsWithoutStdio.md)

  ↳↳ [`SpawnOptionsWithStdioTuple`](s.child.SpawnOptionsWithStdioTuple.md)

## Table of contents

### Properties

- [detached](s.child.SpawnOptions.md#detached)
- [argv0](s.child.SpawnOptions.md#argv0)
- [stdio](s.child.SpawnOptions.md#stdio)
- [shell](s.child.SpawnOptions.md#shell)
- [windowsVerbatimArguments](s.child.SpawnOptions.md#windowsverbatimarguments)
- [windowsHide](s.child.SpawnOptions.md#windowshide)
- [timeout](s.child.SpawnOptions.md#timeout)
- [uid](s.child.SpawnOptions.md#uid)
- [gid](s.child.SpawnOptions.md#gid)
- [cwd](s.child.SpawnOptions.md#cwd)
- [env](s.child.SpawnOptions.md#env)
- [serialization](s.child.SpawnOptions.md#serialization)
- [killSignal](s.child.SpawnOptions.md#killsignal)
- [signal](s.child.SpawnOptions.md#signal)

## Properties

### detached

• `Optional` **detached**: `boolean`

___

### argv0

• `Optional` **argv0**: `string`

#### Inherited from

[CommonSpawnOptions](s.child.CommonSpawnOptions.md).[argv0](s.child.CommonSpawnOptions.md#argv0)

___

### stdio

• `Optional` **stdio**: [`StdioOptions`](../modules/s.child.md#stdiooptions)

#### Inherited from

[CommonSpawnOptions](s.child.CommonSpawnOptions.md).[stdio](s.child.CommonSpawnOptions.md#stdio)

___

### shell

• `Optional` **shell**: `string` \| `boolean`

#### Inherited from

[CommonSpawnOptions](s.child.CommonSpawnOptions.md).[shell](s.child.CommonSpawnOptions.md#shell)

___

### windowsVerbatimArguments

• `Optional` **windowsVerbatimArguments**: `boolean`

#### Inherited from

[CommonSpawnOptions](s.child.CommonSpawnOptions.md).[windowsVerbatimArguments](s.child.CommonSpawnOptions.md#windowsverbatimarguments)

___

### windowsHide

• `Optional` **windowsHide**: `boolean`

**`Default`**

false

#### Inherited from

[CommonSpawnOptions](s.child.CommonSpawnOptions.md).[windowsHide](s.child.CommonSpawnOptions.md#windowshide)

___

### timeout

• `Optional` **timeout**: `number`

**`Default`**

0

#### Inherited from

[CommonSpawnOptions](s.child.CommonSpawnOptions.md).[timeout](s.child.CommonSpawnOptions.md#timeout)

___

### uid

• `Optional` **uid**: `number`

#### Inherited from

[CommonSpawnOptions](s.child.CommonSpawnOptions.md).[uid](s.child.CommonSpawnOptions.md#uid)

___

### gid

• `Optional` **gid**: `number`

#### Inherited from

[CommonSpawnOptions](s.child.CommonSpawnOptions.md).[gid](s.child.CommonSpawnOptions.md#gid)

___

### cwd

• `Optional` **cwd**: `string` \| `URL`

#### Inherited from

[CommonSpawnOptions](s.child.CommonSpawnOptions.md).[cwd](s.child.CommonSpawnOptions.md#cwd)

___

### env

• `Optional` **env**: `ProcessEnv`

#### Inherited from

[CommonSpawnOptions](s.child.CommonSpawnOptions.md).[env](s.child.CommonSpawnOptions.md#env)

___

### serialization

• `Optional` **serialization**: [`SerializationType`](../modules/s.child.md#serializationtype)

Specify the kind of serialization used for sending messages between processes.

**`Default`**

'json'

#### Inherited from

[CommonSpawnOptions](s.child.CommonSpawnOptions.md).[serialization](s.child.CommonSpawnOptions.md#serialization)

___

### killSignal

• `Optional` **killSignal**: `number` \| `Signals`

The signal value to be used when the spawned process will be killed by the abort signal.

**`Default`**

'SIGTERM'

#### Inherited from

[CommonSpawnOptions](s.child.CommonSpawnOptions.md).[killSignal](s.child.CommonSpawnOptions.md#killsignal)

___

### signal

• `Optional` **signal**: `AbortSignal`

When provided the corresponding `AbortController` can be used to cancel an asynchronous action.

#### Inherited from

[CommonSpawnOptions](s.child.CommonSpawnOptions.md).[signal](s.child.CommonSpawnOptions.md#signal)
