---
layout: centered-column
header: false
prose: false
layout-style: width-mobile-lg
button-style: bg-primary-vivid hover:bg-primary-darker
text-input-style: radius-lg border-2px border-base
---
# Subscribe to our mailing list

{% include components/alert.html type="success" heading="Success" text="Thank you for subscribing. You’ll hear from us soon!" %}

{% include components/text-input.html label="Email" type="text" %}

{% include components/button.html label="Subscribe" link="#" %}

{% include actions/show.html click-this="subscribe" show-this="success" focus-this="close" %}

{% include actions/hide.html click-this="close" hide-this="success" %}