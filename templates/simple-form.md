---
layout: centered-column
header: false
layout-style: tablet:width-mobile-lg
button-style: bg-primary-vivid hover:bg-primary-darker
---

{% include components/alert.html heading="Warning" text="This form may cause unusual levels of excitement." type="warning" style="margin-top-4" %}

# Excitement level

{% include components/radio-buttons.html legend="How excited are you about this form?" labels="Pretty excited 😃,Very excited 🤩,Meh 😐" tile=true %}
{: .margin-bottom-3}

{% include components/checkbox.html legend="Terms & Conditions" labels="I have never not read the terms and conditions 🤞" %}
{: .margin-bottom-3}

{% include components/button.html label="Embrace my emotion 🤗" link="#" %}

<!-- Include action to save data from all inputs as it's entered. -->
{% include actions/save-data.html %}