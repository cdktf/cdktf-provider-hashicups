# `dataHashicupsIngredients` Submodule <a name="`dataHashicupsIngredients` Submodule" id="@cdktf/provider-hashicups.dataHashicupsIngredients"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### DataHashicupsIngredients <a name="DataHashicupsIngredients" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients"></a>

Represents a {@link https://www.terraform.io/docs/providers/hashicups/d/ingredients hashicups_ingredients}.

#### Initializers <a name="Initializers" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.Initializer"></a>

```go
import "github.com/cdktf/cdktf-provider-hashicups-go/hashicups/v3/datahashicupsingredients"

datahashicupsingredients.NewDataHashicupsIngredients(scope Construct, id *string, config DataHashicupsIngredientsConfig) DataHashicupsIngredients
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.Initializer.parameter.scope">scope</a></code> | <code>github.com/aws/constructs-go/constructs/v10.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.Initializer.parameter.id">id</a></code> | <code>*string</code> | The scoped construct ID. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.Initializer.parameter.config">config</a></code> | <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig">DataHashicupsIngredientsConfig</a></code> | *No description.* |

---

##### `scope`<sup>Required</sup> <a name="scope" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.Initializer.parameter.scope"></a>

- *Type:* github.com/aws/constructs-go/constructs/v10.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.Initializer.parameter.id"></a>

- *Type:* *string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `config`<sup>Required</sup> <a name="config" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.Initializer.parameter.config"></a>

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

```go
func ToString() *string
```

Returns a string representation of this construct.

##### `AddOverride` <a name="AddOverride" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.addOverride"></a>

```go
func AddOverride(path *string, value interface{})
```

###### `path`<sup>Required</sup> <a name="path" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.addOverride.parameter.path"></a>

- *Type:* *string

---

###### `value`<sup>Required</sup> <a name="value" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.addOverride.parameter.value"></a>

- *Type:* interface{}

---

##### `OverrideLogicalId` <a name="OverrideLogicalId" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.overrideLogicalId"></a>

```go
func OverrideLogicalId(newLogicalId *string)
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* *string

The new logical ID to use for this stack element.

---

##### `ResetOverrideLogicalId` <a name="ResetOverrideLogicalId" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.resetOverrideLogicalId"></a>

```go
func ResetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `ToMetadata` <a name="ToMetadata" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.toMetadata"></a>

```go
func ToMetadata() interface{}
```

##### `ToTerraform` <a name="ToTerraform" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.toTerraform"></a>

```go
func ToTerraform() interface{}
```

Adds this resource to the terraform JSON output.

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `ResetId` <a name="ResetId" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.resetId"></a>

```go
func ResetId()
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.isConstruct">IsConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.isTerraformElement">IsTerraformElement</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.isTerraformDataSource">IsTerraformDataSource</a></code> | *No description.* |

---

##### `IsConstruct` <a name="IsConstruct" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.isConstruct"></a>

```go
import "github.com/cdktf/cdktf-provider-hashicups-go/hashicups/v3/datahashicupsingredients"

datahashicupsingredients.DataHashicupsIngredients_IsConstruct(x interface{}) *bool
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

- *Type:* interface{}

Any object.

---

##### `IsTerraformElement` <a name="IsTerraformElement" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.isTerraformElement"></a>

```go
import "github.com/cdktf/cdktf-provider-hashicups-go/hashicups/v3/datahashicupsingredients"

datahashicupsingredients.DataHashicupsIngredients_IsTerraformElement(x interface{}) *bool
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.isTerraformElement.parameter.x"></a>

- *Type:* interface{}

---

##### `IsTerraformDataSource` <a name="IsTerraformDataSource" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.isTerraformDataSource"></a>

```go
import "github.com/cdktf/cdktf-provider-hashicups-go/hashicups/v3/datahashicupsingredients"

datahashicupsingredients.DataHashicupsIngredients_IsTerraformDataSource(x interface{}) *bool
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.isTerraformDataSource.parameter.x"></a>

- *Type:* interface{}

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.node">Node</a></code> | <code>github.com/aws/constructs-go/constructs/v10.Node</code> | The tree node. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.cdktfStack">CdktfStack</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.friendlyUniqueId">FriendlyUniqueId</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.terraformMetaArguments">TerraformMetaArguments</a></code> | <code>*map[string]interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.terraformResourceType">TerraformResourceType</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.terraformGeneratorMetadata">TerraformGeneratorMetadata</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.count">Count</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.dependsOn">DependsOn</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.forEach">ForEach</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.lifecycle">Lifecycle</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.provider">Provider</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.ingredients">Ingredients</a></code> | <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList">DataHashicupsIngredientsIngredientsList</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.coffeeIdInput">CoffeeIdInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.idInput">IdInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.coffeeId">CoffeeId</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.id">Id</a></code> | <code>*string</code> | *No description.* |

---

##### `Node`<sup>Required</sup> <a name="Node" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.node"></a>

```go
func Node() Node
```

- *Type:* github.com/aws/constructs-go/constructs/v10.Node

The tree node.

---

##### `CdktfStack`<sup>Required</sup> <a name="CdktfStack" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.cdktfStack"></a>

```go
func CdktfStack() TerraformStack
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformStack

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `FriendlyUniqueId`<sup>Required</sup> <a name="FriendlyUniqueId" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.friendlyUniqueId"></a>

```go
func FriendlyUniqueId() *string
```

- *Type:* *string

---

##### `TerraformMetaArguments`<sup>Required</sup> <a name="TerraformMetaArguments" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.terraformMetaArguments"></a>

```go
func TerraformMetaArguments() *map[string]interface{}
```

- *Type:* *map[string]interface{}

---

##### `TerraformResourceType`<sup>Required</sup> <a name="TerraformResourceType" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.terraformResourceType"></a>

```go
func TerraformResourceType() *string
```

- *Type:* *string

---

##### `TerraformGeneratorMetadata`<sup>Optional</sup> <a name="TerraformGeneratorMetadata" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.terraformGeneratorMetadata"></a>

```go
func TerraformGeneratorMetadata() TerraformProviderGeneratorMetadata
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProviderGeneratorMetadata

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.count"></a>

```go
func Count() *f64
```

- *Type:* *f64

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.dependsOn"></a>

```go
func DependsOn() *[]*string
```

- *Type:* *[]*string

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.forEach"></a>

```go
func ForEach() ITerraformIterator
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.lifecycle"></a>

```go
func Lifecycle() TerraformResourceLifecycle
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.provider"></a>

```go
func Provider() TerraformProvider
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider

---

##### `Ingredients`<sup>Required</sup> <a name="Ingredients" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.ingredients"></a>

```go
func Ingredients() DataHashicupsIngredientsIngredientsList
```

- *Type:* <a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList">DataHashicupsIngredientsIngredientsList</a>

---

##### `CoffeeIdInput`<sup>Optional</sup> <a name="CoffeeIdInput" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.coffeeIdInput"></a>

```go
func CoffeeIdInput() *f64
```

- *Type:* *f64

---

##### `IdInput`<sup>Optional</sup> <a name="IdInput" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.idInput"></a>

```go
func IdInput() *string
```

- *Type:* *string

---

##### `CoffeeId`<sup>Required</sup> <a name="CoffeeId" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.coffeeId"></a>

```go
func CoffeeId() *f64
```

- *Type:* *f64

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.id"></a>

```go
func Id() *string
```

- *Type:* *string

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.tfResourceType">TfResourceType</a></code> | <code>*string</code> | *No description.* |

---

##### `TfResourceType`<sup>Required</sup> <a name="TfResourceType" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.tfResourceType"></a>

```go
func TfResourceType() *string
```

- *Type:* *string

---

## Structs <a name="Structs" id="Structs"></a>

### DataHashicupsIngredientsConfig <a name="DataHashicupsIngredientsConfig" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.Initializer"></a>

```go
import "github.com/cdktf/cdktf-provider-hashicups-go/hashicups/v3/datahashicupsingredients"

&datahashicupsingredients.DataHashicupsIngredientsConfig {
	Connection: interface{},
	Count: *f64,
	DependsOn: *[]github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformDependable,
	ForEach: github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator,
	Lifecycle: github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle,
	Provider: github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider,
	Provisioners: *[]interface{},
	CoffeeId: *f64,
	Id: *string,
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.connection">Connection</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.count">Count</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.dependsOn">DependsOn</a></code> | <code>*[]github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformDependable</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.forEach">ForEach</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.lifecycle">Lifecycle</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.provider">Provider</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.provisioners">Provisioners</a></code> | <code>*[]interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.coffeeId">CoffeeId</a></code> | <code>*f64</code> | Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/hashicups/d/ingredients#coffee_id DataHashicupsIngredients#coffee_id}. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.id">Id</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/hashicups/d/ingredients#id DataHashicupsIngredients#id}. |

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.connection"></a>

```go
Connection interface{}
```

- *Type:* interface{}

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.count"></a>

```go
Count *f64
```

- *Type:* *f64

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.dependsOn"></a>

```go
DependsOn *[]ITerraformDependable
```

- *Type:* *[]github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformDependable

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.forEach"></a>

```go
ForEach ITerraformIterator
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.lifecycle"></a>

```go
Lifecycle TerraformResourceLifecycle
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.provider"></a>

```go
Provider TerraformProvider
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.provisioners"></a>

```go
Provisioners *[]interface{}
```

- *Type:* *[]interface{}

---

##### `CoffeeId`<sup>Required</sup> <a name="CoffeeId" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.coffeeId"></a>

```go
CoffeeId *f64
```

- *Type:* *f64

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/hashicups/d/ingredients#coffee_id DataHashicupsIngredients#coffee_id}.

---

##### `Id`<sup>Optional</sup> <a name="Id" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.id"></a>

```go
Id *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/hashicups/d/ingredients#id DataHashicupsIngredients#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

### DataHashicupsIngredientsIngredients <a name="DataHashicupsIngredientsIngredients" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredients"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredients.Initializer"></a>

```go
import "github.com/cdktf/cdktf-provider-hashicups-go/hashicups/v3/datahashicupsingredients"

&datahashicupsingredients.DataHashicupsIngredientsIngredients {

}
```


## Classes <a name="Classes" id="Classes"></a>

### DataHashicupsIngredientsIngredientsList <a name="DataHashicupsIngredientsIngredientsList" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList"></a>

#### Initializers <a name="Initializers" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.Initializer"></a>

```go
import "github.com/cdktf/cdktf-provider-hashicups-go/hashicups/v3/datahashicupsingredients"

datahashicupsingredients.NewDataHashicupsIngredientsIngredientsList(terraformResource IInterpolatingParent, terraformAttribute *string, wrapsSet *bool) DataHashicupsIngredientsIngredientsList
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.Initializer.parameter.wrapsSet"></a>

- *Type:* *bool

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

```go
func ComputeFqn() *string
```

##### `Resolve` <a name="Resolve" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.get"></a>

```go
func Get(index *f64) DataHashicupsIngredientsIngredientsOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.get.parameter.index"></a>

- *Type:* *f64

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---


### DataHashicupsIngredientsIngredientsOutputReference <a name="DataHashicupsIngredientsIngredientsOutputReference" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.Initializer"></a>

```go
import "github.com/cdktf/cdktf-provider-hashicups-go/hashicups/v3/datahashicupsingredients"

datahashicupsingredients.NewDataHashicupsIngredientsIngredientsOutputReference(terraformResource IInterpolatingParent, terraformAttribute *string, complexObjectIndex *f64, complexObjectIsFromSet *bool) DataHashicupsIngredientsIngredientsOutputReference
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>*f64</code> | the index of this item in the list. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* *f64

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* *bool

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

```go
func ComputeFqn() *string
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(property *string) IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* *string

---

##### `Resolve` <a name="Resolve" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.id">Id</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.name">Name</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.quantity">Quantity</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.unit">Unit</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.internalValue">InternalValue</a></code> | <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredients">DataHashicupsIngredientsIngredients</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.id"></a>

```go
func Id() *f64
```

- *Type:* *f64

---

##### `Name`<sup>Required</sup> <a name="Name" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.name"></a>

```go
func Name() *string
```

- *Type:* *string

---

##### `Quantity`<sup>Required</sup> <a name="Quantity" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.quantity"></a>

```go
func Quantity() *f64
```

- *Type:* *f64

---

##### `Unit`<sup>Required</sup> <a name="Unit" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.unit"></a>

```go
func Unit() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.internalValue"></a>

```go
func InternalValue() DataHashicupsIngredientsIngredients
```

- *Type:* <a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredients">DataHashicupsIngredientsIngredients</a>

---



