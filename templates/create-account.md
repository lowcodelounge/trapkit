---
layout: default
header: false
prose: true
---

# Create your account

<!-- Include a text input component for name. -->
{% include text-input.html label="Name" id="name" type="text" %}

<!-- Include a text input component for email. -->
{% include text-input.html label="Email" id="email" type="email" %}

[Use phone instead of email](#){: .usa-link}

After creating your account, you'll receive a message with a link to set up your username and password.

<!-- Include a button component as a call-to-action for completing the form. -->
{% include button.html label="Create" link="../index.html" style="usa-button--big" new-tab=false %}