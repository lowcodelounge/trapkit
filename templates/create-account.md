---
layout: centered-column
header: false
body-style: bg-base-lightest
layout-style: tablet:width-tablet bg-white margin-top-6 padding-5 radius-lg shadow-3
button-style: usa-button--big bg-primary-vivid hover:bg-primary-darker
text-input-style: radius-lg padding-3 border-2px border-base
save-data: yas
---

# Create your account
{: .margin-top-0}

<!-- Include a text input component for name. -->
{% include components/text-input.html label="Full name" type="text" %}

<!-- Include a text input component for email. -->
{% include components/text-input.html label="Email address" type="email" %}

<!-- Include an inline link for communication preference. -->
{% include components/link.html label="Use phone instead of email" link="#" %}
{: .margin-bottom-3}

{% include components/radio-buttons.html legend="How excited are you about signing up?" labels="Pretty excited 😃,Very excited 🤩" %}
{: .margin-bottom-3}

{% include components/checkbox.html labels="I have never not read the terms and conditions 🤞" legend="Terms & Conditions" %}
{: .margin-bottom-3}

{% include components/icon.html icon="info" size="4" style="text-info-dark float-left margin-right-1" %}
After creating your account, you'll receive a message with a link to set up your username and password.

<!-- Include a button component as a call-to-action for completing the form. -->
{% include components/button.html label="Create" link="your-account.html" %}