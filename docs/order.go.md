# `order` Submodule <a name="`order` Submodule" id="@cdktf/provider-hashicups.order"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### Order <a name="Order" id="@cdktf/provider-hashicups.order.Order"></a>

Represents a {@link https://www.terraform.io/docs/providers/hashicups/r/order hashicups_order}.

#### Initializers <a name="Initializers" id="@cdktf/provider-hashicups.order.Order.Initializer"></a>

```go
import "github.com/cdktf/cdktf-provider-hashicups-go/hashicups/order"

order.NewOrder(scope Construct, id *string, config OrderConfig) Order
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.order.Order.Initializer.parameter.scope">scope</a></code> | <code>github.com/aws/constructs-go/constructs/v10.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktf/provider-hashicups.order.Order.Initializer.parameter.id">id</a></code> | <code>*string</code> | The scoped construct ID. |
| <code><a href="#@cdktf/provider-hashicups.order.Order.Initializer.parameter.config">config</a></code> | <code><a href="#@cdktf/provider-hashicups.order.OrderConfig">OrderConfig</a></code> | *No description.* |

---

##### `scope`<sup>Required</sup> <a name="scope" id="@cdktf/provider-hashicups.order.Order.Initializer.parameter.scope"></a>

- *Type:* github.com/aws/constructs-go/constructs/v10.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-hashicups.order.Order.Initializer.parameter.id"></a>

- *Type:* *string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `config`<sup>Required</sup> <a name="config" id="@cdktf/provider-hashicups.order.Order.Initializer.parameter.config"></a>

- *Type:* <a href="#@cdktf/provider-hashicups.order.OrderConfig">OrderConfig</a>

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-hashicups.order.Order.toString">ToString</a></code> | Returns a string representation of this construct. |
| <code><a href="#@cdktf/provider-hashicups.order.Order.addOverride">AddOverride</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.Order.overrideLogicalId">OverrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#@cdktf/provider-hashicups.order.Order.resetOverrideLogicalId">ResetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#@cdktf/provider-hashicups.order.Order.toMetadata">ToMetadata</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.Order.toTerraform">ToTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktf/provider-hashicups.order.Order.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.Order.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.Order.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.Order.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.Order.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.Order.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.Order.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.Order.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.Order.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.Order.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.Order.putItems">PutItems</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.Order.resetId">ResetId</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.Order.resetLastUpdated">ResetLastUpdated</a></code> | *No description.* |

---

##### `ToString` <a name="ToString" id="@cdktf/provider-hashicups.order.Order.toString"></a>

```go
func ToString() *string
```

Returns a string representation of this construct.

##### `AddOverride` <a name="AddOverride" id="@cdktf/provider-hashicups.order.Order.addOverride"></a>

```go
func AddOverride(path *string, value interface{})
```

###### `path`<sup>Required</sup> <a name="path" id="@cdktf/provider-hashicups.order.Order.addOverride.parameter.path"></a>

- *Type:* *string

---

###### `value`<sup>Required</sup> <a name="value" id="@cdktf/provider-hashicups.order.Order.addOverride.parameter.value"></a>

- *Type:* interface{}

---

##### `OverrideLogicalId` <a name="OverrideLogicalId" id="@cdktf/provider-hashicups.order.Order.overrideLogicalId"></a>

```go
func OverrideLogicalId(newLogicalId *string)
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="@cdktf/provider-hashicups.order.Order.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* *string

The new logical ID to use for this stack element.

---

##### `ResetOverrideLogicalId` <a name="ResetOverrideLogicalId" id="@cdktf/provider-hashicups.order.Order.resetOverrideLogicalId"></a>

```go
func ResetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `ToMetadata` <a name="ToMetadata" id="@cdktf/provider-hashicups.order.Order.toMetadata"></a>

```go
func ToMetadata() interface{}
```

##### `ToTerraform` <a name="ToTerraform" id="@cdktf/provider-hashicups.order.Order.toTerraform"></a>

```go
func ToTerraform() interface{}
```

Adds this resource to the terraform JSON output.

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktf/provider-hashicups.order.Order.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.order.Order.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktf/provider-hashicups.order.Order.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.order.Order.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktf/provider-hashicups.order.Order.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.order.Order.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktf/provider-hashicups.order.Order.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.order.Order.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktf/provider-hashicups.order.Order.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.order.Order.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktf/provider-hashicups.order.Order.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.order.Order.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktf/provider-hashicups.order.Order.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.order.Order.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktf/provider-hashicups.order.Order.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.order.Order.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktf/provider-hashicups.order.Order.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.order.Order.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktf/provider-hashicups.order.Order.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.order.Order.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `PutItems` <a name="PutItems" id="@cdktf/provider-hashicups.order.Order.putItems"></a>

```go
func PutItems(value interface{})
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktf/provider-hashicups.order.Order.putItems.parameter.value"></a>

- *Type:* interface{}

---

##### `ResetId` <a name="ResetId" id="@cdktf/provider-hashicups.order.Order.resetId"></a>

```go
func ResetId()
```

##### `ResetLastUpdated` <a name="ResetLastUpdated" id="@cdktf/provider-hashicups.order.Order.resetLastUpdated"></a>

```go
func ResetLastUpdated()
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-hashicups.order.Order.isConstruct">IsConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#@cdktf/provider-hashicups.order.Order.isTerraformElement">IsTerraformElement</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.Order.isTerraformResource">IsTerraformResource</a></code> | *No description.* |

---

##### `IsConstruct` <a name="IsConstruct" id="@cdktf/provider-hashicups.order.Order.isConstruct"></a>

```go
import "github.com/cdktf/cdktf-provider-hashicups-go/hashicups/order"

order.Order_IsConstruct(x interface{}) *bool
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

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-hashicups.order.Order.isConstruct.parameter.x"></a>

- *Type:* interface{}

Any object.

---

##### `IsTerraformElement` <a name="IsTerraformElement" id="@cdktf/provider-hashicups.order.Order.isTerraformElement"></a>

```go
import "github.com/cdktf/cdktf-provider-hashicups-go/hashicups/order"

order.Order_IsTerraformElement(x interface{}) *bool
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-hashicups.order.Order.isTerraformElement.parameter.x"></a>

- *Type:* interface{}

---

##### `IsTerraformResource` <a name="IsTerraformResource" id="@cdktf/provider-hashicups.order.Order.isTerraformResource"></a>

```go
import "github.com/cdktf/cdktf-provider-hashicups-go/hashicups/order"

order.Order_IsTerraformResource(x interface{}) *bool
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-hashicups.order.Order.isTerraformResource.parameter.x"></a>

- *Type:* interface{}

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.order.Order.property.node">Node</a></code> | <code>github.com/aws/constructs-go/constructs/v10.Node</code> | The tree node. |
| <code><a href="#@cdktf/provider-hashicups.order.Order.property.cdktfStack">CdktfStack</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.Order.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.Order.property.friendlyUniqueId">FriendlyUniqueId</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.Order.property.terraformMetaArguments">TerraformMetaArguments</a></code> | <code>*map[string]interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.Order.property.terraformResourceType">TerraformResourceType</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.Order.property.terraformGeneratorMetadata">TerraformGeneratorMetadata</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.Order.property.connection">Connection</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.Order.property.count">Count</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.Order.property.dependsOn">DependsOn</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.Order.property.forEach">ForEach</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.Order.property.lifecycle">Lifecycle</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.Order.property.provider">Provider</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.Order.property.provisioners">Provisioners</a></code> | <code>*[]interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.Order.property.items">Items</a></code> | <code><a href="#@cdktf/provider-hashicups.order.OrderItemsList">OrderItemsList</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.Order.property.idInput">IdInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.Order.property.itemsInput">ItemsInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.Order.property.lastUpdatedInput">LastUpdatedInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.Order.property.id">Id</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.Order.property.lastUpdated">LastUpdated</a></code> | <code>*string</code> | *No description.* |

---

##### `Node`<sup>Required</sup> <a name="Node" id="@cdktf/provider-hashicups.order.Order.property.node"></a>

```go
func Node() Node
```

- *Type:* github.com/aws/constructs-go/constructs/v10.Node

The tree node.

---

##### `CdktfStack`<sup>Required</sup> <a name="CdktfStack" id="@cdktf/provider-hashicups.order.Order.property.cdktfStack"></a>

```go
func CdktfStack() TerraformStack
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformStack

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktf/provider-hashicups.order.Order.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `FriendlyUniqueId`<sup>Required</sup> <a name="FriendlyUniqueId" id="@cdktf/provider-hashicups.order.Order.property.friendlyUniqueId"></a>

```go
func FriendlyUniqueId() *string
```

- *Type:* *string

---

##### `TerraformMetaArguments`<sup>Required</sup> <a name="TerraformMetaArguments" id="@cdktf/provider-hashicups.order.Order.property.terraformMetaArguments"></a>

```go
func TerraformMetaArguments() *map[string]interface{}
```

- *Type:* *map[string]interface{}

---

##### `TerraformResourceType`<sup>Required</sup> <a name="TerraformResourceType" id="@cdktf/provider-hashicups.order.Order.property.terraformResourceType"></a>

```go
func TerraformResourceType() *string
```

- *Type:* *string

---

##### `TerraformGeneratorMetadata`<sup>Optional</sup> <a name="TerraformGeneratorMetadata" id="@cdktf/provider-hashicups.order.Order.property.terraformGeneratorMetadata"></a>

```go
func TerraformGeneratorMetadata() TerraformProviderGeneratorMetadata
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProviderGeneratorMetadata

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="@cdktf/provider-hashicups.order.Order.property.connection"></a>

```go
func Connection() interface{}
```

- *Type:* interface{}

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktf/provider-hashicups.order.Order.property.count"></a>

```go
func Count() *f64
```

- *Type:* *f64

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktf/provider-hashicups.order.Order.property.dependsOn"></a>

```go
func DependsOn() *[]*string
```

- *Type:* *[]*string

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktf/provider-hashicups.order.Order.property.forEach"></a>

```go
func ForEach() ITerraformIterator
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktf/provider-hashicups.order.Order.property.lifecycle"></a>

```go
func Lifecycle() TerraformResourceLifecycle
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktf/provider-hashicups.order.Order.property.provider"></a>

```go
func Provider() TerraformProvider
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="@cdktf/provider-hashicups.order.Order.property.provisioners"></a>

```go
func Provisioners() *[]interface{}
```

- *Type:* *[]interface{}

---

##### `Items`<sup>Required</sup> <a name="Items" id="@cdktf/provider-hashicups.order.Order.property.items"></a>

```go
func Items() OrderItemsList
```

- *Type:* <a href="#@cdktf/provider-hashicups.order.OrderItemsList">OrderItemsList</a>

---

##### `IdInput`<sup>Optional</sup> <a name="IdInput" id="@cdktf/provider-hashicups.order.Order.property.idInput"></a>

```go
func IdInput() *string
```

- *Type:* *string

---

##### `ItemsInput`<sup>Optional</sup> <a name="ItemsInput" id="@cdktf/provider-hashicups.order.Order.property.itemsInput"></a>

```go
func ItemsInput() interface{}
```

- *Type:* interface{}

---

##### `LastUpdatedInput`<sup>Optional</sup> <a name="LastUpdatedInput" id="@cdktf/provider-hashicups.order.Order.property.lastUpdatedInput"></a>

```go
func LastUpdatedInput() *string
```

- *Type:* *string

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktf/provider-hashicups.order.Order.property.id"></a>

```go
func Id() *string
```

- *Type:* *string

---

##### `LastUpdated`<sup>Required</sup> <a name="LastUpdated" id="@cdktf/provider-hashicups.order.Order.property.lastUpdated"></a>

```go
func LastUpdated() *string
```

- *Type:* *string

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.order.Order.property.tfResourceType">TfResourceType</a></code> | <code>*string</code> | *No description.* |

---

##### `TfResourceType`<sup>Required</sup> <a name="TfResourceType" id="@cdktf/provider-hashicups.order.Order.property.tfResourceType"></a>

```go
func TfResourceType() *string
```

- *Type:* *string

---

## Structs <a name="Structs" id="Structs"></a>

### OrderConfig <a name="OrderConfig" id="@cdktf/provider-hashicups.order.OrderConfig"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-hashicups.order.OrderConfig.Initializer"></a>

```go
import "github.com/cdktf/cdktf-provider-hashicups-go/hashicups/order"

&order.OrderConfig {
	Connection: interface{},
	Count: *f64,
	DependsOn: *[]github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformDependable,
	ForEach: github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator,
	Lifecycle: github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle,
	Provider: github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider,
	Provisioners: *[]interface{},
	Items: interface{},
	Id: *string,
	LastUpdated: *string,
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.order.OrderConfig.property.connection">Connection</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.OrderConfig.property.count">Count</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.OrderConfig.property.dependsOn">DependsOn</a></code> | <code>*[]github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformDependable</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.OrderConfig.property.forEach">ForEach</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.OrderConfig.property.lifecycle">Lifecycle</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.OrderConfig.property.provider">Provider</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.OrderConfig.property.provisioners">Provisioners</a></code> | <code>*[]interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.OrderConfig.property.items">Items</a></code> | <code>interface{}</code> | items block. |
| <code><a href="#@cdktf/provider-hashicups.order.OrderConfig.property.id">Id</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/hashicups/r/order#id Order#id}. |
| <code><a href="#@cdktf/provider-hashicups.order.OrderConfig.property.lastUpdated">LastUpdated</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/hashicups/r/order#last_updated Order#last_updated}. |

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="@cdktf/provider-hashicups.order.OrderConfig.property.connection"></a>

```go
Connection interface{}
```

- *Type:* interface{}

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktf/provider-hashicups.order.OrderConfig.property.count"></a>

```go
Count *f64
```

- *Type:* *f64

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktf/provider-hashicups.order.OrderConfig.property.dependsOn"></a>

```go
DependsOn *[]ITerraformDependable
```

- *Type:* *[]github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformDependable

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktf/provider-hashicups.order.OrderConfig.property.forEach"></a>

```go
ForEach ITerraformIterator
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktf/provider-hashicups.order.OrderConfig.property.lifecycle"></a>

```go
Lifecycle TerraformResourceLifecycle
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktf/provider-hashicups.order.OrderConfig.property.provider"></a>

```go
Provider TerraformProvider
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="@cdktf/provider-hashicups.order.OrderConfig.property.provisioners"></a>

```go
Provisioners *[]interface{}
```

- *Type:* *[]interface{}

---

##### `Items`<sup>Required</sup> <a name="Items" id="@cdktf/provider-hashicups.order.OrderConfig.property.items"></a>

```go
Items interface{}
```

- *Type:* interface{}

items block.

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/hashicups/r/order#items Order#items}

---

##### `Id`<sup>Optional</sup> <a name="Id" id="@cdktf/provider-hashicups.order.OrderConfig.property.id"></a>

```go
Id *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/hashicups/r/order#id Order#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `LastUpdated`<sup>Optional</sup> <a name="LastUpdated" id="@cdktf/provider-hashicups.order.OrderConfig.property.lastUpdated"></a>

```go
LastUpdated *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/hashicups/r/order#last_updated Order#last_updated}.

---

### OrderItems <a name="OrderItems" id="@cdktf/provider-hashicups.order.OrderItems"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-hashicups.order.OrderItems.Initializer"></a>

```go
import "github.com/cdktf/cdktf-provider-hashicups-go/hashicups/order"

&order.OrderItems {
	Coffee: github.com/cdktf/cdktf-provider-hashicups-go/hashicups.order.OrderItemsCoffee,
	Quantity: *f64,
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItems.property.coffee">Coffee</a></code> | <code><a href="#@cdktf/provider-hashicups.order.OrderItemsCoffee">OrderItemsCoffee</a></code> | coffee block. |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItems.property.quantity">Quantity</a></code> | <code>*f64</code> | Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/hashicups/r/order#quantity Order#quantity}. |

---

##### `Coffee`<sup>Required</sup> <a name="Coffee" id="@cdktf/provider-hashicups.order.OrderItems.property.coffee"></a>

```go
Coffee OrderItemsCoffee
```

- *Type:* <a href="#@cdktf/provider-hashicups.order.OrderItemsCoffee">OrderItemsCoffee</a>

coffee block.

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/hashicups/r/order#coffee Order#coffee}

---

##### `Quantity`<sup>Required</sup> <a name="Quantity" id="@cdktf/provider-hashicups.order.OrderItems.property.quantity"></a>

```go
Quantity *f64
```

- *Type:* *f64

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/hashicups/r/order#quantity Order#quantity}.

---

### OrderItemsCoffee <a name="OrderItemsCoffee" id="@cdktf/provider-hashicups.order.OrderItemsCoffee"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-hashicups.order.OrderItemsCoffee.Initializer"></a>

```go
import "github.com/cdktf/cdktf-provider-hashicups-go/hashicups/order"

&order.OrderItemsCoffee {
	Id: *f64,
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsCoffee.property.id">Id</a></code> | <code>*f64</code> | Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/hashicups/r/order#id Order#id}. |

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktf/provider-hashicups.order.OrderItemsCoffee.property.id"></a>

```go
Id *f64
```

- *Type:* *f64

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/hashicups/r/order#id Order#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

## Classes <a name="Classes" id="Classes"></a>

### OrderItemsCoffeeOutputReference <a name="OrderItemsCoffeeOutputReference" id="@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.Initializer"></a>

```go
import "github.com/cdktf/cdktf-provider-hashicups-go/hashicups/order"

order.NewOrderItemsCoffeeOutputReference(terraformResource IInterpolatingParent, terraformAttribute *string) OrderItemsCoffeeOutputReference
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(property *string) IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* *string

---

##### `Resolve` <a name="Resolve" id="@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.property.description">Description</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.property.image">Image</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.property.name">Name</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.property.price">Price</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.property.teaser">Teaser</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.property.idInput">IdInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.property.id">Id</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.property.internalValue">InternalValue</a></code> | <code><a href="#@cdktf/provider-hashicups.order.OrderItemsCoffee">OrderItemsCoffee</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `Description`<sup>Required</sup> <a name="Description" id="@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.property.description"></a>

```go
func Description() *string
```

- *Type:* *string

---

##### `Image`<sup>Required</sup> <a name="Image" id="@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.property.image"></a>

```go
func Image() *string
```

- *Type:* *string

---

##### `Name`<sup>Required</sup> <a name="Name" id="@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.property.name"></a>

```go
func Name() *string
```

- *Type:* *string

---

##### `Price`<sup>Required</sup> <a name="Price" id="@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.property.price"></a>

```go
func Price() *f64
```

- *Type:* *f64

---

##### `Teaser`<sup>Required</sup> <a name="Teaser" id="@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.property.teaser"></a>

```go
func Teaser() *string
```

- *Type:* *string

---

##### `IdInput`<sup>Optional</sup> <a name="IdInput" id="@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.property.idInput"></a>

```go
func IdInput() *f64
```

- *Type:* *f64

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.property.id"></a>

```go
func Id() *f64
```

- *Type:* *f64

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference.property.internalValue"></a>

```go
func InternalValue() OrderItemsCoffee
```

- *Type:* <a href="#@cdktf/provider-hashicups.order.OrderItemsCoffee">OrderItemsCoffee</a>

---


### OrderItemsList <a name="OrderItemsList" id="@cdktf/provider-hashicups.order.OrderItemsList"></a>

#### Initializers <a name="Initializers" id="@cdktf/provider-hashicups.order.OrderItemsList.Initializer"></a>

```go
import "github.com/cdktf/cdktf-provider-hashicups-go/hashicups/order"

order.NewOrderItemsList(terraformResource IInterpolatingParent, terraformAttribute *string, wrapsSet *bool) OrderItemsList
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktf/provider-hashicups.order.OrderItemsList.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.order.OrderItemsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="@cdktf/provider-hashicups.order.OrderItemsList.Initializer.parameter.wrapsSet"></a>

- *Type:* *bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsList.get">Get</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktf/provider-hashicups.order.OrderItemsList.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `Resolve` <a name="Resolve" id="@cdktf/provider-hashicups.order.OrderItemsList.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktf/provider-hashicups.order.OrderItemsList.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktf/provider-hashicups.order.OrderItemsList.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="@cdktf/provider-hashicups.order.OrderItemsList.get"></a>

```go
func Get(index *f64) OrderItemsOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="@cdktf/provider-hashicups.order.OrderItemsList.get.parameter.index"></a>

- *Type:* *f64

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsList.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsList.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsList.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktf/provider-hashicups.order.OrderItemsList.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktf/provider-hashicups.order.OrderItemsList.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktf/provider-hashicups.order.OrderItemsList.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---


### OrderItemsOutputReference <a name="OrderItemsOutputReference" id="@cdktf/provider-hashicups.order.OrderItemsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktf/provider-hashicups.order.OrderItemsOutputReference.Initializer"></a>

```go
import "github.com/cdktf/cdktf-provider-hashicups-go/hashicups/order"

order.NewOrderItemsOutputReference(terraformResource IInterpolatingParent, terraformAttribute *string, complexObjectIndex *f64, complexObjectIsFromSet *bool) OrderItemsOutputReference
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>*f64</code> | the index of this item in the list. |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktf/provider-hashicups.order.OrderItemsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.order.OrderItemsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="@cdktf/provider-hashicups.order.OrderItemsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* *f64

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="@cdktf/provider-hashicups.order.OrderItemsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* *bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsOutputReference.putCoffee">PutCoffee</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktf/provider-hashicups.order.OrderItemsOutputReference.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktf/provider-hashicups.order.OrderItemsOutputReference.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.order.OrderItemsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktf/provider-hashicups.order.OrderItemsOutputReference.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.order.OrderItemsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktf/provider-hashicups.order.OrderItemsOutputReference.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.order.OrderItemsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktf/provider-hashicups.order.OrderItemsOutputReference.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.order.OrderItemsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktf/provider-hashicups.order.OrderItemsOutputReference.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.order.OrderItemsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktf/provider-hashicups.order.OrderItemsOutputReference.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.order.OrderItemsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktf/provider-hashicups.order.OrderItemsOutputReference.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.order.OrderItemsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktf/provider-hashicups.order.OrderItemsOutputReference.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.order.OrderItemsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktf/provider-hashicups.order.OrderItemsOutputReference.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-hashicups.order.OrderItemsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktf/provider-hashicups.order.OrderItemsOutputReference.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(property *string) IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktf/provider-hashicups.order.OrderItemsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* *string

---

##### `Resolve` <a name="Resolve" id="@cdktf/provider-hashicups.order.OrderItemsOutputReference.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktf/provider-hashicups.order.OrderItemsOutputReference.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktf/provider-hashicups.order.OrderItemsOutputReference.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `PutCoffee` <a name="PutCoffee" id="@cdktf/provider-hashicups.order.OrderItemsOutputReference.putCoffee"></a>

```go
func PutCoffee(value OrderItemsCoffee)
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktf/provider-hashicups.order.OrderItemsOutputReference.putCoffee.parameter.value"></a>

- *Type:* <a href="#@cdktf/provider-hashicups.order.OrderItemsCoffee">OrderItemsCoffee</a>

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsOutputReference.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsOutputReference.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsOutputReference.property.coffee">Coffee</a></code> | <code><a href="#@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference">OrderItemsCoffeeOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsOutputReference.property.coffeeInput">CoffeeInput</a></code> | <code><a href="#@cdktf/provider-hashicups.order.OrderItemsCoffee">OrderItemsCoffee</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsOutputReference.property.quantityInput">QuantityInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsOutputReference.property.quantity">Quantity</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.order.OrderItemsOutputReference.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktf/provider-hashicups.order.OrderItemsOutputReference.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktf/provider-hashicups.order.OrderItemsOutputReference.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `Coffee`<sup>Required</sup> <a name="Coffee" id="@cdktf/provider-hashicups.order.OrderItemsOutputReference.property.coffee"></a>

```go
func Coffee() OrderItemsCoffeeOutputReference
```

- *Type:* <a href="#@cdktf/provider-hashicups.order.OrderItemsCoffeeOutputReference">OrderItemsCoffeeOutputReference</a>

---

##### `CoffeeInput`<sup>Optional</sup> <a name="CoffeeInput" id="@cdktf/provider-hashicups.order.OrderItemsOutputReference.property.coffeeInput"></a>

```go
func CoffeeInput() OrderItemsCoffee
```

- *Type:* <a href="#@cdktf/provider-hashicups.order.OrderItemsCoffee">OrderItemsCoffee</a>

---

##### `QuantityInput`<sup>Optional</sup> <a name="QuantityInput" id="@cdktf/provider-hashicups.order.OrderItemsOutputReference.property.quantityInput"></a>

```go
func QuantityInput() *f64
```

- *Type:* *f64

---

##### `Quantity`<sup>Required</sup> <a name="Quantity" id="@cdktf/provider-hashicups.order.OrderItemsOutputReference.property.quantity"></a>

```go
func Quantity() *f64
```

- *Type:* *f64

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktf/provider-hashicups.order.OrderItemsOutputReference.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---



