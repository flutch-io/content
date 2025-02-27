---
title: 'ARIA: range role'
slug: Web/Accessibility/ARIA/Roles/range_role
tags:
  - Accessibility
  - ARIA
  - roles
  - Reference
  - ARIA roles
  - Abstract role
spec-urls: https://w3c.github.io/aria/#range
---


The `range` abstract role is a generic type of structure role representing a range of values.

> **Note:**  The `range` role is an [abstract role](/en-US/docs/Web/Accessibility/ARIA/Roles/#Abstract_roles). It is included here for completeness of documentation. It is not to be used by web authors.

## Description

The `range` role is an abstract role. It must not be used by web authors. It is the superclass for structural roles for elements that accept a value within a range of values, including the [`meter`](/en-US/docs/Web/Accessibility/ARIA/Roles/meter_role) role, [`progressbar`](/en-US/docs/Web/Accessibility/ARIA/Roles/progressbar_role) and [`slider`](/en-US/docs/Web/Accessibility/ARIA/Roles/slider_role). For these three, consider using the {{HTMLElement("meter")}} element, the {{HTMLElement("progress")}} element, and the {{HTMLElement("input/range")}}, respectively.

## Best Practices

Do not use.

## Specifications

{{Specifications}}

## See Also

- [ARIA: `structure` role](/en-US/docs/Web/Accessibility/ARIA/Roles/structure_role)
- [ARIA: `meter` role](/en-US/docs/Web/Accessibility/ARIA/Roles/meter_role)
- [ARIA: `progressbar` role](/en-US/docs/Web/Accessibility/ARIA/Roles/progressbar_role)
- [ARIA: `scrollbar` role](/en-US/docs/Web/Accessibility/ARIA/Roles/scrollbar_role)
- [ARIA: `slider` role](/en-US/docs/Web/Accessibility/ARIA/Roles/slider_role)
- [ARIA: `spinbutton` role](/en-US/docs/Web/Accessibility/ARIA/Roles/spinbutton_role)
- {{HTMLElement("input/range")}}
- {{HTMLElement("meter")}}
- {{HTMLElement("progress")}}

<section id="Quick_links">

1. [**WAI-ARIA roles**](/en-US/docs/Web/Accessibility/ARIA/Roles)

    {{ListSubpagesForSidebar("/en-US/docs/Web/Accessibility/ARIA/Roles")}}

</section>
