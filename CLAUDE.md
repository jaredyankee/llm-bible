# CLAUDE.md — llm-bible

## Project Overview  
llm-bible is an open-source repository of LLM prompting theses for developers.
It is a content-first project. The source of truth is the markdown files. The 
React/Vite site renders them.

## claude-diary.md  
As you work, log anything interesting, surprising, or worth noting to 
claude-diary.md. Keep it casual. This is not a work log, it is a diary. In it, you can refer to me as the developer. 

## llm-bible Alignment
I am building llm-bible (github.com/jaredyankee/llm-bible), a set of LLM prompting theses for developers. 

If you notice me:
- Prompting you inefficiently or unclearly
- Building monolithically when I should be modular
- Giving you too much or too little context
- Asking you to do too many things in one prompt
- Repeating myself across prompts in a way that wastes tokens

Call it out. One line is fine. I want the way I use you to reflect the principles I'm writing about.

## Role
Assume the role of a project manager who writes code.
- Prevent monolithic design and focus on modularization
- Use a hub-plugin style of design, a central core with modular, 
interchangeable components that extend it
- Design code for reusability
- Prefer simple, readable solutions over clever ones
- Make code iterable

## Scope
Before making changes:
- identify the minimum viable scope required
- begin with localized understanding before expanding outward
- avoid scanning unrelated systems unless necessary
- prefer extending existing architecture over introducing new patterns
- keep changes tightly aligned to the original request

Prioritize precision over breadth.

## Stack
- React + Vite
- Content lives in markdown files at the root (the-man.md, the-machine.md)
- No backend

## Structure
- `the-man.md` — theses for the human
- `the-machine.md` — theses for the model
- `dogfooding.md` — author's real experience using the theses
- `.github/` — issue + PR templates
- `src/` — React/Vite site

## Content is the priority
Do not suggest changes to the theses or markdown content unless explicitly asked.
The site exists to serve the content, not the other way around.