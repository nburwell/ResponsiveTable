# ResponsiveTable

## Live Demo
[View the demo](http://nburwell.github.com/ResponsiveTable/).

## Example

Use a normal table with added markup in the head row.

```html
<table class="responsive-table">
  <thead>
    <tr>
      <th class="persist">Name</th>
      <th class="essential">Employer</th>
      <th class="optional">Education</th>
      <th class="optional">Graduated</th>
      <th>Notes</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Bob</td>
      <td>Google</td>
      <td>Computer Science</td>
      <td>2004</td>
      <td>likes hikes and photography</td>
    </tr>
    <tr>
      <td>John</td>
      <td>Bing</td>
      <td>Computer Engineering</td>
      <td>2001</td>
      <td>volleyball, tennis</td>
    </tr>
  </tbody>
</table>
```

Enable the plugin on the table(s)

```javascript
$(document).ready(function() {
  $('.responsive-table').responsiveTable();
});
```