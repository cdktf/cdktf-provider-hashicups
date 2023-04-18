# `data_hashicups_order`

Refer to the Terraform Registory for docs: [`data_hashicups_order`](https://registry.terraform.io/providers/hashicorp/hashicups/0.3.1/docs/data-sources/order).

# `dataHashicupsOrder` Submodule <a name="`dataHashicupsOrder` Submodule" id="@cdktf/provider-hashicups.dataHashicupsOrder"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### DataHashicupsOrder <a name="DataHashicupsOrder" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder"></a>

Represents a {@link https://registry.terraform.io/providers/hashicorp/hashicups/0.3.1/docs/data-sources/order hashicups_order}.

#### Initializers <a name="Initializers" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.Initializer"></a>

```go
import "github.com/cdktf/cdktf-provider-hashicups-go/hashicups/datahashicupsorder"

datahashicupsorder.NewDataHashicupsOrder(scope Construct, id *string, config DataHashicupsOrderConfig) DataHashicupsOrder
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.Initializer.parameter.scope">scope</a></code> | <code>github.com/aws/constructs-go/constructs/v10.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.Initializer.parameter.id">id</a></code> | <code>*string</code> | The scoped construct ID. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.Initializer.parameter.config">config</a></code> | <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderConfig">DataHashicupsOrderConfig</a></code> | *No description.* |

---

##### `scope`<sup>Required</sup> <a name="scope" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.Initializer.parameter.scope"></a>

- *Type:* github.com/aws/constructs-go/constructs/v10.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.Initializer.parameter.id"></a>

- *Type:* *string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `config`<sup>Required</sup> <a name="config" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.Initializer.parameter.config"></a>

- *Type:* <a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderConfig">DataHashicupsOrderConfig</a>

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.toString">ToString</a></code> | Returns a string representation of this construct. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.addOverride">AddOverride</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.overrideLogicalId">OverrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.resetOverrideLogicalId">ResetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.toMetadata">ToMetadata</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.toTerraform">ToTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |

---

##### `ToString` <a name="ToString" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.toString"></a>

```go
func ToString() *string
```

Returns a string representation of this construct.

##### `AddOverride` <a name="AddOverride" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.addOverride"></a>

```go
func AddOverride(path *string, value interface{})
```

###### `path`<sup>Required</sup> <a name="path" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.addOverride.parameter.path"></a>

- *Type:* *string

---

###### `value`<sup>Required</sup> <a name="value" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.addOverride.parameter.value"></a>

- *Type:* interface{}

---

##### `OverrideLogicalId` <a name="OverrideLogicalId" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.overrideLogicalId"></a>

```go
func OverrideLogicalId(newLogicalId *string)
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* *string

The new logical ID to use for this stack element.

---

##### `ResetOverrideLogicalId` <a name="ResetOverrideLogicalId" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.resetOverrideLogicalId"></a>

```go
func ResetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `ToMetadata` <a name="ToMetadata" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.toMetadata"></a>

```go
func ToMetadata() interface{}
```

##### `ToTerraform` <a name="ToTerraform" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.toTerraform"></a>

```go
func ToTerraform() interface{}
```

Adds this resource to the terraform JSON output.

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.isConstruct">IsConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.isTerraformElement">IsTerraformElement</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.isTerraformDataSource">IsTerraformDataSource</a></code> | *No description.* |

---

##### `IsConstruct` <a name="IsConstruct" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.isConstruct"></a>

```go
import "github.com/cdktf/cdktf-provider-hashicups-go/hashicups/datahashicupsorder"

datahashicupsorder.DataHashicupsOrder_IsConstruct(x interface{}) *bool
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

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.isConstruct.parameter.x"></a>

- *Type:* interface{}

Any object.

---

##### `IsTerraformElement` <a name="IsTerraformElement" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.isTerraformElement"></a>

```go
import "github.com/cdktf/cdktf-provider-hashicups-go/hashicups/datahashicupsorder"

datahashicupsorder.DataHashicupsOrder_IsTerraformElement(x interface{}) *bool
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.isTerraformElement.parameter.x"></a>

- *Type:* interface{}

---

##### `IsTerraformDataSource` <a name="IsTerraformDataSource" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.isTerraformDataSource"></a>

```go
import "github.com/cdktf/cdktf-provider-hashicups-go/hashicups/datahashicupsorder"

datahashicupsorder.DataHashicupsOrder_IsTerraformDataSource(x interface{}) *bool
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.isTerraformDataSource.parameter.x"></a>

- *Type:* interface{}

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.node">Node</a></code> | <code>github.com/aws/constructs-go/constructs/v10.Node</code> | The tree node. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.cdktfStack">CdktfStack</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.friendlyUniqueId">FriendlyUniqueId</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.terraformMetaArguments">TerraformMetaArguments</a></code> | <code>*map[string]interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.terraformResourceType">TerraformResourceType</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.terraformGeneratorMetadata">TerraformGeneratorMetadata</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.count">Count</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.dependsOn">DependsOn</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.forEach">ForEach</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.lifecycle">Lifecycle</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.provider">Provider</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.items">Items</a></code> | <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsList">DataHashicupsOrderItemsList</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.idInput">IdInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.id">Id</a></code> | <code>*f64</code> | *No description.* |

---

##### `Node`<sup>Required</sup> <a name="Node" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.node"></a>

```go
func Node() Node
```

- *Type:* github.com/aws/constructs-go/constructs/v10.Node

The tree node.

---

##### `CdktfStack`<sup>Required</sup> <a name="CdktfStack" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.cdktfStack"></a>

```go
func CdktfStack() TerraformStack
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformStack

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `FriendlyUniqueId`<sup>Required</sup> <a name="FriendlyUniqueId" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.friendlyUniqueId"></a>

```go
func FriendlyUniqueId() *string
```

- *Type:* *string

---

##### `TerraformMetaArguments`<sup>Required</sup> <a name="TerraformMetaArguments" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.terraformMetaArguments"></a>

```go
func TerraformMetaArguments() *map[string]interface{}
```

- *Type:* *map[string]interface{}

---

##### `TerraformResourceType`<sup>Required</sup> <a name="TerraformResourceType" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.terraformResourceType"></a>

```go
func TerraformResourceType() *string
```

- *Type:* *string

---

##### `TerraformGeneratorMetadata`<sup>Optional</sup> <a name="TerraformGeneratorMetadata" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.terraformGeneratorMetadata"></a>

```go
func TerraformGeneratorMetadata() TerraformProviderGeneratorMetadata
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProviderGeneratorMetadata

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.count"></a>

```go
func Count() interface{}
```

- *Type:* interface{}

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.dependsOn"></a>

```go
func DependsOn() *[]*string
```

- *Type:* *[]*string

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.forEach"></a>

```go
func ForEach() ITerraformIterator
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.lifecycle"></a>

```go
func Lifecycle() TerraformResourceLifecycle
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.provider"></a>

```go
func Provider() TerraformProvider
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider

---

##### `Items`<sup>Required</sup> <a name="Items" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.items"></a>

```go
func Items() DataHashicupsOrderItemsList
```

- *Type:* <a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsList">DataHashicupsOrderItemsList</a>

---

##### `IdInput`<sup>Optional</sup> <a name="IdInput" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.idInput"></a>

```go
func IdInput() *f64
```

- *Type:* *f64

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.id"></a>

```go
func Id() *f64
```

- *Type:* *f64

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.tfResourceType">TfResourceType</a></code> | <code>*string</code> | *No description.* |

---

##### `TfResourceType`<sup>Required</sup> <a name="TfResourceType" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.tfResourceType"></a>

```go
func TfResourceType() *string
```

- *Type:* *string

---

## Structs <a name="Structs" id="Structs"></a>

### DataHashicupsOrderConfig <a name="DataHashicupsOrderConfig" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderConfig"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderConfig.Initializer"></a>

```go
import "github.com/cdktf/cdktf-provider-hashicups-go/hashicups/datahashicupsorder"

&datahashicupsorder.DataHashicupsOrderConfig {
	Connection: interface{},
	Count: interface{},
	DependsOn: *[]github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformDependable,
	ForEach: github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator,
	Lifecycle: github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle,
	Provider: github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider,
	Provisioners: *[]interface{},
	Id: *f64,
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderConfig.property.connection">Connection</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderConfig.property.count">Count</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderConfig.property.dependsOn">DependsOn</a></code> | <code>*[]github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformDependable</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderConfig.property.forEach">ForEach</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderConfig.property.lifecycle">Lifecycle</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderConfig.property.provider">Provider</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderConfig.property.provisioners">Provisioners</a></code> | <code>*[]interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderConfig.property.id">Id</a></code> | <code>*f64</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/hashicups/0.3.1/docs/data-sources/order#id DataHashicupsOrder#id}. |

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderConfig.property.connection"></a>

```go
Connection interface{}
```

- *Type:* interface{}

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderConfig.property.count"></a>

```go
Count interface{}
```

- *Type:* interface{}

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderConfig.property.dependsOn"></a>

```go
DependsOn *[]ITerraformDependable
```

- *Type:* *[]github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformDependable

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderConfig.property.forEach"></a>

```go
ForEach ITerraformIterator
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderConfig.property.lifecycle"></a>

```go
Lifecycle TerraformResourceLifecycle
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderConfig.property.provider"></a>

```go
Provider TerraformProvider
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderConfig.property.provisioners"></a>

```go
Provisioners *[]interface{}
```

- *Type:* *[]interface{}

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderConfig.property.id"></a>

```go
Id *f64
```

- *Type:* *f64

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/hashicups/0.3.1/docs/data-sources/order#id DataHashicupsOrder#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

### DataHashicupsOrderItems <a name="DataHashicupsOrderItems" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItems"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItems.Initializer"></a>

```go
import "github.com/cdktf/cdktf-provider-hashicups-go/hashicups/datahashicupsorder"

&datahashicupsorder.DataHashicupsOrderItems {

}
```


## Classes <a name="Classes" id="Classes"></a>

### DataHashicupsOrderItemsList <a name="DataHashicupsOrderItemsList" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsList"></a>

#### Initializers <a name="Initializers" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsList.Initializer"></a>

```go
import "github.com/cdktf/cdktf-provider-hashicups-go/hashicups/datahashicupsorder"

datahashicupsorder.NewDataHashicupsOrderItemsList(terraformResource IInterpolatingParent, terraformAttribute *string, wrapsSet *bool) DataHashicupsOrderItemsList
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsList.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsList.Initializer.parameter.wrapsSet"></a>

- *Type:* *bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsList.get">Get</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsList.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `Resolve` <a name="Resolve" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsList.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsList.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsList.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsList.get"></a>

```go
func Get(index *f64) DataHashicupsOrderItemsOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsList.get.parameter.index"></a>

- *Type:* *f64

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsList.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsList.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsList.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsList.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---


### DataHashicupsOrderItemsOutputReference <a name="DataHashicupsOrderItemsOutputReference" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.Initializer"></a>

```go
import "github.com/cdktf/cdktf-provider-hashicups-go/hashicups/datahashicupsorder"

datahashicupsorder.NewDataHashicupsOrderItemsOutputReference(terraformResource IInterpolatingParent, terraformAttribute *string, complexObjectIndex *f64, complexObjectIsFromSet *bool) DataHashicupsOrderItemsOutputReference
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>*f64</code> | the index of this item in the list. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* *f64

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* *bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(property *string) IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* *string

---

##### `Resolve` <a name="Resolve" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.property.coffeeDescription">CoffeeDescription</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.property.coffeeId">CoffeeId</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.property.coffeeImage">CoffeeImage</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.property.coffeeName">CoffeeName</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.property.coffeePrice">CoffeePrice</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.property.coffeeTeaser">CoffeeTeaser</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.property.quantity">Quantity</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.property.internalValue">InternalValue</a></code> | <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItems">DataHashicupsOrderItems</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `CoffeeDescription`<sup>Required</sup> <a name="CoffeeDescription" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.property.coffeeDescription"></a>

```go
func CoffeeDescription() *string
```

- *Type:* *string

---

##### `CoffeeId`<sup>Required</sup> <a name="CoffeeId" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.property.coffeeId"></a>

```go
func CoffeeId() *f64
```

- *Type:* *f64

---

##### `CoffeeImage`<sup>Required</sup> <a name="CoffeeImage" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.property.coffeeImage"></a>

```go
func CoffeeImage() *string
```

- *Type:* *string

---

##### `CoffeeName`<sup>Required</sup> <a name="CoffeeName" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.property.coffeeName"></a>

```go
func CoffeeName() *string
```

- *Type:* *string

---

##### `CoffeePrice`<sup>Required</sup> <a name="CoffeePrice" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.property.coffeePrice"></a>

```go
func CoffeePrice() *f64
```

- *Type:* *f64

---

##### `CoffeeTeaser`<sup>Required</sup> <a name="CoffeeTeaser" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.property.coffeeTeaser"></a>

```go
func CoffeeTeaser() *string
```

- *Type:* *string

---

##### `Quantity`<sup>Required</sup> <a name="Quantity" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.property.quantity"></a>

```go
func Quantity() *f64
```

- *Type:* *f64

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.property.internalValue"></a>

```go
func InternalValue() DataHashicupsOrderItems
```

- *Type:* <a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItems">DataHashicupsOrderItems</a>

---



