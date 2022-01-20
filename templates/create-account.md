---
layout: default
header: false
prose: true
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

After creating your account, you'll receive a message with a link to set up your username and password.

<!-- Include a button component as a call-to-action for completing the form. -->
{% include components/button.html label="Create" link="#" %}