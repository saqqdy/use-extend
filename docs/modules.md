[index.md - v1.0.0-alpha.1](README.md) / Exports

# index.md - v1.0.0-alpha.1

## Table of contents

### Type Aliases

- [Component](modules.md#component)
- [CreateVNodeParameters](modules.md#createvnodeparameters)

### Functions

- [default](modules.md#default)

## Type Aliases

### Component

Ƭ **Component**: [`CreateVNodeParameters`](modules.md#createvnodeparameters)[``"0"``]

#### Defined in

index.ts:6

---

### CreateVNodeParameters

Ƭ **CreateVNodeParameters**: `Parameters`<typeof `createVNode`\>

#### Defined in

index.ts:5

## Functions

### default

▸ **default**(`component`, `options?`): `Object`

#### Parameters

| Name        | Type                                                                |
| :---------- | :------------------------------------------------------------------ |
| `component` | `VNodeTypes` \| `ClassComponent` \| typeof `NULL_DYNAMIC_COMPONENT` |
| `options?`  | `Options`                                                           |

#### Returns

`Object`

| Name    | Type         |
| :------ | :----------- |
| `close` | () => `void` |
| `open`  | () => `void` |

#### Defined in

index.ts:11
