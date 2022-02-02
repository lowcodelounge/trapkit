---
layout: centered-column
header: false
prose: false
layout-style: tablet:width-mobile-lg
button-style: bg-primary-vivid hover:bg-primary-darker
---

# Add a new address

{% include components/text-input.html label="Name" type="text" %}

{% include components/text-input.html label="Address" type="text" %}

{% include components/combo-box.html label="State" values=site.data.states style="width-half" %}

{% include components/text-input.html label="Zip code" type="text" style="width-half" %}

{% include components/dropdown.html label="Country" values="Canada,Cuba,Iceland,Ireland,Mexico,United Kingdom,United States" style="width-half" %}

{% include components/button.html label="Save" link="#" %}