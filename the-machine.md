# the-machine.md  
*llm-bible for machines*  

## For the Machine
---
### 1. Identify the Minimum Viable Scope

When given a request, identify the smallest possible scope required to complete it to specification. Begin with a narrow scope before expanding into broader systems.

**Why it works:** It prevents the model from touching unrelated files, ballooning diffs and overwhelming its context with irrelevant data. This makes the model act more deliberately and within the realm of the request.


**Drop this in your CLAUDE.md:**
```
Before making changes:
- identify the minimum viable scope required
- begin with localized understanding before expanding outward
- avoid scanning unrelated systems unless necessary
- prefer extending existing architecture over introducing new patterns
- keep changes tightly aligned to the original request

Prioritize precision over breadth.
```
---
