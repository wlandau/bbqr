---
name: Bug
about: txtq produced an error, failure, or otherwise unexpected result.
title: ''
labels: 'type: bug'
assignees: wlandau

---

## Prework

- [ ] Read and abide by `txtq`'s [code of conduct](https://github.com/wlandau/txtq/blob/main/CODE_OF_CONDUCT.md).
- [ ] Search for duplicates among the [existing issues](https://github.com/wlandau/txtq/issues), both open and closed.
- [ ] Advanced users: verify that the bug still persists in the current development version (i.e. `remotes::install_github("wlandau/txtq")`) and mention the [SHA-1 hash](https://git-scm.com/book/en/v1/Getting-Started-Git-Basics#Git-Has-Integrity) of the [Git commit you install](https://github.com/wlandau/txtq/commits/main).

## Description

Describe the bug clearly and concisely. 

## Reproducible example

Provide a minimal reproducible example with code and output that demonstrates the bug. The [`reprex`](https://github.com/tidyverse/reprex) package is extremely helpful for this.

## Session info

End the reproducible example with a call to `sessionInfo()` in the same session (e.g. `reprex(si = TRUE)`) and include the output.

## Expected output

What output would the correct behavior have produced?
