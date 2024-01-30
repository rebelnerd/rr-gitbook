[@roberts-studios/harness](../README.md) / [Exports](../modules.md) / PluginComponent

# Class: PluginComponent

## Hierarchy

- `HTMLElement`

  ↳ **`PluginComponent`**

## Table of contents

### Constructors

- [constructor](PluginComponent.md#constructor)

### Properties

- [\_originalBlob](PluginComponent.md#_originalblob)
- [img](PluginComponent.md#img)
- [metadata](PluginComponent.md#metadata)
- [shadow](PluginComponent.md#shadow)

### Accessors

- [originalBlob](PluginComponent.md#originalblob)
- [observedAttributes](PluginComponent.md#observedattributes)

### Methods

- [attributedChangedCallback](PluginComponent.md#attributedchangedcallback)
- [cancel](PluginComponent.md#cancel)
- [complete](PluginComponent.md#complete)
- [connectedCallback](PluginComponent.md#connectedcallback)
- [disconnectedCallback](PluginComponent.md#disconnectedcallback)
- [initialize](PluginComponent.md#initialize)
- [loadComponent](PluginComponent.md#loadcomponent)
- [setup](PluginComponent.md#setup)
- [test](PluginComponent.md#test)
- [toBlob](PluginComponent.md#toblob)

## Constructors

### constructor

• **new PluginComponent**(): [`PluginComponent`](PluginComponent.md)

#### Returns

[`PluginComponent`](PluginComponent.md)

#### Overrides

HTMLElement.constructor

#### Defined in

[web-components/plugin/plugin.component.ts:39](https://bitbucket.org/prcode/harness/src/c577484/src/web-components/plugin/plugin.component.ts#lines-39)

## Properties

### \_originalBlob

• **\_originalBlob**: `any`

#### Defined in

[web-components/plugin/plugin.component.ts:29](https://bitbucket.org/prcode/harness/src/c577484/src/web-components/plugin/plugin.component.ts#lines-29)

___

### img

• `Protected` **img**: `HTMLInputElement`

#### Defined in

[web-components/plugin/plugin.component.ts:20](https://bitbucket.org/prcode/harness/src/c577484/src/web-components/plugin/plugin.component.ts#lines-20)

___

### metadata

• `Protected` **metadata**: `any`

#### Defined in

[web-components/plugin/plugin.component.ts:23](https://bitbucket.org/prcode/harness/src/c577484/src/web-components/plugin/plugin.component.ts#lines-23)

___

### shadow

• `Protected` **shadow**: `any`

#### Defined in

[web-components/plugin/plugin.component.ts:18](https://bitbucket.org/prcode/harness/src/c577484/src/web-components/plugin/plugin.component.ts#lines-18)

## Accessors

### originalBlob

• `get` **originalBlob**(): `any`

#### Returns

`any`

#### Defined in

[web-components/plugin/plugin.component.ts:30](https://bitbucket.org/prcode/harness/src/c577484/src/web-components/plugin/plugin.component.ts#lines-30)

• `set` **originalBlob**(`value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `any` |

#### Returns

`void`

#### Defined in

[web-components/plugin/plugin.component.ts:33](https://bitbucket.org/prcode/harness/src/c577484/src/web-components/plugin/plugin.component.ts#lines-33)

___

### observedAttributes

• `get` **observedAttributes**(): `string`[]

#### Returns

`string`[]

#### Defined in

[web-components/plugin/plugin.component.ts:25](https://bitbucket.org/prcode/harness/src/c577484/src/web-components/plugin/plugin.component.ts#lines-25)

## Methods

### attributedChangedCallback

▸ **attributedChangedCallback**(`name`, `oldValue`, `newValue`): `void`

Called when an attribute is added, removed, updated, or replaced on the custom element. Only called for observed attributes.

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |
| `oldValue` | `string` |
| `newValue` | `string` |

#### Returns

`void`

#### Defined in

[web-components/plugin/plugin.component.ts:139](https://bitbucket.org/prcode/harness/src/c577484/src/web-components/plugin/plugin.component.ts#lines-139)

___

### cancel

▸ **cancel**(): `void`

#### Returns

`void`

#### Defined in

[web-components/plugin/plugin.component.ts:87](https://bitbucket.org/prcode/harness/src/c577484/src/web-components/plugin/plugin.component.ts#lines-87)

___

### complete

▸ **complete**(`blob`, `metadata?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `blob` | `any` |
| `metadata?` | `any` |

#### Returns

`void`

#### Defined in

[web-components/plugin/plugin.component.ts:76](https://bitbucket.org/prcode/harness/src/c577484/src/web-components/plugin/plugin.component.ts#lines-76)

___

### connectedCallback

▸ **connectedCallback**(): `void`

Custom element added to the page event

#### Returns

`void`

#### Defined in

[web-components/plugin/plugin.component.ts:122](https://bitbucket.org/prcode/harness/src/c577484/src/web-components/plugin/plugin.component.ts#lines-122)

___

### disconnectedCallback

▸ **disconnectedCallback**(): `void`

Custom element removed from the page

#### Returns

`void`

#### Defined in

[web-components/plugin/plugin.component.ts:129](https://bitbucket.org/prcode/harness/src/c577484/src/web-components/plugin/plugin.component.ts#lines-129)

___

### initialize

▸ **initialize**(`metadata`): `void`

The platform calls this method with the options reqiured for the plugin.

#### Parameters

| Name | Type |
| :------ | :------ |
| `metadata` | `any` |

#### Returns

`void`

#### Defined in

[web-components/plugin/plugin.component.ts:64](https://bitbucket.org/prcode/harness/src/c577484/src/web-components/plugin/plugin.component.ts#lines-64)

___

### loadComponent

▸ **loadComponent**(`htmlFile`, `componentStyles`): `Promise`\<`void`\>

Loads the HTML and SCSS styles into the web component

#### Parameters

| Name | Type |
| :------ | :------ |
| `htmlFile` | `any` |
| `componentStyles` | `any` |

#### Returns

`Promise`\<`void`\>

#### Defined in

[web-components/plugin/plugin.component.ts:49](https://bitbucket.org/prcode/harness/src/c577484/src/web-components/plugin/plugin.component.ts#lines-49)

___

### setup

▸ **setup**(): `void`

#### Returns

`void`

#### Defined in

[web-components/plugin/plugin.component.ts:72](https://bitbucket.org/prcode/harness/src/c577484/src/web-components/plugin/plugin.component.ts#lines-72)

___

### test

▸ **test**(): `void`

#### Returns

`void`

#### Defined in

[web-components/plugin/plugin.component.ts:94](https://bitbucket.org/prcode/harness/src/c577484/src/web-components/plugin/plugin.component.ts#lines-94)

___

### toBlob

▸ **toBlob**(): `any`

#### Returns

`any`

a blob of an HTML image

#### Defined in

[web-components/plugin/plugin.component.ts:102](https://bitbucket.org/prcode/harness/src/c577484/src/web-components/plugin/plugin.component.ts#lines-102)
