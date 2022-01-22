---
layout: grid-container
prose: true
header: true
---

# Component kitchen sink

These are all the available components on one page. This content file is located here: `docs/component-kitchen-sink.md`.

## Button

{% include components/button.html label="Create" link="index.html" %}

## Checkbox

{% include components/checkbox.html labels="Check yourself" %}

## Combo box

{% include components/combo-box.html label="State" values=site.data.states %}

## Dropdown

{% include components/dropdown.html label="Country" values="Canada,Cuba,Iceland,Ireland,Mexico,United Kingdom,United States" %}

## Header

Content page settings include: `header: true`.

## Link

{% include components/link.html label="Link text" link="index.html" %}

## Icon

{% include components/icon.html icon="info" %}

## Prose

Content page settings include: `prose: true`.

## Radio buttons

{% include components/radio-buttons.html legend="I am legend" labels="Yes,No,Maybe so" %}

## Tag

{% include components/tag.html labels="one,two,three" %}

## Text input

{% include components/text-input.html label="The Label" type="text" %}

## Tooltip

{% include components/button.html label="Create" link="#" style="usa-tooltip" tooltip="Click me to create an account" %}