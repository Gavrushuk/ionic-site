---
layout: "v2_fluid/docs_base"
version: "nightly"
versionHref: "/docs/v2"
path: ""
category: api
id: "{{ItemSliding | slugify}}"
title: "ItemSliding"
header_sub_title: "Class in module "
doc: "ItemSliding"
docType: "class"

---









<h1 class="api-title">


ItemSliding






</h1>

<a class="improve-v2-docs" href='http://github.com/driftyco/ionic/edit/2.0/ionic/components/item/item-sliding.ts#L2'>
Improve this doc
</a>






<!-- description -->

<p>Creates a list-item that can easily be swiped, deleted, reordered, edited, and more.</p>


<h3>Component</h3>
<h3>selector: <code>ion-item-sliding</code></h3>
<!-- @usage tag -->

<h3 style="margin-bottom: 7px">Usage</h3>


<pre><code class="lang-html">&lt;ion-list&gt;
  &lt;ion-item-sliding *ngFor=&quot;#item of items&quot;&gt;
    &lt;ion-item (click)=&quot;itemTapped(item)&quot;&gt;
      {{item.title}}
    &lt;/ion-item&gt;
    &lt;ion-item-options&gt;
      &lt;button (click)=&quot;favorite(item)&quot;&gt;Favorite&lt;/button&gt;
      &lt;button (click)=&quot;share(item)&quot;&gt;Share&lt;/button&gt;
    &lt;/ion-item-options&gt;
  &lt;/ion-item-sliding&gt;
&lt;/ion-list&gt;
</code></pre>




<!-- @property tags -->


<!-- methods on the class --><!-- related link -->

<h3>Related</h3>

<a href='/docs/v2/components#lists'>List Component Docs</a>
<a href='../../list/List'>List API Docs</a><!-- end content block -->


<!-- end body block -->
