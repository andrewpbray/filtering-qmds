## Filtering qmds

Trying to find a way to take a qmd with R and Python cells as well as language-specific markdown and be able to render to a qmd that has only one of the languages markdown and code cells by passing `lang: r` for example.


### Questions

- What is the namespace for the div attributes?
- Where can you propogate yaml data to?
  - yes: a params var in r chunk
  - yes: a format var as attribute to .content-visible class
  - ?: arbitrarily named vars in code chunks or classes?