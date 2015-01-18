# Introducing pattern libraries into your front-end workflow

:thought_balloon:
As a front-end developer I have recently been including pattern libraries into my workflow.
This document is my attempt to capture and share my experience and thoughts with others.

:question:
I'm not exactly sure about terminology here. Am I referring to a style guide, a living style guide, a CSS or front-end style guide, a pattern library?
_Pattern library_ seems to be the clearest term since _style guide_ can also refer to design-centric guides.
Further thoughts on this will be tracked here:
<https://github.com/himedlooff/frontend-pattern-library-workflow/issues/1>

:speech_balloon:
Discussion is encouraged by filling out an issue:
<https://github.com/himedlooff/frontend-pattern-library-workflow/issues/new>

---

# What is a pattern library?

# Pattern library pros and cons

- Pro: promotes code reuse, which means less redundant code
- Pro: easy to test
- Pro: awareness of what exists across teams and team members
- Pro: front-end code is more approachable and usable by other team members, even non-technical team members, making the front-end developer less of a blocker
- Con: fitting it into your workflow can be a challenge
- Con: depending on which solution you use they can be hard to maintain
- Con: over-documenting can make it hard for others to find what they're looking for
- Con: under-documenting can cause fractured implementation of patterns

# Front-end owning the pattern library

# Experience

## Workflow

- Analyze the design and spot new patterns.
- Build the patterns first.
- Document and collect them into a pattern library as you build them, not after you're done building the design. Use tools like Topdoc or Dox-ray. Use task runners like Grunt to help with this process.
- Build out the design using the patterns you created.
- Think "reusable" first, instead of "page-specific" first. It's easier to have a one-off pattern than it is to go back and refactor patterns that you thought were page-specific.

# Formats

Talk about the different formats that your pattern library can take and baby steps that can help you ease into this kind of workflow.

# Participation

Thoughts on making participation easy:

- Make it part of the workflow
- Use GitHub, GitHub Issues and GitHub Pages
- jQuery gh-issues plugin
