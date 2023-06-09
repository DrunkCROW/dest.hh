---
title: amplitude
slug: Web/SVG/Attribute/amplitude
tags:
  - NeedsCompatTable
  - SVG
  - SVG Attribute
---
{{SVGRef}}

The **`amplitude`** attribute controls the amplitude of the gamma function of a component transfer element when its {{SVGAttr("type")}} attribute is `gamma`.

You can use this attribute with the following SVG elements:

* {{SVGElement("feFuncA")}}
* {{SVGElement("feFuncB")}}
* {{SVGElement("feFuncG")}}
* {{SVGElement("feFuncR")}}

## Usage notes

<table class="properties">
  <tbody>
    <tr>
      <th scope="row">Value</th>
      <td><a href="/en-US/docs/Web/CSS/number">&#x3C;number></a></td>
    </tr>
    <tr>
      <th scope="row">Default value</th>
      <td><code>1</code></td>
    </tr>
    <tr>
      <th scope="row">Animatable</th>
      <td>Yes</td>
    </tr>
  </tbody>
</table>

## Specifications

<table class="no-markdown">
  <thead>
    <tr>
      <th scope="col">Specification</th>
      <th scope="col">Status</th>
      <th scope="col">Comment</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        {{SpecName("Filters 1.0", "#element-attrdef-fecomponenttransfer-amplitude", "amplitude")}}
      </td>
      <td>{{Spec2("Filters 1.0")}}</td>
      <td>No change</td>
    </tr>
    <tr>
      <td>
        {{SpecName("SVG1.1", "filters.html#feComponentTransferAmplitudeAttribute", "amplitude")}}
      </td>
      <td>{{Spec2("SVG1.1")}}</td>
      <td>Initial definition</td>
    </tr>
  </tbody>
</table>

## See also

* {{SVGElement("feComponentTransfer")}}
