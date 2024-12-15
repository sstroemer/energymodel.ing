# energymodel.ing

Content of the [energymodel.ing](https://energymodel.ing/) blog/page.

## Guide

This section contains some commonly used prepared "X", that may be helpful.

### Writing

#### Abbreviatons

```html
<abbr title="Energy System Optimization Models">ESOMs</abbr>
```

#### Digest

Each paper in the digest follows this structure:

- **Title:** Some title followed by `(Authors, Year)`.
- **Description:** The exact title of the original paper.
- **Citation:** The citation is given as footnote as soon as readable (and as first one!), using APA style from [Google Scholar](https://scholar.google.com/), applying italics and similar stylings.
- **DOI:** The citation is directly followed by a DOI link that looks like `doi.org/10.1000/j.foobar.YYYY.AA.BBB`.

Example: https://energymodel.ing/digest/kotzur-2018/

### Commands

**Set-up of pre-commit and dependencies**  
```shell
pipx install pre-commit
pre-commit install

sudo snap install vale
```

**Creating a new article**  
```shell
hugo new content general/some-title.md
```

**Pushing changes without re-building**  
```shell
git push -o skip.ci
```
