# `data_hashicups_ingredients`

Refer to the Terraform Registory for docs: [`data_hashicups_ingredients`](https://www.terraform.io/docs/providers/hashicups/d/ingredients).

# `dataHashicupsIngredients` Submodule <a name="`dataHashicupsIngredients` Submodule" id="@cdktf/provider-hashicups.dataHashicupsIngredients"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### DataHashicupsIngredients <a name="DataHashicupsIngredients" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients"></a>

Represents a {@link https://www.terraform.io/docs/providers/hashicups/d/ingredients hashicups_ingredients}.

#### Initializers <a name="Initializers" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Hashicups;

new DataHashicupsIngredients(Construct Scope, string Id, DataHashicupsIngredientsConfig Config);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.Initializer.parameter.scope">Scope</a></code> | <code>Constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.Initializer.parameter.id">Id</a></code> | <code>string</code> | The scoped construct ID. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.Initializer.parameter.config">Config</a></code> | <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig">DataHashicupsIngredientsConfig</a></code> | *No description.* |

---

##### `Scope`<sup>Required</sup> <a name="Scope" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.Initializer.parameter.scope"></a>

- *Type:* Constructs.Construct

The scope in which to define this construct.

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.Initializer.parameter.id"></a>

- *Type:* string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `Config`<sup>Required</sup> <a name="Config" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.Initializer.parameter.config"></a>

- *Type:* <a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig">DataHashicupsIngredientsConfig</a>

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.toString">ToString</a></code> | Returns a string representation of this construct. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.addOverride">AddOverride</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.overrideLogicalId">OverrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.resetOverrideLogicalId">ResetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.toMetadata">ToMetadata</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.toTerraform">ToTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.resetId">ResetId</a></code> | *No description.* |

---

##### `ToString` <a name="ToString" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.toString"></a>

```csharp
private string ToString()
```

Returns a string representation of this construct.

##### `AddOverride` <a name="AddOverride" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.addOverride"></a>

```csharp
private void AddOverride(string Path, object Value)
```

###### `Path`<sup>Required</sup> <a name="Path" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.addOverride.parameter.path"></a>

- *Type:* string

---

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.addOverride.parameter.value"></a>

- *Type:* object

---

##### `OverrideLogicalId` <a name="OverrideLogicalId" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.overrideLogicalId"></a>

```csharp
private void OverrideLogicalId(string NewLogicalId)
```

Overrides the auto-generated logical ID with a specific ID.

###### `NewLogicalId`<sup>Required</sup> <a name="NewLogicalId" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* string

The new logical ID to use for this stack element.

---

##### `ResetOverrideLogicalId` <a name="ResetOverrideLogicalId" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.resetOverrideLogicalId"></a>

```csharp
private void ResetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `ToMetadata` <a name="ToMetadata" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.toMetadata"></a>

```csharp
private object ToMetadata()
```

##### `ToTerraform` <a name="ToTerraform" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.toTerraform"></a>

```csharp
private object ToTerraform()
```

Adds this resource to the terraform JSON output.

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `ResetId` <a name="ResetId" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.resetId"></a>

```csharp
private void ResetId()
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.isConstruct">IsConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.isTerraformElement">IsTerraformElement</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.isTerraformDataSource">IsTerraformDataSource</a></code> | *No description.* |

---

##### `IsConstruct` <a name="IsConstruct" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.isConstruct"></a>

```csharp
using HashiCorp.Cdktf.Providers.Hashicups;

DataHashicupsIngredients.IsConstruct(object X);
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

###### `X`<sup>Required</sup> <a name="X" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.isConstruct.parameter.x"></a>

- *Type:* object

Any object.

---

##### `IsTerraformElement` <a name="IsTerraformElement" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.isTerraformElement"></a>

```csharp
using HashiCorp.Cdktf.Providers.Hashicups;

DataHashicupsIngredients.IsTerraformElement(object X);
```

###### `X`<sup>Required</sup> <a name="X" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.isTerraformElement.parameter.x"></a>

- *Type:* object

---

##### `IsTerraformDataSource` <a name="IsTerraformDataSource" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.isTerraformDataSource"></a>

```csharp
using HashiCorp.Cdktf.Providers.Hashicups;

DataHashicupsIngredients.IsTerraformDataSource(object X);
```

###### `X`<sup>Required</sup> <a name="X" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.isTerraformDataSource.parameter.x"></a>

- *Type:* object

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.node">Node</a></code> | <code>Constructs.Node</code> | The tree node. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.cdktfStack">CdktfStack</a></code> | <code>HashiCorp.Cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.friendlyUniqueId">FriendlyUniqueId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.terraformMetaArguments">TerraformMetaArguments</a></code> | <code>System.Collections.Generic.IDictionary<string, object></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.terraformResourceType">TerraformResourceType</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.terraformGeneratorMetadata">TerraformGeneratorMetadata</a></code> | <code>HashiCorp.Cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.count">Count</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.dependsOn">DependsOn</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.forEach">ForEach</a></code> | <code>HashiCorp.Cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.lifecycle">Lifecycle</a></code> | <code>HashiCorp.Cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.provider">Provider</a></code> | <code>HashiCorp.Cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.ingredients">Ingredients</a></code> | <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList">DataHashicupsIngredientsIngredientsList</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.coffeeIdInput">CoffeeIdInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.idInput">IdInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.coffeeId">CoffeeId</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.id">Id</a></code> | <code>string</code> | *No description.* |

---

##### `Node`<sup>Required</sup> <a name="Node" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.node"></a>

```csharp
public Node Node { get; }
```

- *Type:* Constructs.Node

The tree node.

---

##### `CdktfStack`<sup>Required</sup> <a name="CdktfStack" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.cdktfStack"></a>

```csharp
public TerraformStack CdktfStack { get; }
```

- *Type:* HashiCorp.Cdktf.TerraformStack

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `FriendlyUniqueId`<sup>Required</sup> <a name="FriendlyUniqueId" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.friendlyUniqueId"></a>

```csharp
public string FriendlyUniqueId { get; }
```

- *Type:* string

---

##### `TerraformMetaArguments`<sup>Required</sup> <a name="TerraformMetaArguments" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.terraformMetaArguments"></a>

```csharp
public System.Collections.Generic.IDictionary<string, object> TerraformMetaArguments { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, object>

---

##### `TerraformResourceType`<sup>Required</sup> <a name="TerraformResourceType" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.terraformResourceType"></a>

```csharp
public string TerraformResourceType { get; }
```

- *Type:* string

---

##### `TerraformGeneratorMetadata`<sup>Optional</sup> <a name="TerraformGeneratorMetadata" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.terraformGeneratorMetadata"></a>

```csharp
public TerraformProviderGeneratorMetadata TerraformGeneratorMetadata { get; }
```

- *Type:* HashiCorp.Cdktf.TerraformProviderGeneratorMetadata

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.count"></a>

```csharp
public double Count { get; }
```

- *Type:* double

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.dependsOn"></a>

```csharp
public string[] DependsOn { get; }
```

- *Type:* string[]

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.forEach"></a>

```csharp
public ITerraformIterator ForEach { get; }
```

- *Type:* HashiCorp.Cdktf.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.lifecycle"></a>

```csharp
public TerraformResourceLifecycle Lifecycle { get; }
```

- *Type:* HashiCorp.Cdktf.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.provider"></a>

```csharp
public TerraformProvider Provider { get; }
```

- *Type:* HashiCorp.Cdktf.TerraformProvider

---

##### `Ingredients`<sup>Required</sup> <a name="Ingredients" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.ingredients"></a>

```csharp
public DataHashicupsIngredientsIngredientsList Ingredients { get; }
```

- *Type:* <a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList">DataHashicupsIngredientsIngredientsList</a>

---

##### `CoffeeIdInput`<sup>Optional</sup> <a name="CoffeeIdInput" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.coffeeIdInput"></a>

```csharp
public double CoffeeIdInput { get; }
```

- *Type:* double

---

##### `IdInput`<sup>Optional</sup> <a name="IdInput" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.idInput"></a>

```csharp
public string IdInput { get; }
```

- *Type:* string

---

##### `CoffeeId`<sup>Required</sup> <a name="CoffeeId" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.coffeeId"></a>

```csharp
public double CoffeeId { get; }
```

- *Type:* double

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.id"></a>

```csharp
public string Id { get; }
```

- *Type:* string

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.tfResourceType">TfResourceType</a></code> | <code>string</code> | *No description.* |

---

##### `TfResourceType`<sup>Required</sup> <a name="TfResourceType" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.tfResourceType"></a>

```csharp
public string TfResourceType { get; }
```

- *Type:* string

---

## Structs <a name="Structs" id="Structs"></a>

### DataHashicupsIngredientsConfig <a name="DataHashicupsIngredientsConfig" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Hashicups;

new DataHashicupsIngredientsConfig {
    object Connection = null,
    double Count = null,
    ITerraformDependable[] DependsOn = null,
    ITerraformIterator ForEach = null,
    TerraformResourceLifecycle Lifecycle = null,
    TerraformProvider Provider = null,
    object[] Provisioners = null,
    double CoffeeId,
    string Id = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.connection">Connection</a></code> | <code>object</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.count">Count</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.dependsOn">DependsOn</a></code> | <code>HashiCorp.Cdktf.ITerraformDependable[]</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.forEach">ForEach</a></code> | <code>HashiCorp.Cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.lifecycle">Lifecycle</a></code> | <code>HashiCorp.Cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.provider">Provider</a></code> | <code>HashiCorp.Cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.provisioners">Provisioners</a></code> | <code>object[]</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.coffeeId">CoffeeId</a></code> | <code>double</code> | Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/hashicups/d/ingredients#coffee_id DataHashicupsIngredients#coffee_id}. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.id">Id</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/hashicups/d/ingredients#id DataHashicupsIngredients#id}. |

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.connection"></a>

```csharp
public object Connection { get; set; }
```

- *Type:* object

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.count"></a>

```csharp
public double Count { get; set; }
```

- *Type:* double

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.dependsOn"></a>

```csharp
public ITerraformDependable[] DependsOn { get; set; }
```

- *Type:* HashiCorp.Cdktf.ITerraformDependable[]

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.forEach"></a>

```csharp
public ITerraformIterator ForEach { get; set; }
```

- *Type:* HashiCorp.Cdktf.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.lifecycle"></a>

```csharp
public TerraformResourceLifecycle Lifecycle { get; set; }
```

- *Type:* HashiCorp.Cdktf.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.provider"></a>

```csharp
public TerraformProvider Provider { get; set; }
```

- *Type:* HashiCorp.Cdktf.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.provisioners"></a>

```csharp
public object[] Provisioners { get; set; }
```

- *Type:* object[]

---

##### `CoffeeId`<sup>Required</sup> <a name="CoffeeId" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.coffeeId"></a>

```csharp
public double CoffeeId { get; set; }
```

- *Type:* double

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/hashicups/d/ingredients#coffee_id DataHashicupsIngredients#coffee_id}.

---

##### `Id`<sup>Optional</sup> <a name="Id" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.id"></a>

```csharp
public string Id { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/hashicups/d/ingredients#id DataHashicupsIngredients#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

### DataHashicupsIngredientsIngredients <a name="DataHashicupsIngredientsIngredients" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredients"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredients.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Hashicups;

new DataHashicupsIngredientsIngredients {

};
```


## Classes <a name="Classes" id="Classes"></a>

### DataHashicupsIngredientsIngredientsList <a name="DataHashicupsIngredientsIngredientsList" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList"></a>

#### Initializers <a name="Initializers" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Hashicups;

new DataHashicupsIngredientsIngredientsList(IInterpolatingParent TerraformResource, string TerraformAttribute, bool WrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>HashiCorp.Cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.Initializer.parameter.wrapsSet">WrapsSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.Initializer.parameter.terraformResource"></a>

- *Type:* HashiCorp.Cdktf.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `WrapsSet`<sup>Required</sup> <a name="WrapsSet" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.get">Get</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `Resolve` <a name="Resolve" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.resolve.parameter._context"></a>

- *Type:* HashiCorp.Cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.get"></a>

```csharp
private DataHashicupsIngredientsIngredientsOutputReference Get(double Index)
```

###### `Index`<sup>Required</sup> <a name="Index" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.get.parameter.index"></a>

- *Type:* double

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---


### DataHashicupsIngredientsIngredientsOutputReference <a name="DataHashicupsIngredientsIngredientsOutputReference" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Hashicups;

new DataHashicupsIngredientsIngredientsOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute, double ComplexObjectIndex, bool ComplexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>HashiCorp.Cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.Initializer.parameter.complexObjectIndex">ComplexObjectIndex</a></code> | <code>double</code> | the index of this item in the list. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.Initializer.parameter.complexObjectIsFromSet">ComplexObjectIsFromSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* HashiCorp.Cdktf.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `ComplexObjectIndex`<sup>Required</sup> <a name="ComplexObjectIndex" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* double

the index of this item in the list.

---

##### `ComplexObjectIsFromSet`<sup>Required</sup> <a name="ComplexObjectIsFromSet" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.resolve.parameter._context"></a>

- *Type:* HashiCorp.Cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.id">Id</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.name">Name</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.quantity">Quantity</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.unit">Unit</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.internalValue">InternalValue</a></code> | <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredients">DataHashicupsIngredientsIngredients</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.id"></a>

```csharp
public double Id { get; }
```

- *Type:* double

---

##### `Name`<sup>Required</sup> <a name="Name" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.name"></a>

```csharp
public string Name { get; }
```

- *Type:* string

---

##### `Quantity`<sup>Required</sup> <a name="Quantity" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.quantity"></a>

```csharp
public double Quantity { get; }
```

- *Type:* double

---

##### `Unit`<sup>Required</sup> <a name="Unit" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.unit"></a>

```csharp
public string Unit { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.internalValue"></a>

```csharp
public DataHashicupsIngredientsIngredients InternalValue { get; }
```

- *Type:* <a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredients">DataHashicupsIngredientsIngredients</a>

---



