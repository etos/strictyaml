---
title: Why not X?
---

There are a number of formats and approaches that can achieve more or
less the same purpose as StrictYAML. I've tried to make it the best one.
Below is a series of documented justifications:

{% for dirfile in thisdir.is_not_dir() - thisdir.named("index.md") -%}
- [{{ title(dirfile) }}](../{{ dirfile.namebase }})
{% endfor %}

If you'd like to write or link to a rebuttal to any argument raised
here, feel free to raise a ticket.
