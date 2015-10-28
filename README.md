Compile with:

```
pdflatex peeragogy_pattern_catalog && bibtex peeragogy_pattern_catalog && bibtex adx && pdflatex peeragogy_pattern_catalog && pdflatex peeragogy_pattern_catalog
```

Convert a given section to plain text

```
cat header.tex Peeragogy_Project.tex | pandoc --from=latex --to=plain --bibliography ./peeragogy-bib.bib --
```


[![Join the chat at https://gitter.im/Peeragogy/PeeragogyPatterns](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/Peeragogy/PeeragogyPatterns?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)