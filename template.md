---
description: Resource markdown template
maturity: Strawman
content_type: Specification
author: Sean Drucker
audience: 
- Everyone
version: 0.0.1
---

# Template
*[{{ page.maturity }}](/lifecycle.md#{{ page.maturity }}) {{ page.content_type }} for {{ page.audience }} by {{ page.author }} v{{ page.version }}*

Markdown files that describe a resource have a YAML header, a title, and content.

## YAML Header (Front Matter)

```yaml
---
description: Resource markdown template
maturity: Draft
content_type: Specification
author: Sean Drucker
audience: 
- Organization
version: 0.0.1
---
```

## Title

The first header should be the title of the resource.

## Content

Content can have any number of sections, but may have the following top level sections: 

```markdown
# References
- [Example](http://example.com)
```