---
layout: centered-column
header: false
layout-style: usa-prose margin-top-6 bg-base-lightest padding-5 radius-lg shadow-3 border-1px border-base-lighter
button-style: usa-button--big bg-primary-vivid hover:bg-primary-darker
text-input-style: radius-lg padding-3 border-2px border-base
---

# Create your account

<!-- Include a text input component for name. -->
{% include components/text-input.html label="Full name" type="text" %}

<!-- Include a text input component for email. -->
{% include components/text-input.html label="Email address" type="email" %}

<!-- Include an inline link for communication preference. -->
{% include components/link.html label="Use phone instead of email" link="#" %}

{% include components/radio-buttons.html legend="How excited are you about this form?" labels="Pretty excited 😃,Very excited 🤩,Meh 😐" tile=true %}

{% include components/checkbox.html labels="I have never not read the terms and conditions 🤞" legend="Terms & Conditions" %}

{% include components/icon.html icon="info" size="4" style="text-info-dark float-left margin-right-1" %}
After creating your account, you'll receive a message with a link to set up your username and password.

<!-- Include a button component as a call-to-action for completing the form. -->
{% include components/button.html label="Create" link="summary.html" %}

## Debugging

page.title: {{ page.title }}

page.title slug: {{ page.title | slugify }}

data:
<div id="data"></div>

{% include actions/save-data.html %}