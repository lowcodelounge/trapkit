---
layout: centered-column
header: false
body-style: bg-base-lightest
layout-style: tablet:width-tablet bg-white margin-top-6 padding-5 radius-lg shadow-3
button-style: usa-button--big bg-primary-vivid hover:bg-primary-darker
text-input-style: radius-lg padding-3 border-2px border-base
---

# Your account
{: .margin-top-0}

<!-- Text input component for name. -->
{% include components/text-input.html label="Full name" type="text" %}

{% include actions/get-data.html get-this="create-your-account-full-name" put-it-here="full-name" %}

<!-- Text input component for email. -->
{% include components/text-input.html label="Email address" type="email" %}

{% include actions/get-data.html get-this="create-your-account-email-address" put-it-here="email-address" %}

## Excitement level

{% include actions/get-data.html get-this="create-your-account-how-excited-are-you-about-signing-up" %}

[Take me home]({{ site.url }}/)