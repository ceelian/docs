---
title: "Module Entitlement"
title_tag: "Module Entitlement | Package @pulumi/azuredevops | Node.js SDK"
linktitle: "Entitlement"
meta_desc: "Explore members of the Entitlement module in the @pulumi/azuredevops package."
git_sha: "f8413512df804b703ebdd0da23b385c99bbe4500"
block_external_search_index: true
---

<!-- WARNING: this page was generated by a tool. Do not edit it by hand. -->
<!-- To change it, please see https://github.com/pulumi/docs/tree/master/tools/tscdocgen. -->

{{< resource-docs-alert "azuredevops" >}}




<h3>Resources</h3>
<ul class="api">
    <li><a href="#User"><span class="symbol resource"></span>User</a></li>
</ul>


<h3>Others</h3>
<ul class="api">
    <li><a href="#UserArgs"><span class="symbol api"></span>UserArgs</a></li>
    <li><a href="#UserState"><span class="symbol api"></span>UserState</a></li>
</ul>


<h2 id="resources">Resources</h2>
<h3 class="pdoc-module-header" id="User" data-link-title="User">
    <a href="https://github.com/pulumi/pulumi-azuredevops/blob/f8413512df804b703ebdd0da23b385c99bbe4500/sdk/nodejs/Entitlement/user.ts#L31">
        Resource <strong>User</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kr'>class</span> <span class='nx'>User</span> <span class='kr'>extends</span> <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResource'>CustomResource</a></code></pre>

Manages a user entitlement within Azure DevOps.

#### Example Usage



```typescript
import * as pulumi from "@pulumi/pulumi";
import * as azuredevops from "@pulumi/azuredevops";

const user = new azuredevops.Entitlement.User("user", {
    principalName: "foo@contoso.com",
});
```

#### Relevant Links

