# `dataHashicupsOrder` Submodule <a name="`dataHashicupsOrder` Submodule" id="@cdktf/provider-hashicups.dataHashicupsOrder"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### DataHashicupsOrder <a name="DataHashicupsOrder" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder"></a>

Represents a {@link https://www.terraform.io/docs/providers/hashicups/d/order hashicups_order}.

#### Initializers <a name="Initializers" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.Initializer"></a>

```python
from cdktf_cdktf_provider_hashicups import data_hashicups_order

dataHashicupsOrder.DataHashicupsOrder(
  scope: Construct,
  id: str,
  connection: typing.Union[SSHProvisionerConnection, WinrmProvisionerConnection] = None,
  count: typing.Union[int, float] = None,
  depends_on: typing.List[ITerraformDependable] = None,
  for_each: ITerraformIterator = None,
  lifecycle: TerraformResourceLifecycle = None,
  provider: TerraformProvider = None,
  provisioners: typing.List[typing.Union[FileProvisioner, LocalExecProvisioner, RemoteExecProvisioner]] = None,
  id: typing.Union[int, float]
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.Initializer.parameter.scope">scope</a></code> | <code>constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.Initializer.parameter.id">id</a></code> | <code>str</code> | The scoped construct ID. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.Initializer.parameter.connection">connection</a></code> | <code>typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.Initializer.parameter.count">count</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.Initializer.parameter.dependsOn">depends_on</a></code> | <code>typing.List[cdktf.ITerraformDependable]</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.Initializer.parameter.forEach">for_each</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.Initializer.parameter.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.Initializer.parameter.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.Initializer.parameter.provisioners">provisioners</a></code> | <code>typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.Initializer.parameter.id">id</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/hashicups/d/order#id DataHashicupsOrder#id}. |

---

##### `scope`<sup>Required</sup> <a name="scope" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.Initializer.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.Initializer.parameter.id"></a>

- *Type:* str

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.Initializer.parameter.connection"></a>

- *Type:* typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.Initializer.parameter.count"></a>

- *Type:* typing.Union[int, float]

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.Initializer.parameter.dependsOn"></a>

- *Type:* typing.List[cdktf.ITerraformDependable]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.Initializer.parameter.forEach"></a>

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.Initializer.parameter.lifecycle"></a>

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.Initializer.parameter.provider"></a>

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.Initializer.parameter.provisioners"></a>

- *Type:* typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.Initializer.parameter.id"></a>

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/hashicups/d/order#id DataHashicupsOrder#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.toString">to_string</a></code> | Returns a string representation of this construct. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.addOverride">add_override</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.overrideLogicalId">override_logical_id</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.resetOverrideLogicalId">reset_override_logical_id</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.toMetadata">to_metadata</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.toTerraform">to_terraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |

---

##### `to_string` <a name="to_string" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.toString"></a>

```python
def to_string() -> str
```

Returns a string representation of this construct.

##### `add_override` <a name="add_override" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.addOverride"></a>

```python
def add_override(
  path: str,
  value: typing.Any
) -> None
```

###### `path`<sup>Required</sup> <a name="path" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.addOverride.parameter.path"></a>

- *Type:* str

---

###### `value`<sup>Required</sup> <a name="value" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.addOverride.parameter.value"></a>

- *Type:* typing.Any

---

##### `override_logical_id` <a name="override_logical_id" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.overrideLogicalId"></a>

```python
def override_logical_id(
  new_logical_id: str
) -> None
```

Overrides the auto-generated logical ID with a specific ID.

###### `new_logical_id`<sup>Required</sup> <a name="new_logical_id" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* str

The new logical ID to use for this stack element.

---

##### `reset_override_logical_id` <a name="reset_override_logical_id" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.resetOverrideLogicalId"></a>

```python
def reset_override_logical_id() -> None
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `to_metadata` <a name="to_metadata" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.toMetadata"></a>

```python
def to_metadata() -> typing.Any
```

##### `to_terraform` <a name="to_terraform" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.toTerraform"></a>

```python
def to_terraform() -> typing.Any
```

Adds this resource to the terraform JSON output.

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.isConstruct">is_construct</a></code> | Checks if `x` is a construct. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.isTerraformElement">is_terraform_element</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.isTerraformDataSource">is_terraform_data_source</a></code> | *No description.* |

---

##### `is_construct` <a name="is_construct" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.isConstruct"></a>

```python
from cdktf_cdktf_provider_hashicups import data_hashicups_order

dataHashicupsOrder.DataHashicupsOrder.is_construct(
  x: typing.Any
)
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

- *Type:* typing.Any

Any object.

---

##### `is_terraform_element` <a name="is_terraform_element" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.isTerraformElement"></a>

```python
from cdktf_cdktf_provider_hashicups import data_hashicups_order

dataHashicupsOrder.DataHashicupsOrder.is_terraform_element(
  x: typing.Any
)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.isTerraformElement.parameter.x"></a>

- *Type:* typing.Any

---

##### `is_terraform_data_source` <a name="is_terraform_data_source" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.isTerraformDataSource"></a>

```python
from cdktf_cdktf_provider_hashicups import data_hashicups_order

dataHashicupsOrder.DataHashicupsOrder.is_terraform_data_source(
  x: typing.Any
)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.isTerraformDataSource.parameter.x"></a>

- *Type:* typing.Any

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.node">node</a></code> | <code>constructs.Node</code> | The tree node. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.cdktfStack">cdktf_stack</a></code> | <code>cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.friendlyUniqueId">friendly_unique_id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.terraformMetaArguments">terraform_meta_arguments</a></code> | <code>typing.Mapping[typing.Any]</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.terraformResourceType">terraform_resource_type</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.terraformGeneratorMetadata">terraform_generator_metadata</a></code> | <code>cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.count">count</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.dependsOn">depends_on</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.forEach">for_each</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.items">items</a></code> | <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsList">DataHashicupsOrderItemsList</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.idInput">id_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.id">id</a></code> | <code>typing.Union[int, float]</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.node"></a>

```python
node: Node
```

- *Type:* constructs.Node

The tree node.

---

##### `cdktf_stack`<sup>Required</sup> <a name="cdktf_stack" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.cdktfStack"></a>

```python
cdktf_stack: TerraformStack
```

- *Type:* cdktf.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `friendly_unique_id`<sup>Required</sup> <a name="friendly_unique_id" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.friendlyUniqueId"></a>

```python
friendly_unique_id: str
```

- *Type:* str

---

##### `terraform_meta_arguments`<sup>Required</sup> <a name="terraform_meta_arguments" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.terraformMetaArguments"></a>

```python
terraform_meta_arguments: typing.Mapping[typing.Any]
```

- *Type:* typing.Mapping[typing.Any]

---

##### `terraform_resource_type`<sup>Required</sup> <a name="terraform_resource_type" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.terraformResourceType"></a>

```python
terraform_resource_type: str
```

- *Type:* str

---

##### `terraform_generator_metadata`<sup>Optional</sup> <a name="terraform_generator_metadata" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.terraformGeneratorMetadata"></a>

```python
terraform_generator_metadata: TerraformProviderGeneratorMetadata
```

- *Type:* cdktf.TerraformProviderGeneratorMetadata

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.count"></a>

```python
count: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.dependsOn"></a>

```python
depends_on: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.forEach"></a>

```python
for_each: ITerraformIterator
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.lifecycle"></a>

```python
lifecycle: TerraformResourceLifecycle
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.provider"></a>

```python
provider: TerraformProvider
```

- *Type:* cdktf.TerraformProvider

---

##### `items`<sup>Required</sup> <a name="items" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.items"></a>

```python
items: DataHashicupsOrderItemsList
```

- *Type:* <a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsList">DataHashicupsOrderItemsList</a>

---

##### `id_input`<sup>Optional</sup> <a name="id_input" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.idInput"></a>

```python
id_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.id"></a>

```python
id: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.tfResourceType">tfResourceType</a></code> | <code>str</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrder.property.tfResourceType"></a>

```python
tfResourceType: str
```

- *Type:* str

---

## Structs <a name="Structs" id="Structs"></a>

### DataHashicupsOrderConfig <a name="DataHashicupsOrderConfig" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderConfig"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderConfig.Initializer"></a>

```python
from cdktf_cdktf_provider_hashicups import data_hashicups_order

dataHashicupsOrder.DataHashicupsOrderConfig(
  connection: typing.Union[SSHProvisionerConnection, WinrmProvisionerConnection] = None,
  count: typing.Union[int, float] = None,
  depends_on: typing.List[ITerraformDependable] = None,
  for_each: ITerraformIterator = None,
  lifecycle: TerraformResourceLifecycle = None,
  provider: TerraformProvider = None,
  provisioners: typing.List[typing.Union[FileProvisioner, LocalExecProvisioner, RemoteExecProvisioner]] = None,
  id: typing.Union[int, float]
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderConfig.property.connection">connection</a></code> | <code>typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderConfig.property.count">count</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderConfig.property.dependsOn">depends_on</a></code> | <code>typing.List[cdktf.ITerraformDependable]</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderConfig.property.forEach">for_each</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderConfig.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderConfig.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderConfig.property.provisioners">provisioners</a></code> | <code>typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderConfig.property.id">id</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/hashicups/d/order#id DataHashicupsOrder#id}. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderConfig.property.connection"></a>

```python
connection: typing.Union[SSHProvisionerConnection, WinrmProvisionerConnection]
```

- *Type:* typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderConfig.property.count"></a>

```python
count: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderConfig.property.dependsOn"></a>

```python
depends_on: typing.List[ITerraformDependable]
```

- *Type:* typing.List[cdktf.ITerraformDependable]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderConfig.property.forEach"></a>

```python
for_each: ITerraformIterator
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderConfig.property.lifecycle"></a>

```python
lifecycle: TerraformResourceLifecycle
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderConfig.property.provider"></a>

```python
provider: TerraformProvider
```

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderConfig.property.provisioners"></a>

```python
provisioners: typing.List[typing.Union[FileProvisioner, LocalExecProvisioner, RemoteExecProvisioner]]
```

- *Type:* typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderConfig.property.id"></a>

```python
id: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/hashicups/d/order#id DataHashicupsOrder#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

### DataHashicupsOrderItems <a name="DataHashicupsOrderItems" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItems"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItems.Initializer"></a>

```python
from cdktf_cdktf_provider_hashicups import data_hashicups_order

dataHashicupsOrder.DataHashicupsOrderItems()
```


## Classes <a name="Classes" id="Classes"></a>

### DataHashicupsOrderItemsList <a name="DataHashicupsOrderItemsList" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsList"></a>

#### Initializers <a name="Initializers" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsList.Initializer"></a>

```python
from cdktf_cdktf_provider_hashicups import data_hashicups_order

dataHashicupsOrder.DataHashicupsOrderItemsList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> DataHashicupsOrderItemsOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---


### DataHashicupsOrderItemsOutputReference <a name="DataHashicupsOrderItemsOutputReference" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.Initializer"></a>

```python
from cdktf_cdktf_provider_hashicups import data_hashicups_order

dataHashicupsOrder.DataHashicupsOrderItemsOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |

---

##### `compute_fqn` <a name="compute_fqn" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.property.coffeeDescription">coffee_description</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.property.coffeeId">coffee_id</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.property.coffeeImage">coffee_image</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.property.coffeeName">coffee_name</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.property.coffeePrice">coffee_price</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.property.coffeeTeaser">coffee_teaser</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.property.quantity">quantity</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.property.internalValue">internal_value</a></code> | <code><a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItems">DataHashicupsOrderItems</a></code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `coffee_description`<sup>Required</sup> <a name="coffee_description" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.property.coffeeDescription"></a>

```python
coffee_description: str
```

- *Type:* str

---

##### `coffee_id`<sup>Required</sup> <a name="coffee_id" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.property.coffeeId"></a>

```python
coffee_id: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `coffee_image`<sup>Required</sup> <a name="coffee_image" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.property.coffeeImage"></a>

```python
coffee_image: str
```

- *Type:* str

---

##### `coffee_name`<sup>Required</sup> <a name="coffee_name" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.property.coffeeName"></a>

```python
coffee_name: str
```

- *Type:* str

---

##### `coffee_price`<sup>Required</sup> <a name="coffee_price" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.property.coffeePrice"></a>

```python
coffee_price: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `coffee_teaser`<sup>Required</sup> <a name="coffee_teaser" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.property.coffeeTeaser"></a>

```python
coffee_teaser: str
```

- *Type:* str

---

##### `quantity`<sup>Required</sup> <a name="quantity" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.property.quantity"></a>

```python
quantity: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItemsOutputReference.property.internalValue"></a>

```python
internal_value: DataHashicupsOrderItems
```

- *Type:* <a href="#@cdktf/provider-hashicups.dataHashicupsOrder.DataHashicupsOrderItems">DataHashicupsOrderItems</a>

---



