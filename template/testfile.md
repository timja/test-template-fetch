Hey - I'm component ${{ values.component_id }}

{% raw %}
```
{% from "macros/csrf.njk" import csrfProtection %}
...
<form ...>
  ...
    {{ csrfProtection(csrfToken) }}
  ...
</form>
...
```
{% endraw %}
