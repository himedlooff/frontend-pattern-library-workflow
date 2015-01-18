# Introducing styleguides into your front-end workflow

:thought_balloon:
As a front-end developer I have recently been including styleguides into my workflow.
This document is my attempt to capture and share my experience and thoughts with others.

:speech_balloon:
Discussion is encouraged by filling out an issue:
<https://github.com/himedlooff/frontend-styleguide-workflow/issues/new>

---

# Experience

## Process used

- Analyze the design and spot new patterns.
- Build the patterns first.
- Document and collect them into a pattern library as you build them, not after you're done building the design. Use tools like Topdoc or Dox-ray. Use task runners like Grunt to help with this process.
- Build out the design using the patterns you created.
- Think "reusable" first, instead of "page-specific" first. It's easier to have a one-off pattern than it is to go back and refactor patterns that you thought were page-specific.
