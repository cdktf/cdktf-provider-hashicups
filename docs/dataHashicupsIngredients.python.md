# `data_hashicups_ingredients`

Refer to the Terraform Registory for docs: [`data_hashicups_ingredients`](https://registry.terraform.io/providers/hashicorp/hashicups/0.3.1/docs/data-sources/ingredients).

# `dataHashicupsIngredients` Submodule <a name="`dataHashicupsIngredients` Submodule" id="@cdktf/provider-hashicups.dataHashicupsIngredients"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### DataHashicupsIngredients <a name="DataHashicupsIngredients" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients"></a>

Represents a {@link https://registry.terraform.io/providers/hashicorp/hashicups/0.3.1/docs/data-sources/ingredients hashicups_ingredients}.

#### Initializers <a name="Initializers" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.Initializer"></a>

```python
from cdktf_cdktf_provider_hashicups import data_hashicups_ingredients

dataHashicupsIngredients.DataHashicupsIngredients(
  scope: Construct,
  id: str,
  connection: typing.Union[SSHProvisionerConnection, WinrmProvisionerConnection] = None,
  count: typing.Union[typing.Union[int, float], TerraformCount] = None,
  depends_on: typing.List[ITerraformDependable] = None,
  for_each: ITerraformIterator = None,
  lifecycle: TerraformResourceLifecycle = None,
  provider: TerraformProvider = None,
  provisioners: typing.List[typing.Union[FileProvisioner, LocalExecProvisioner, RemoteExecProvisioner]] = None,
  coffee_id: typing.Union[int, float],
  id: str = None
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.Initializer.parameter.scope">scope</a></code> | <code>constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.Initializer.parameter.id">id</a></code> | <code>str</code> | The scoped construct ID. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.Initializer.parameter.connection">connection</a></code> | <code>typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.Initializer.parameter.count">count</a></code> | <code>typing.Union[typing.Union[int, float], cdktf.TerraformCount]</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.Initializer.parameter.dependsOn">depends_on</a></code> | <code>typing.List[cdktf.ITerraformDependable]</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.Initializer.parameter.forEach">for_each</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.Initializer.parameter.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.Initializer.parameter.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.Initializer.parameter.provisioners">provisioners</a></code> | <code>typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.Initializer.parameter.coffeeId">coffee_id</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/hashicups/0.3.1/docs/data-sources/ingredients#coffee_id DataHashicupsIngredients#coffee_id}. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.Initializer.parameter.id">id</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/hashicups/0.3.1/docs/data-sources/ingredients#id DataHashicupsIngredients#id}. |

---

##### `scope`<sup>Required</sup> <a name="scope" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.Initializer.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.Initializer.parameter.id"></a>

- *Type:* str

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.Initializer.parameter.connection"></a>

- *Type:* typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.Initializer.parameter.count"></a>

- *Type:* typing.Union[typing.Union[int, float], cdktf.TerraformCount]

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.Initializer.parameter.dependsOn"></a>

- *Type:* typing.List[cdktf.ITerraformDependable]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.Initializer.parameter.forEach"></a>

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.Initializer.parameter.lifecycle"></a>

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.Initializer.parameter.provider"></a>

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.Initializer.parameter.provisioners"></a>

- *Type:* typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]

---

##### `coffee_id`<sup>Required</sup> <a name="coffee_id" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.Initializer.parameter.coffeeId"></a>

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/hashicups/0.3.1/docs/data-sources/ingredients#coffee_id DataHashicupsIngredients#coffee_id}.

---

##### `id`<sup>Optional</sup> <a name="id" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.Initializer.parameter.id"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/hashicups/0.3.1/docs/data-sources/ingredients#id DataHashicupsIngredients#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.toString">to_string</a></code> | Returns a string representation of this construct. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.addOverride">add_override</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.overrideLogicalId">override_logical_id</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.resetOverrideLogicalId">reset_override_logical_id</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.toMetadata">to_metadata</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.toTerraform">to_terraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.resetId">reset_id</a></code> | *No description.* |

---

##### `to_string` <a name="to_string" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.toString"></a>

```python
def to_string() -> str
```

Returns a string representation of this construct.

##### `add_override` <a name="add_override" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.addOverride"></a>

```python
def add_override(
  path: str,
  value: typing.Any
) -> None
```

###### `path`<sup>Required</sup> <a name="path" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.addOverride.parameter.path"></a>

- *Type:* str

---

###### `value`<sup>Required</sup> <a name="value" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.addOverride.parameter.value"></a>

- *Type:* typing.Any

---

##### `override_logical_id` <a name="override_logical_id" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.overrideLogicalId"></a>

```python
def override_logical_id(
  new_logical_id: str
) -> None
```

Overrides the auto-generated logical ID with a specific ID.

###### `new_logical_id`<sup>Required</sup> <a name="new_logical_id" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* str

The new logical ID to use for this stack element.

---

##### `reset_override_logical_id` <a name="reset_override_logical_id" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.resetOverrideLogicalId"></a>

```python
def reset_override_logical_id() -> None
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `to_metadata` <a name="to_metadata" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.toMetadata"></a>

```python
def to_metadata() -> typing.Any
```

##### `to_terraform` <a name="to_terraform" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.toTerraform"></a>

```python
def to_terraform() -> typing.Any
```

Adds this resource to the terraform JSON output.

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `reset_id` <a name="reset_id" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.resetId"></a>

```python
def reset_id() -> None
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.isConstruct">is_construct</a></code> | Checks if `x` is a construct. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.isTerraformElement">is_terraform_element</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.isTerraformDataSource">is_terraform_data_source</a></code> | *No description.* |

---

##### `is_construct` <a name="is_construct" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.isConstruct"></a>

```python
from cdktf_cdktf_provider_hashicups import data_hashicups_ingredients

dataHashicupsIngredients.DataHashicupsIngredients.is_construct(
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

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.isConstruct.parameter.x"></a>

- *Type:* typing.Any

Any object.

---

##### `is_terraform_element` <a name="is_terraform_element" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.isTerraformElement"></a>

```python
from cdktf_cdktf_provider_hashicups import data_hashicups_ingredients

dataHashicupsIngredients.DataHashicupsIngredients.is_terraform_element(
  x: typing.Any
)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.isTerraformElement.parameter.x"></a>

- *Type:* typing.Any

---

##### `is_terraform_data_source` <a name="is_terraform_data_source" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.isTerraformDataSource"></a>

```python
from cdktf_cdktf_provider_hashicups import data_hashicups_ingredients

dataHashicupsIngredients.DataHashicupsIngredients.is_terraform_data_source(
  x: typing.Any
)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.isTerraformDataSource.parameter.x"></a>

- *Type:* typing.Any

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.node">node</a></code> | <code>constructs.Node</code> | The tree node. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.cdktfStack">cdktf_stack</a></code> | <code>cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.friendlyUniqueId">friendly_unique_id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.terraformMetaArguments">terraform_meta_arguments</a></code> | <code>typing.Mapping[typing.Any]</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.terraformResourceType">terraform_resource_type</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.terraformGeneratorMetadata">terraform_generator_metadata</a></code> | <code>cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.count">count</a></code> | <code>typing.Union[typing.Union[int, float], cdktf.TerraformCount]</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.dependsOn">depends_on</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.forEach">for_each</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.ingredients">ingredients</a></code> | <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList">DataHashicupsIngredientsIngredientsList</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.coffeeIdInput">coffee_id_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.idInput">id_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.coffeeId">coffee_id</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.id">id</a></code> | <code>str</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.node"></a>

```python
node: Node
```

- *Type:* constructs.Node

The tree node.

---

##### `cdktf_stack`<sup>Required</sup> <a name="cdktf_stack" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.cdktfStack"></a>

```python
cdktf_stack: TerraformStack
```

- *Type:* cdktf.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `friendly_unique_id`<sup>Required</sup> <a name="friendly_unique_id" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.friendlyUniqueId"></a>

```python
friendly_unique_id: str
```

- *Type:* str

---

##### `terraform_meta_arguments`<sup>Required</sup> <a name="terraform_meta_arguments" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.terraformMetaArguments"></a>

```python
terraform_meta_arguments: typing.Mapping[typing.Any]
```

- *Type:* typing.Mapping[typing.Any]

---

##### `terraform_resource_type`<sup>Required</sup> <a name="terraform_resource_type" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.terraformResourceType"></a>

```python
terraform_resource_type: str
```

- *Type:* str

---

##### `terraform_generator_metadata`<sup>Optional</sup> <a name="terraform_generator_metadata" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.terraformGeneratorMetadata"></a>

```python
terraform_generator_metadata: TerraformProviderGeneratorMetadata
```

- *Type:* cdktf.TerraformProviderGeneratorMetadata

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.count"></a>

```python
count: typing.Union[typing.Union[int, float], TerraformCount]
```

- *Type:* typing.Union[typing.Union[int, float], cdktf.TerraformCount]

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.dependsOn"></a>

```python
depends_on: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.forEach"></a>

```python
for_each: ITerraformIterator
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.lifecycle"></a>

```python
lifecycle: TerraformResourceLifecycle
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.provider"></a>

```python
provider: TerraformProvider
```

- *Type:* cdktf.TerraformProvider

---

##### `ingredients`<sup>Required</sup> <a name="ingredients" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.ingredients"></a>

```python
ingredients: DataHashicupsIngredientsIngredientsList
```

- *Type:* <a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList">DataHashicupsIngredientsIngredientsList</a>

---

##### `coffee_id_input`<sup>Optional</sup> <a name="coffee_id_input" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.coffeeIdInput"></a>

```python
coffee_id_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `id_input`<sup>Optional</sup> <a name="id_input" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.idInput"></a>

```python
id_input: str
```

- *Type:* str

---

##### `coffee_id`<sup>Required</sup> <a name="coffee_id" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.coffeeId"></a>

```python
coffee_id: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.id"></a>

```python
id: str
```

- *Type:* str

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.tfResourceType">tfResourceType</a></code> | <code>str</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredients.property.tfResourceType"></a>

```python
tfResourceType: str
```

- *Type:* str

---

## Structs <a name="Structs" id="Structs"></a>

### DataHashicupsIngredientsConfig <a name="DataHashicupsIngredientsConfig" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.Initializer"></a>

```python
from cdktf_cdktf_provider_hashicups import data_hashicups_ingredients

dataHashicupsIngredients.DataHashicupsIngredientsConfig(
  connection: typing.Union[SSHProvisionerConnection, WinrmProvisionerConnection] = None,
  count: typing.Union[typing.Union[int, float], TerraformCount] = None,
  depends_on: typing.List[ITerraformDependable] = None,
  for_each: ITerraformIterator = None,
  lifecycle: TerraformResourceLifecycle = None,
  provider: TerraformProvider = None,
  provisioners: typing.List[typing.Union[FileProvisioner, LocalExecProvisioner, RemoteExecProvisioner]] = None,
  coffee_id: typing.Union[int, float],
  id: str = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.connection">connection</a></code> | <code>typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.count">count</a></code> | <code>typing.Union[typing.Union[int, float], cdktf.TerraformCount]</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.dependsOn">depends_on</a></code> | <code>typing.List[cdktf.ITerraformDependable]</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.forEach">for_each</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.provisioners">provisioners</a></code> | <code>typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.coffeeId">coffee_id</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/hashicups/0.3.1/docs/data-sources/ingredients#coffee_id DataHashicupsIngredients#coffee_id}. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.id">id</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/hashicups/0.3.1/docs/data-sources/ingredients#id DataHashicupsIngredients#id}. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.connection"></a>

```python
connection: typing.Union[SSHProvisionerConnection, WinrmProvisionerConnection]
```

- *Type:* typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.count"></a>

```python
count: typing.Union[typing.Union[int, float], TerraformCount]
```

- *Type:* typing.Union[typing.Union[int, float], cdktf.TerraformCount]

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.dependsOn"></a>

```python
depends_on: typing.List[ITerraformDependable]
```

- *Type:* typing.List[cdktf.ITerraformDependable]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.forEach"></a>

```python
for_each: ITerraformIterator
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.lifecycle"></a>

```python
lifecycle: TerraformResourceLifecycle
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.provider"></a>

```python
provider: TerraformProvider
```

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.provisioners"></a>

```python
provisioners: typing.List[typing.Union[FileProvisioner, LocalExecProvisioner, RemoteExecProvisioner]]
```

- *Type:* typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]

---

##### `coffee_id`<sup>Required</sup> <a name="coffee_id" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.coffeeId"></a>

```python
coffee_id: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/hashicups/0.3.1/docs/data-sources/ingredients#coffee_id DataHashicupsIngredients#coffee_id}.

---

##### `id`<sup>Optional</sup> <a name="id" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsConfig.property.id"></a>

```python
id: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/hashicups/0.3.1/docs/data-sources/ingredients#id DataHashicupsIngredients#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

### DataHashicupsIngredientsIngredients <a name="DataHashicupsIngredientsIngredients" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredients"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredients.Initializer"></a>

```python
from cdktf_cdktf_provider_hashicups import data_hashicups_ingredients

dataHashicupsIngredients.DataHashicupsIngredientsIngredients()
```


## Classes <a name="Classes" id="Classes"></a>

### DataHashicupsIngredientsIngredientsList <a name="DataHashicupsIngredientsIngredientsList" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList"></a>

#### Initializers <a name="Initializers" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.Initializer"></a>

```python
from cdktf_cdktf_provider_hashicups import data_hashicups_ingredients

dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> DataHashicupsIngredientsIngredientsOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---


### DataHashicupsIngredientsIngredientsOutputReference <a name="DataHashicupsIngredientsIngredientsOutputReference" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.Initializer"></a>

```python
from cdktf_cdktf_provider_hashicups import data_hashicups_ingredients

dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |

---

##### `compute_fqn` <a name="compute_fqn" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.id">id</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.name">name</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.quantity">quantity</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.unit">unit</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.internalValue">internal_value</a></code> | <code><a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredients">DataHashicupsIngredientsIngredients</a></code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.id"></a>

```python
id: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `name`<sup>Required</sup> <a name="name" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.name"></a>

```python
name: str
```

- *Type:* str

---

##### `quantity`<sup>Required</sup> <a name="quantity" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.quantity"></a>

```python
quantity: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `unit`<sup>Required</sup> <a name="unit" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.unit"></a>

```python
unit: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredientsOutputReference.property.internalValue"></a>

```python
internal_value: DataHashicupsIngredientsIngredients
```

- *Type:* <a href="#@cdktf/provider-hashicups.dataHashicupsIngredients.DataHashicupsIngredientsIngredients">DataHashicupsIngredientsIngredients</a>

---



