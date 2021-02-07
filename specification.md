---
description: Specification for describing a resource in a markdown file.
maturity: strawman
content_type: specification
author: 
- Sean Drucker
audience:
- everyone
- everything
version: 0.0.1
---

# Resource Markdown File Specification
A *[{{ page.maturity }}](/lifecycle.md#{{ page.maturity }}) {{ page.content_type }} for {{ page.audience }} by {{ page.author }} v{{ page.version }}*

**{{page.description}}**

## TL;DR

Resources are described in a markdown file.  A simple way to create a new resource description is to copy and modify the [Template](/template.md] or cut and paste the template below.

## Template

```markdown
---
description: Resource markdown template
maturity: strawman
content_type: specification
author: Sean Drucker
audience: 
- everyone
- everything
version: 0.0.1
---

# Title
{% raw %}
*[{{ page.maturity }}](/lifecycle.md#{{ page.maturity }}) {{ page.content_type }} for {{ page.audience }} by {{ page.author }} v{{ page.version }}*

{{page.description}}
{% endraw %}

## TL;DR

Brief description of the resource

# References

- [Example](http://example.com)

```

## YAML Header (Front Matter)

### Description

A short description of the resource.

### Maturity

The [lifecycle](/lifecycle.md) maturity of the resource.