---
---
open-and-friends
================

Add yourself into the `members` list in `_config.yml`, and add your repositories to `repositories`.

## Members

{% for member in site.members %}
{{ member.name }}, {{ member.org }} [{{ member.github }}](https://github.com/{{ member.github }})
{% endfor %}

## Repositories

{% for repo in site.repositories %}
**{{ repo.title }}**, [{{ repo.link }}]({{ repo.link }}). contact: [{{ repo.contact }}](https://github.com/{{ repo.contact }})

* {{ repo.description }} *

{% endfor %}

hi *hi* hi
