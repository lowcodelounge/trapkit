---
layout: centered-column
header: false
---

# Data Summary

{% include components/text-input.html label="Saved name" type="text" %}

{% include components/text-input.html label="Saved email" type="text" %}

{% include components/text-input.html label="Excitement level" type="text" %}

{% include actions/get-data.html get-this="create-your-account-full-name" put-it-here="saved-name" %}

{% include actions/get-data.html get-this="create-your-account-email-address" put-it-here="saved-email" %}

{% include actions/get-data.html get-this="create-your-account-how-excited-are-you-about-this-form" put-it-here="excitement-level" %}

[Go back to form](create-account.html)
