# Experiences and thoughts on styleguide driven development

I have been using a pseudo-styleguide driven approach to recent projects.
This document is my attempt to capture and share my experience and thoughts with others.

Discussion is encouraged by filiing out an issue: <https://github.com/himedlooff/styleguide-driven-development-notes/issues/new>

---

# Experience

## Process used

- Analyze the design and spot new patterns.
- Build the patterns first.
- Document and collect them into a pattern library as you build them, not after you're done building the design. Use tools like Topdoc or Dox-ray. Use task runners like Grunt to help with this process.
- Build out the design using the patterns you created.
- Think "reusable" first, instead of "page-specific" first. It's easier to have a one-off pattern than it is to go back and refactor patterns that you thought were page-specific.
