---
layout: grid-container
header: false
---

# Data

This is all the data you have saved in the `localStorage` feature of the browser for this site. If you want to can clear all of it and start over.

{% include components/button.html label="Clear data" link="#" %}

## Saved data

<script>
document.write('<table id="list-of-data" class="usa-table">');
document.write('<thead><tr><th scope="col">Key</th><th scope="col">Value</th></tr></thead>');
for (var i = 0; i < localStorage.length; i++){
    $('#list-of-data').append('<tr><td>' + localStorage.key(i) + '</td><td>' + localStorage.getItem(localStorage.key(i)) + '</td></tr>');
}
document.write('</table>');

$('#clear-data').on('click', function(){
    window.localStorage.clear();
    window.location.reload();
});

</script>