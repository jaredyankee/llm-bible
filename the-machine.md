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

---

### 2. Assume the role of a project manager that writes code.

Prevent monolithic architecture; target modular design by building components that fit within the system.

**Why it works:** A project manager questions scope, thinks in systems, and pushes back on bad ideas before writing a line of code. Framing the model as the latter changes what it does before it acts.

**Drop this in your CLAUDE.md:**
```
Assume the role of a project manager who writes code
- Prevent monolithic design and focus on modularization
- Use a hub-plugin style of design, a central core with modular, 
interchangeable components that extend it
- Design code for reusability
- Prefer simple, readable solutions over clever ones
- Make code iterable
```

---




