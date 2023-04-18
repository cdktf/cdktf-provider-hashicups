# `data_hashicups_ingredients`

Refer to the Terraform Registory for docs: [`data_hashicups_ingredients`](https://registry.terraform.io/providers/hashicorp/hashicups/0.3.1/docs/data-sources/ingredients).

# `dataHashicupsIngredients` Submodule <a name="`dataHashicupsIngredients` Submodule" id="@cdktf/provider-hashicups.dataHashicupsIngredients"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### DataHashicupsIngredients <a name="DataHashicupsIngredients" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients"></a>

Represents a {@link https://registry.terraform.io/providers/hashicorp/hashicups/0.3.1/docs/data-sources/ingredients hashicups_ingredients}.

#### Initializers <a name="Initializers" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.Initializer"></a>

```typescript
import { dataHashicupsIngredients } from '@cdktf/provider-hashicups'

new dataHashicupsIngredients.DataHashicupsIngredients(scope: Construct, id: string, config: DataHashicupsIngredientsConfig)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.Initializer.parameter.scope">scope</a></code> | <code>constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.Initializer.parameter.id">id</a></code> | <code>string</code> | The scoped construct ID. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.Initializer.parameter.config">config</a></code> | <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig">DataHashicupsIngredientsConfig</a></code> | *No description.* |

---

##### `scope`<sup>Required</sup> <a name="scope" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.Initializer.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.Initializer.parameter.id"></a>

- *Type:* string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `config`<sup>Required</sup> <a name="config" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.Initializer.parameter.config"></a>

- *Type:* <a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig">DataHashicupsIngredientsConfig</a>

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.toString">toString</a></code> | Returns a string representation of this construct. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.addOverride">addOverride</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.overrideLogicalId">overrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.resetOverrideLogicalId">resetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.toMetadata">toMetadata</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.toTerraform">toTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.resetId">resetId</a></code> | *No description.* |

---

##### `toString` <a name="toString" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.toString"></a>

```typescript
public toString(): string
```

Returns a string representation of this construct.

##### `addOverride` <a name="addOverride" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.addOverride"></a>

```typescript
public addOverride(path: string, value: any): void
```

###### `path`<sup>Required</sup> <a name="path" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.addOverride.parameter.path"></a>

- *Type:* string

---

###### `value`<sup>Required</sup> <a name="value" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.addOverride.parameter.value"></a>

- *Type:* any

---

##### `overrideLogicalId` <a name="overrideLogicalId" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.overrideLogicalId"></a>

```typescript
public overrideLogicalId(newLogicalId: string): void
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* string

The new logical ID to use for this stack element.

---

##### `resetOverrideLogicalId` <a name="resetOverrideLogicalId" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.resetOverrideLogicalId"></a>

```typescript
public resetOverrideLogicalId(): void
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `toMetadata` <a name="toMetadata" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.toMetadata"></a>

```typescript
public toMetadata(): any
```

##### `toTerraform` <a name="toTerraform" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.toTerraform"></a>

```typescript
public toTerraform(): any
```

Adds this resource to the terraform JSON output.

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `resetId` <a name="resetId" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.resetId"></a>

```typescript
public resetId(): void
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.isConstruct">isConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.isTerraformElement">isTerraformElement</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.isTerraformDataSource">isTerraformDataSource</a></code> | *No description.* |

---

##### `isConstruct` <a name="isConstruct" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.isConstruct"></a>

```typescript
import { dataHashicupsIngredients } from '@cdktf/provider-hashicups'

dataHashicupsIngredients.DataHashicupsIngredients.isConstruct(x: any)
```

Checks if `x` is a construct.

Use this method instead of `instanceof` to properly detect `Construct`
instances, even when the construct library is symlinked.

Explanation: in JavaScript, multiple copies of the `constructs` library on
disk are seen as independent, completely different libraries. As a
consequence, the class `Construct` in each copy of the `constructs` library
is seen as a different class, and an instance of one class will not test as
`instanceof` the other class. `npm install` will not create installations
like this, but users may manually symlink construct libraries together or
use a monorepo tool: in those cases, multiple copies of the `constructs`
library can be accidentally installed, and `instanceof` will behave
unpredictably. It is safest to avoid using `instanceof`, and using
this type-testing method instead.

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.isConstruct.parameter.x"></a>

- *Type:* any

Any object.

---

##### `isTerraformElement` <a name="isTerraformElement" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.isTerraformElement"></a>

```typescript
import { dataHashicupsIngredients } from '@cdktf/provider-hashicups'

dataHashicupsIngredients.DataHashicupsIngredients.isTerraformElement(x: any)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.isTerraformElement.parameter.x"></a>

- *Type:* any

---

##### `isTerraformDataSource` <a name="isTerraformDataSource" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.isTerraformDataSource"></a>

```typescript
import { dataHashicupsIngredients } from '@cdktf/provider-hashicups'

dataHashicupsIngredients.DataHashicupsIngredients.isTerraformDataSource(x: any)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.isTerraformDataSource.parameter.x"></a>

- *Type:* any

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.node">node</a></code> | <code>constructs.Node</code> | The tree node. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.cdktfStack">cdktfStack</a></code> | <code>cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.friendlyUniqueId">friendlyUniqueId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.terraformMetaArguments">terraformMetaArguments</a></code> | <code>{[ key: string ]: any}</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.terraformResourceType">terraformResourceType</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.terraformGeneratorMetadata">terraformGeneratorMetadata</a></code> | <code>cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.count">count</a></code> | <code>number \| cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.dependsOn">dependsOn</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.forEach">forEach</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.ingredients">ingredients</a></code> | <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList">DataHashicupsIngredientsIngredientsList</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.coffeeIdInput">coffeeIdInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.idInput">idInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.coffeeId">coffeeId</a></code> | <code>number</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.id">id</a></code> | <code>string</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.node"></a>

```typescript
public readonly node: Node;
```

- *Type:* constructs.Node

The tree node.

---

##### `cdktfStack`<sup>Required</sup> <a name="cdktfStack" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.cdktfStack"></a>

```typescript
public readonly cdktfStack: TerraformStack;
```

- *Type:* cdktf.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `friendlyUniqueId`<sup>Required</sup> <a name="friendlyUniqueId" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.friendlyUniqueId"></a>

```typescript
public readonly friendlyUniqueId: string;
```

- *Type:* string

---

##### `terraformMetaArguments`<sup>Required</sup> <a name="terraformMetaArguments" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.terraformMetaArguments"></a>

```typescript
public readonly terraformMetaArguments: {[ key: string ]: any};
```

- *Type:* {[ key: string ]: any}

---

##### `terraformResourceType`<sup>Required</sup> <a name="terraformResourceType" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.terraformResourceType"></a>

```typescript
public readonly terraformResourceType: string;
```

- *Type:* string

---

##### `terraformGeneratorMetadata`<sup>Optional</sup> <a name="terraformGeneratorMetadata" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.terraformGeneratorMetadata"></a>

```typescript
public readonly terraformGeneratorMetadata: TerraformProviderGeneratorMetadata;
```

- *Type:* cdktf.TerraformProviderGeneratorMetadata

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.count"></a>

```typescript
public readonly count: number | TerraformCount;
```

- *Type:* number | cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.dependsOn"></a>

```typescript
public readonly dependsOn: string[];
```

- *Type:* string[]

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.forEach"></a>

```typescript
public readonly forEach: ITerraformIterator;
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.lifecycle"></a>

```typescript
public readonly lifecycle: TerraformResourceLifecycle;
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.provider"></a>

```typescript
public readonly provider: TerraformProvider;
```

- *Type:* cdktf.TerraformProvider

---

##### `ingredients`<sup>Required</sup> <a name="ingredients" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.ingredients"></a>

```typescript
public readonly ingredients: DataHashicupsIngredientsIngredientsList;
```

- *Type:* <a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList">DataHashicupsIngredientsIngredientsList</a>

---

##### `coffeeIdInput`<sup>Optional</sup> <a name="coffeeIdInput" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.coffeeIdInput"></a>

```typescript
public readonly coffeeIdInput: number;
```

- *Type:* number

---

##### `idInput`<sup>Optional</sup> <a name="idInput" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.idInput"></a>

```typescript
public readonly idInput: string;
```

- *Type:* string

---

##### `coffeeId`<sup>Required</sup> <a name="coffeeId" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.coffeeId"></a>

```typescript
public readonly coffeeId: number;
```

- *Type:* number

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* string

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.tfResourceType">tfResourceType</a></code> | <code>string</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.tfResourceType"></a>

```typescript
public readonly tfResourceType: string;
```

- *Type:* string

---

## Structs <a name="Structs" id="Structs"></a>

### DataHashicupsIngredientsConfig <a name="DataHashicupsIngredientsConfig" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.Initializer"></a>

```typescript
import { dataHashicupsIngredients } from '@cdktf/provider-hashicups'

const dataHashicupsIngredientsConfig: dataHashicupsIngredients.DataHashicupsIngredientsConfig = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.connection">connection</a></code> | <code>cdktf.SSHProvisionerConnection \| cdktf.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.count">count</a></code> | <code>number \| cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.dependsOn">dependsOn</a></code> | <code>cdktf.ITerraformDependable[]</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.forEach">forEach</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.provisioners">provisioners</a></code> | <code>cdktf.FileProvisioner \| cdktf.LocalExecProvisioner \| cdktf.RemoteExecProvisioner[]</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.coffeeId">coffeeId</a></code> | <code>number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/hashicups/0.3.1/docs/data-sources/ingredients#coffee_id DataHashicupsIngredients#coffee_id}. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.id">id</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/hashicups/0.3.1/docs/data-sources/ingredients#id DataHashicupsIngredients#id}. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.connection"></a>

```typescript
public readonly connection: SSHProvisionerConnection | WinrmProvisionerConnection;
```

- *Type:* cdktf.SSHProvisionerConnection | cdktf.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.count"></a>

```typescript
public readonly count: number | TerraformCount;
```

- *Type:* number | cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.dependsOn"></a>

```typescript
public readonly dependsOn: ITerraformDependable[];
```

- *Type:* cdktf.ITerraformDependable[]

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.forEach"></a>

```typescript
public readonly forEach: ITerraformIterator;
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.lifecycle"></a>

```typescript
public readonly lifecycle: TerraformResourceLifecycle;
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.provider"></a>

```typescript
public readonly provider: TerraformProvider;
```

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.provisioners"></a>

```typescript
public readonly provisioners: FileProvisioner | LocalExecProvisioner | RemoteExecProvisioner[];
```

- *Type:* cdktf.FileProvisioner | cdktf.LocalExecProvisioner | cdktf.RemoteExecProvisioner[]

---

##### `coffeeId`<sup>Required</sup> <a name="coffeeId" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.coffeeId"></a>

```typescript
public readonly coffeeId: number;
```

- *Type:* number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/hashicups/0.3.1/docs/data-sources/ingredients#coffee_id DataHashicupsIngredients#coffee_id}.

---

##### `id`<sup>Optional</sup> <a name="id" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/hashicups/0.3.1/docs/data-sources/ingredients#id DataHashicupsIngredients#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

### DataHashicupsIngredientsIngredients <a name="DataHashicupsIngredientsIngredients" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredients"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredients.Initializer"></a>

```typescript
import { dataHashicupsIngredients } from '@cdktf/provider-hashicups'

const dataHashicupsIngredientsIngredients: dataHashicupsIngredients.DataHashicupsIngredientsIngredients = { ... }
```


## Classes <a name="Classes" id="Classes"></a>

### DataHashicupsIngredientsIngredientsList <a name="DataHashicupsIngredientsIngredientsList" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList"></a>

#### Initializers <a name="Initializers" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.Initializer"></a>

```typescript
import { dataHashicupsIngredients } from '@cdktf/provider-hashicups'

new dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList(terraformResource: IInterpolatingParent, terraformAttribute: string, wrapsSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.Initializer.parameter.wrapsSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.get">get</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `resolve` <a name="resolve" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.get"></a>

```typescript
public get(index: number): DataHashicupsIngredientsIngredientsOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.get.parameter.index"></a>

- *Type:* number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---


### DataHashicupsIngredientsIngredientsOutputReference <a name="DataHashicupsIngredientsIngredientsOutputReference" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.Initializer"></a>

```typescript
import { dataHashicupsIngredients } from '@cdktf/provider-hashicups'

new dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string, complexObjectIndex: number, complexObjectIsFromSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>number</code> | the index of this item in the list. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |

---

##### `computeFqn` <a name="computeFqn" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.id">id</a></code> | <code>number</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.name">name</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.quantity">quantity</a></code> | <code>number</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.unit">unit</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.internalValue">internalValue</a></code> | <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredients">DataHashicupsIngredientsIngredients</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.id"></a>

```typescript
public readonly id: number;
```

- *Type:* number

---

##### `name`<sup>Required</sup> <a name="name" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.name"></a>

```typescript
public readonly name: string;
```

- *Type:* string

---

##### `quantity`<sup>Required</sup> <a name="quantity" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.quantity"></a>

```typescript
public readonly quantity: number;
```

- *Type:* number

---

##### `unit`<sup>Required</sup> <a name="unit" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.unit"></a>

```typescript
public readonly unit: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: DataHashicupsIngredientsIngredients;
```

- *Type:* <a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredients">DataHashicupsIngredientsIngredients</a>

---



