# `provider` Submodule <a name="`provider` Submodule" id="@cdktf/provider-hashicups.provider"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### HashicupsProvider <a name="HashicupsProvider" id="@cdktf/provider-hashicups.provider.HashicupsProvider"></a>

Represents a {@link https://www.terraform.io/docs/providers/hashicups hashicups}.

#### Initializers <a name="Initializers" id="@cdktf/provider-hashicups.provider.HashicupsProvider.Initializer"></a>

```python
from cdktf_cdktf_provider_hashicups import provider

provider.HashicupsProvider(
  scope: Construct,
  id: str,
  alias: str = None,
  host: str = None,
  password: str = None,
  username: str = None
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.provider.HashicupsProvider.Initializer.parameter.scope">scope</a></code> | <code>constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktf/provider-hashicups.provider.HashicupsProvider.Initializer.parameter.id">id</a></code> | <code>str</code> | The scoped construct ID. |
| <code><a href="#@cdktf/provider-hashicups.provider.HashicupsProvider.Initializer.parameter.alias">alias</a></code> | <code>str</code> | Alias name. |
| <code><a href="#@cdktf/provider-hashicups.provider.HashicupsProvider.Initializer.parameter.host">host</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/hashicups#host HashicupsProvider#host}. |
| <code><a href="#@cdktf/provider-hashicups.provider.HashicupsProvider.Initializer.parameter.password">password</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/hashicups#password HashicupsProvider#password}. |
| <code><a href="#@cdktf/provider-hashicups.provider.HashicupsProvider.Initializer.parameter.username">username</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/hashicups#username HashicupsProvider#username}. |

---

##### `scope`<sup>Required</sup> <a name="scope" id="@cdktf/provider-hashicups.provider.HashicupsProvider.Initializer.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-hashicups.provider.HashicupsProvider.Initializer.parameter.id"></a>

- *Type:* str

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `alias`<sup>Optional</sup> <a name="alias" id="@cdktf/provider-hashicups.provider.HashicupsProvider.Initializer.parameter.alias"></a>

- *Type:* str

Alias name.

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/hashicups#alias HashicupsProvider#alias}

---

##### `host`<sup>Optional</sup> <a name="host" id="@cdktf/provider-hashicups.provider.HashicupsProvider.Initializer.parameter.host"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/hashicups#host HashicupsProvider#host}.

---

##### `password`<sup>Optional</sup> <a name="password" id="@cdktf/provider-hashicups.provider.HashicupsProvider.Initializer.parameter.password"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/hashicups#password HashicupsProvider#password}.

---

##### `username`<sup>Optional</sup> <a name="username" id="@cdktf/provider-hashicups.provider.HashicupsProvider.Initializer.parameter.username"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/hashicups#username HashicupsProvider#username}.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-hashicups.provider.HashicupsProvider.toString">to_string</a></code> | Returns a string representation of this construct. |
| <code><a href="#@cdktf/provider-hashicups.provider.HashicupsProvider.addOverride">add_override</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.provider.HashicupsProvider.overrideLogicalId">override_logical_id</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#@cdktf/provider-hashicups.provider.HashicupsProvider.resetOverrideLogicalId">reset_override_logical_id</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#@cdktf/provider-hashicups.provider.HashicupsProvider.toMetadata">to_metadata</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.provider.HashicupsProvider.toTerraform">to_terraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktf/provider-hashicups.provider.HashicupsProvider.resetAlias">reset_alias</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.provider.HashicupsProvider.resetHost">reset_host</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.provider.HashicupsProvider.resetPassword">reset_password</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.provider.HashicupsProvider.resetUsername">reset_username</a></code> | *No description.* |

---

##### `to_string` <a name="to_string" id="@cdktf/provider-hashicups.provider.HashicupsProvider.toString"></a>

```python
def to_string() -> str
```

Returns a string representation of this construct.

##### `add_override` <a name="add_override" id="@cdktf/provider-hashicups.provider.HashicupsProvider.addOverride"></a>

```python
def add_override(
  path: str,
  value: typing.Any
) -> None
```

###### `path`<sup>Required</sup> <a name="path" id="@cdktf/provider-hashicups.provider.HashicupsProvider.addOverride.parameter.path"></a>

- *Type:* str

---

###### `value`<sup>Required</sup> <a name="value" id="@cdktf/provider-hashicups.provider.HashicupsProvider.addOverride.parameter.value"></a>

- *Type:* typing.Any

---

##### `override_logical_id` <a name="override_logical_id" id="@cdktf/provider-hashicups.provider.HashicupsProvider.overrideLogicalId"></a>

```python
def override_logical_id(
  new_logical_id: str
) -> None
```

Overrides the auto-generated logical ID with a specific ID.

###### `new_logical_id`<sup>Required</sup> <a name="new_logical_id" id="@cdktf/provider-hashicups.provider.HashicupsProvider.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* str

The new logical ID to use for this stack element.

---

##### `reset_override_logical_id` <a name="reset_override_logical_id" id="@cdktf/provider-hashicups.provider.HashicupsProvider.resetOverrideLogicalId"></a>

```python
def reset_override_logical_id() -> None
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `to_metadata` <a name="to_metadata" id="@cdktf/provider-hashicups.provider.HashicupsProvider.toMetadata"></a>

```python
def to_metadata() -> typing.Any
```

##### `to_terraform` <a name="to_terraform" id="@cdktf/provider-hashicups.provider.HashicupsProvider.toTerraform"></a>

```python
def to_terraform() -> typing.Any
```

Adds this resource to the terraform JSON output.

##### `reset_alias` <a name="reset_alias" id="@cdktf/provider-hashicups.provider.HashicupsProvider.resetAlias"></a>

```python
def reset_alias() -> None
```

##### `reset_host` <a name="reset_host" id="@cdktf/provider-hashicups.provider.HashicupsProvider.resetHost"></a>

```python
def reset_host() -> None
```

##### `reset_password` <a name="reset_password" id="@cdktf/provider-hashicups.provider.HashicupsProvider.resetPassword"></a>

```python
def reset_password() -> None
```

##### `reset_username` <a name="reset_username" id="@cdktf/provider-hashicups.provider.HashicupsProvider.resetUsername"></a>

```python
def reset_username() -> None
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-hashicups.provider.HashicupsProvider.isConstruct">is_construct</a></code> | Checks if `x` is a construct. |
| <code><a href="#@cdktf/provider-hashicups.provider.HashicupsProvider.isTerraformElement">is_terraform_element</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.provider.HashicupsProvider.isTerraformProvider">is_terraform_provider</a></code> | *No description.* |

---

##### `is_construct` <a name="is_construct" id="@cdktf/provider-hashicups.provider.HashicupsProvider.isConstruct"></a>

```python
from cdktf_cdktf_provider_hashicups import provider

provider.HashicupsProvider.is_construct(
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

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-hashicups.provider.HashicupsProvider.isConstruct.parameter.x"></a>

- *Type:* typing.Any

Any object.

---

##### `is_terraform_element` <a name="is_terraform_element" id="@cdktf/provider-hashicups.provider.HashicupsProvider.isTerraformElement"></a>

```python
from cdktf_cdktf_provider_hashicups import provider

provider.HashicupsProvider.is_terraform_element(
  x: typing.Any
)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-hashicups.provider.HashicupsProvider.isTerraformElement.parameter.x"></a>

- *Type:* typing.Any

---

##### `is_terraform_provider` <a name="is_terraform_provider" id="@cdktf/provider-hashicups.provider.HashicupsProvider.isTerraformProvider"></a>

```python
from cdktf_cdktf_provider_hashicups import provider

provider.HashicupsProvider.is_terraform_provider(
  x: typing.Any
)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-hashicups.provider.HashicupsProvider.isTerraformProvider.parameter.x"></a>

- *Type:* typing.Any

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.provider.HashicupsProvider.property.node">node</a></code> | <code>constructs.Node</code> | The tree node. |
| <code><a href="#@cdktf/provider-hashicups.provider.HashicupsProvider.property.cdktfStack">cdktf_stack</a></code> | <code>cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.provider.HashicupsProvider.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.provider.HashicupsProvider.property.friendlyUniqueId">friendly_unique_id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.provider.HashicupsProvider.property.metaAttributes">meta_attributes</a></code> | <code>typing.Mapping[typing.Any]</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.provider.HashicupsProvider.property.terraformResourceType">terraform_resource_type</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.provider.HashicupsProvider.property.terraformGeneratorMetadata">terraform_generator_metadata</a></code> | <code>cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.provider.HashicupsProvider.property.terraformProviderSource">terraform_provider_source</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.provider.HashicupsProvider.property.alias">alias</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.provider.HashicupsProvider.property.aliasInput">alias_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.provider.HashicupsProvider.property.hostInput">host_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.provider.HashicupsProvider.property.passwordInput">password_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.provider.HashicupsProvider.property.usernameInput">username_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.provider.HashicupsProvider.property.host">host</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.provider.HashicupsProvider.property.password">password</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-hashicups.provider.HashicupsProvider.property.username">username</a></code> | <code>str</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="@cdktf/provider-hashicups.provider.HashicupsProvider.property.node"></a>

```python
node: Node
```

- *Type:* constructs.Node

The tree node.

---

##### `cdktf_stack`<sup>Required</sup> <a name="cdktf_stack" id="@cdktf/provider-hashicups.provider.HashicupsProvider.property.cdktfStack"></a>

```python
cdktf_stack: TerraformStack
```

- *Type:* cdktf.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktf/provider-hashicups.provider.HashicupsProvider.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `friendly_unique_id`<sup>Required</sup> <a name="friendly_unique_id" id="@cdktf/provider-hashicups.provider.HashicupsProvider.property.friendlyUniqueId"></a>

```python
friendly_unique_id: str
```

- *Type:* str

---

##### `meta_attributes`<sup>Required</sup> <a name="meta_attributes" id="@cdktf/provider-hashicups.provider.HashicupsProvider.property.metaAttributes"></a>

```python
meta_attributes: typing.Mapping[typing.Any]
```

- *Type:* typing.Mapping[typing.Any]

---

##### `terraform_resource_type`<sup>Required</sup> <a name="terraform_resource_type" id="@cdktf/provider-hashicups.provider.HashicupsProvider.property.terraformResourceType"></a>

```python
terraform_resource_type: str
```

- *Type:* str

---

##### `terraform_generator_metadata`<sup>Optional</sup> <a name="terraform_generator_metadata" id="@cdktf/provider-hashicups.provider.HashicupsProvider.property.terraformGeneratorMetadata"></a>

```python
terraform_generator_metadata: TerraformProviderGeneratorMetadata
```

- *Type:* cdktf.TerraformProviderGeneratorMetadata

---

##### `terraform_provider_source`<sup>Optional</sup> <a name="terraform_provider_source" id="@cdktf/provider-hashicups.provider.HashicupsProvider.property.terraformProviderSource"></a>

```python
terraform_provider_source: str
```

- *Type:* str

---

##### `alias`<sup>Optional</sup> <a name="alias" id="@cdktf/provider-hashicups.provider.HashicupsProvider.property.alias"></a>

```python
alias: str
```

- *Type:* str

---

##### `alias_input`<sup>Optional</sup> <a name="alias_input" id="@cdktf/provider-hashicups.provider.HashicupsProvider.property.aliasInput"></a>

```python
alias_input: str
```

- *Type:* str

---

##### `host_input`<sup>Optional</sup> <a name="host_input" id="@cdktf/provider-hashicups.provider.HashicupsProvider.property.hostInput"></a>

```python
host_input: str
```

- *Type:* str

---

##### `password_input`<sup>Optional</sup> <a name="password_input" id="@cdktf/provider-hashicups.provider.HashicupsProvider.property.passwordInput"></a>

```python
password_input: str
```

- *Type:* str

---

##### `username_input`<sup>Optional</sup> <a name="username_input" id="@cdktf/provider-hashicups.provider.HashicupsProvider.property.usernameInput"></a>

```python
username_input: str
```

- *Type:* str

---

##### `host`<sup>Optional</sup> <a name="host" id="@cdktf/provider-hashicups.provider.HashicupsProvider.property.host"></a>

```python
host: str
```

- *Type:* str

---

##### `password`<sup>Optional</sup> <a name="password" id="@cdktf/provider-hashicups.provider.HashicupsProvider.property.password"></a>

```python
password: str
```

- *Type:* str

---

##### `username`<sup>Optional</sup> <a name="username" id="@cdktf/provider-hashicups.provider.HashicupsProvider.property.username"></a>

```python
username: str
```

- *Type:* str

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.provider.HashicupsProvider.property.tfResourceType">tfResourceType</a></code> | <code>str</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="@cdktf/provider-hashicups.provider.HashicupsProvider.property.tfResourceType"></a>

```python
tfResourceType: str
```

- *Type:* str

---

## Structs <a name="Structs" id="Structs"></a>

### HashicupsProviderConfig <a name="HashicupsProviderConfig" id="@cdktf/provider-hashicups.provider.HashicupsProviderConfig"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-hashicups.provider.HashicupsProviderConfig.Initializer"></a>

```python
from cdktf_cdktf_provider_hashicups import provider

provider.HashicupsProviderConfig(
  alias: str = None,
  host: str = None,
  password: str = None,
  username: str = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-hashicups.provider.HashicupsProviderConfig.property.alias">alias</a></code> | <code>str</code> | Alias name. |
| <code><a href="#@cdktf/provider-hashicups.provider.HashicupsProviderConfig.property.host">host</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/hashicups#host HashicupsProvider#host}. |
| <code><a href="#@cdktf/provider-hashicups.provider.HashicupsProviderConfig.property.password">password</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/hashicups#password HashicupsProvider#password}. |
| <code><a href="#@cdktf/provider-hashicups.provider.HashicupsProviderConfig.property.username">username</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/hashicups#username HashicupsProvider#username}. |

---

##### `alias`<sup>Optional</sup> <a name="alias" id="@cdktf/provider-hashicups.provider.HashicupsProviderConfig.property.alias"></a>

```python
alias: str
```

- *Type:* str

Alias name.

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/hashicups#alias HashicupsProvider#alias}

---

##### `host`<sup>Optional</sup> <a name="host" id="@cdktf/provider-hashicups.provider.HashicupsProviderConfig.property.host"></a>

```python
host: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/hashicups#host HashicupsProvider#host}.

---

##### `password`<sup>Optional</sup> <a name="password" id="@cdktf/provider-hashicups.provider.HashicupsProviderConfig.property.password"></a>

```python
password: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/hashicups#password HashicupsProvider#password}.

---

##### `username`<sup>Optional</sup> <a name="username" id="@cdktf/provider-hashicups.provider.HashicupsProviderConfig.property.username"></a>

```python
username: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/hashicups#username HashicupsProvider#username}.

---



