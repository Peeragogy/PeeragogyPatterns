Compile with:

```
pdflatex peeragogy_pattern_catalog && bibtex peeragogy_pattern_catalog && bibtex adx && pdflatex peeragogy_pattern_catalog && pdflatex peeragogy_pattern_catalog
```

Convert a given section to plain text

```
cat header.tex Peeragogy_Project.tex | pandoc --from=latex --to=plain --bibliography ./peeragogy-bib.bib --
```
