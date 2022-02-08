---
layout: sidebar
prose: false
header: true
sidebar: component-nav.md
---

# Component kitchen sink

These are all the available components on one page. To include the component on a Markdown content page, copy and paste the line of text. This content file is located here: [`docs/component-kitchen-sink.md`](https://github.com/pglevy/rwp-toolkit/blob/main/docs/component-kitchen-sink.md).

## Accordion

{% include components/accordion.html collection=site.charters %}

`{% raw %}{% include components/accordion.html collection=site.charters %}{% endraw %}`

## Alert

{% include components/alert.html heading="Warning" text="This form may cause unusual levels of excitement." type="warning" %}

`{% raw %}{% include components/alert.html heading="Warning" text="This form may cause unusual levels of excitement." type="warning" %}{% endraw %}`

## Breadcrumb

{% include components/breadcrumb.html %}

`{% raw %}{% include components/breadcrumb.html %}{% endraw %}`

Front matter:

```
---
breadcrumbs:
- name: Framework
  url: framework/
- name: Molecules
  url: framework/molecules/
---
```

## Button

{% include components/button.html label="Create" link="index.html" %}

`{% raw %}{% include components/button.html label="Create" link="index.html" %}{% endraw %}`

## Card

{% include components/card.html width="tablet:grid-col-4" values=site.data.cards %}

`{% raw %}{% include components/card.html width="tablet:grid-col-4" values=site.data.cards %}{% endraw %}`

## Checkbox

{% include components/checkbox.html labels="Check yourself" %}

`{% raw %}{% include components/checkbox.html labels="Check yourself" %}{% endraw %}`

## Combo box

{% include components/combo-box.html label="State" values=site.data.states %}

`{% raw %}{% include components/combo-box.html label="State" values=site.data.states %}{% endraw %}`

## Dropdown

{% include components/dropdown.html label="Country" values="Canada,Cuba,Iceland,Ireland,Mexico,United Kingdom,United States" %}

`{% raw %}{% include components/dropdown.html label="Country" values="Canada,Cuba,Iceland,Ireland,Mexico,United Kingdom,United States" %}{% endraw %}`

## Header

Content page settings include: `header: true`.

## Link

{% include components/link.html label="Link text" link="index.html" %}

`{% raw %}{% include components/link.html label="Link text" link="index.html" %}{% endraw %}`

## Icon

{% include components/icon.html icon="info" %}

`{% raw %}{% include components/icon.html icon="info" %}{% endraw %}`

## Prose

Content page settings include: `prose: true`.

## Radio buttons

{% include components/radio-buttons.html legend="I am legend" labels="Yes,No,Maybe so" %}

`{% raw %}{% include components/radio-buttons.html legend="I am legend" labels="Yes,No,Maybe so" %}{% endraw %}`

## Side navigation

```
---
sidebar: side-nav.md
sidenav-parent: Current Parent
sidenav-child: Current Child
---
```

## Tag

{% include components/tag.html labels="one,two,three" %}

`{% raw %}{% include components/tag.html labels="one,two,three" %}{% endraw %}`

## Text input

{% include components/text-input.html label="The Label" type="text" %}

`{% raw %}{% include components/text-input.html label="The Label" type="text" %}{% endraw %}`

## Tooltip

{% include components/button.html label="Create" link="#" style="usa-tooltip" tooltip="Click me to create an account" %}

`{% raw %}{% include components/button.html label="Create" link="#" style="usa-tooltip" tooltip="Click me to create an account" %}{% endraw %}`