* [Azure DevOps Service REST API 5.1 - User Entitlements - Add](https://docs.microsoft.com/en-us/rest/api/azure/devops/memberentitlementmanagement/user%20entitlements/add?view=azure-devops-rest-5.1)

#### PAT Permissions Required

- **Member Entitlement Management**: Read & Write

<h4 class="pdoc-member-header" id="User-constructor">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azuredevops/blob/f8413512df804b703ebdd0da23b385c99bbe4500/sdk/nodejs/Entitlement/user.ts#L82"> <b>constructor</b></a>
</h4>


<pre class="highlight"><code><span class='kd'></span><span class='kd'>new</span> User(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, args?: <a href='#UserArgs'>UserArgs</a>, opts?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>)</code></pre>


Create a User resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h4 class="pdoc-member-header" id="User-get">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azuredevops/blob/f8413512df804b703ebdd0da23b385c99bbe4500/sdk/nodejs/Entitlement/user.ts#L41">method <b>get</b></a>
</h4>


<pre class="highlight"><code><span class='kd'>public static </span>get(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, id: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#ID'>pulumi.ID</a>&gt;, state?: <a href='#UserState'>UserState</a>, opts?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>): <a href='#User'>User</a></code></pre>


Get an existing User resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h4 class="pdoc-member-header" id="User-getProvider">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azuredevops/blob/f8413512df804b703ebdd0da23b385c99bbe4500/sdk/nodejs/Entitlement/user.ts#L31">method <b>getProvider</b></a>
</h4>


<pre class="highlight"><code><span class='kd'></span>getProvider(moduleMember: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>): <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#ProviderResource'>ProviderResource</a> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span></code></pre>

<h4 class="pdoc-member-header" id="User-isInstance">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azuredevops/blob/f8413512df804b703ebdd0da23b385c99bbe4500/sdk/nodejs/Entitlement/user.ts#L52">method <b>isInstance</b></a>
</h4>


<pre class="highlight"><code><span class='kd'>public static </span>isInstance(obj: <span class='kd'><a href='https://www.typescriptlang.org/docs/handbook/basic-types.html#any'>any</a></span>): obj is User</code></pre>


Returns true if the given object is an instance of User.  This is designed to work even
when multiple copies of the Pulumi SDK have been loaded into the same process.

<h4 class="pdoc-member-header" id="User-accountLicenseType">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azuredevops/blob/f8413512df804b703ebdd0da23b385c99bbe4500/sdk/nodejs/Entitlement/user.ts#L62">property <b>accountLicenseType</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>accountLicenseType: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span>&gt;;</code></pre>

Type of Account License. Valid values: `advanced`, `earlyAdopter`, `express`, `none`, `professional`, or `stakeholder`. Defaults to `express`. In addition the value `basic` is allowed which is an alias for `express` and reflects the name of the `express` license used in the Azure DevOps web interface.

<h4 class="pdoc-member-header" id="User-descriptor">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azuredevops/blob/f8413512df804b703ebdd0da23b385c99bbe4500/sdk/nodejs/Entitlement/user.ts#L66">property <b>descriptor</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>descriptor: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The descriptor is the primary way to reference the graph subject while the system is running. This field will uniquely identify the user graph subject.

<h4 class="pdoc-member-header" id="User-id">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azuredevops/blob/f8413512df804b703ebdd0da23b385c99bbe4500/sdk/nodejs/Entitlement/user.ts#L31">property <b>id</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>id: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>Output</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#ID'>ID</a>&gt;;</code></pre>

id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h4 class="pdoc-member-header" id="User-licensingSource">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azuredevops/blob/f8413512df804b703ebdd0da23b385c99bbe4500/sdk/nodejs/Entitlement/user.ts#L70">property <b>licensingSource</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>licensingSource: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span>&gt;;</code></pre>

The source of the licensing (e.g. Account. MSDN etc.) Valid values: `account` (Default), `auto`, `msdn`, `none`, `profile`, `trail`

<h4 class="pdoc-member-header" id="User-origin">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azuredevops/blob/f8413512df804b703ebdd0da23b385c99bbe4500/sdk/nodejs/Entitlement/user.ts#L74">property <b>origin</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>origin: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The type of source provider for the origin identifier.

<h4 class="pdoc-member-header" id="User-originId">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azuredevops/blob/f8413512df804b703ebdd0da23b385c99bbe4500/sdk/nodejs/Entitlement/user.ts#L78">property <b>originId</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>originId: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The unique identifier from the system of origin. Typically a sid, object id or Guid. e.g. Used for member of other tenant on Azure Active Directory.

<h4 class="pdoc-member-header" id="User-principalName">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azuredevops/blob/f8413512df804b703ebdd0da23b385c99bbe4500/sdk/nodejs/Entitlement/user.ts#L82">property <b>principalName</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>principalName: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The principal name is the PrincipalName of a graph member from the source provider. Usually, e-mail address.

<h4 class="pdoc-member-header" id="User-urn">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azuredevops/blob/f8413512df804b703ebdd0da23b385c99bbe4500/sdk/nodejs/Entitlement/user.ts#L31">property <b>urn</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>urn: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>Output</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#URN'>URN</a>&gt;;</code></pre>

urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.



<h2 id="apis">Others</h2>
<h3 class="pdoc-module-header" id="UserArgs" data-link-title="UserArgs">
    <a href="https://github.com/pulumi/pulumi-azuredevops/blob/f8413512df804b703ebdd0da23b385c99bbe4500/sdk/nodejs/Entitlement/user.ts#L155">
        interface <strong>UserArgs</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kr'>interface</span> <span class='nx'>UserArgs</span></code></pre>

The set of arguments for constructing a User resource.

<h4 class="pdoc-member-header" id="UserArgs-accountLicenseType">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azuredevops/blob/f8413512df804b703ebdd0da23b385c99bbe4500/sdk/nodejs/Entitlement/user.ts#L159">property <b>accountLicenseType</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>accountLicenseType?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

Type of Account License. Valid values: `advanced`, `earlyAdopter`, `express`, `none`, `professional`, or `stakeholder`. Defaults to `express`. In addition the value `basic` is allowed which is an alias for `express` and reflects the name of the `express` license used in the Azure DevOps web interface.

<h4 class="pdoc-member-header" id="UserArgs-licensingSource">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azuredevops/blob/f8413512df804b703ebdd0da23b385c99bbe4500/sdk/nodejs/Entitlement/user.ts#L163">property <b>licensingSource</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>licensingSource?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The source of the licensing (e.g. Account. MSDN etc.) Valid values: `account` (Default), `auto`, `msdn`, `none`, `profile`, `trail`

<h4 class="pdoc-member-header" id="UserArgs-origin">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azuredevops/blob/f8413512df804b703ebdd0da23b385c99bbe4500/sdk/nodejs/Entitlement/user.ts#L167">property <b>origin</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>origin?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The type of source provider for the origin identifier.

<h4 class="pdoc-member-header" id="UserArgs-originId">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azuredevops/blob/f8413512df804b703ebdd0da23b385c99bbe4500/sdk/nodejs/Entitlement/user.ts#L171">property <b>originId</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>originId?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The unique identifier from the system of origin. Typically a sid, object id or Guid. e.g. Used for member of other tenant on Azure Active Directory.

<h4 class="pdoc-member-header" id="UserArgs-principalName">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azuredevops/blob/f8413512df804b703ebdd0da23b385c99bbe4500/sdk/nodejs/Entitlement/user.ts#L175">property <b>principalName</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>principalName?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The principal name is the PrincipalName of a graph member from the source provider. Usually, e-mail address.

<h3 class="pdoc-module-header" id="UserState" data-link-title="UserState">
    <a href="https://github.com/pulumi/pulumi-azuredevops/blob/f8413512df804b703ebdd0da23b385c99bbe4500/sdk/nodejs/Entitlement/user.ts#L125">
        interface <strong>UserState</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kr'>interface</span> <span class='nx'>UserState</span></code></pre>

Input properties used for looking up and filtering User resources.

<h4 class="pdoc-member-header" id="UserState-accountLicenseType">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azuredevops/blob/f8413512df804b703ebdd0da23b385c99bbe4500/sdk/nodejs/Entitlement/user.ts#L129">property <b>accountLicenseType</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>accountLicenseType?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

Type of Account License. Valid values: `advanced`, `earlyAdopter`, `express`, `none`, `professional`, or `stakeholder`. Defaults to `express`. In addition the value `basic` is allowed which is an alias for `express` and reflects the name of the `express` license used in the Azure DevOps web interface.

<h4 class="pdoc-member-header" id="UserState-descriptor">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azuredevops/blob/f8413512df804b703ebdd0da23b385c99bbe4500/sdk/nodejs/Entitlement/user.ts#L133">property <b>descriptor</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>descriptor?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The descriptor is the primary way to reference the graph subject while the system is running. This field will uniquely identify the user graph subject.

<h4 class="pdoc-member-header" id="UserState-licensingSource">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azuredevops/blob/f8413512df804b703ebdd0da23b385c99bbe4500/sdk/nodejs/Entitlement/user.ts#L137">property <b>licensingSource</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>licensingSource?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The source of the licensing (e.g. Account. MSDN etc.) Valid values: `account` (Default), `auto`, `msdn`, `none`, `profile`, `trail`

<h4 class="pdoc-member-header" id="UserState-origin">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azuredevops/blob/f8413512df804b703ebdd0da23b385c99bbe4500/sdk/nodejs/Entitlement/user.ts#L141">property <b>origin</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>origin?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The type of source provider for the origin identifier.

<h4 class="pdoc-member-header" id="UserState-originId">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azuredevops/blob/f8413512df804b703ebdd0da23b385c99bbe4500/sdk/nodejs/Entitlement/user.ts#L145">property <b>originId</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>originId?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The unique identifier from the system of origin. Typically a sid, object id or Guid. e.g. Used for member of other tenant on Azure Active Directory.

<h4 class="pdoc-member-header" id="UserState-principalName">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azuredevops/blob/f8413512df804b703ebdd0da23b385c99bbe4500/sdk/nodejs/Entitlement/user.ts#L149">property <b>principalName</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>principalName?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The principal name is the PrincipalName of a graph member from the source provider. Usually, e-mail address.

