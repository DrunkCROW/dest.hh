---
title: bias
slug: Web/SVG/Attribute/bias
tags:
  - Filters
  - NeedsExample
  - SVG
  - SVG Attribute
browser-compat: svg.elements.feConvolveMatrix.bias
---
{{SVGRef}}

The **`bias`** attribute shifts the range of the filter. After applying the {{SVGAttr("kernelMatrix")}} of the {{SVGElement("feConvolveMatrix")}} element to the input image to yield a number and applied the {{SVGAttr("divisor")}} attribute, the `bias` attribute is added to each component. This allows representation of values that would otherwise be clamped to 0 or 1.

You can use this attribute with the following SVG elements:

* {{SVGElement("feConvolveMatrix")}}

## Usage notes

<table class="properties">
  <tbody>
    <tr>
      <th scope="row">Value</th>
      <td>
        <a href="/en-US/docs/Web/SVG/Content_type#Number">&#x3C;number></a>
      </td>
    </tr>
    <tr>
      <th scope="row">Default value</th>
      <td><code>0</code></td>
    </tr>
    <tr>
      <th scope="row">Animatable</th>
      <td>Yes</td>
    </tr>
  </tbody>
</table>

One application of bias is when it is desirable to have 0.5 gray value be the zero response of the filter.

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
        {{SpecName("Filters 1.0", "#element-attrdef-feconvolvematrix-bias", "bias")}}
      </td>
      <td>{{Spec2("Filters 1.0")}}</td>
      <td>No change</td>
    </tr>
    <tr>
      <td>
        {{SpecName("SVG1.1", "filters.html#feConvolveMatrixElementBiasAttribute", "bias")}}
      </td>
      <td>{{Spec2("SVG1.1")}}</td>
      <td>Initial definition</td>
    </tr>
  </tbody>
</table>

## Browser compatibility

{{Compat}}
