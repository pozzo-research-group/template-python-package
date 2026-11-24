# package-name

<!-- After "Use this template", work through this checklist, then delete it.
- [ ] Replace package-name (repo, pyproject.toml) and package_name (src/package_name, imports).
- [ ] LICENSE: replace YEAR and AUTHOR NAMES. MIT is the group default for new repositories.
- [ ] CITATION.cff: title, authors (with ORCIDs), date. Run `cffconvert --validate`.
- [ ] Set the repository description and one category topic.
- [ ] Fill in every section below.
See the group's repository guide: https://github.com/pozzo-research-group/.github/blob/main/REPOSITORY_GUIDE.md
-->

[![Tests](https://github.com/pozzo-research-group/package-name/actions/workflows/tests.yml/badge.svg)](https://github.com/pozzo-research-group/package-name/actions/workflows/tests.yml)
<!-- After the first Zenodo release, add the concept-DOI badge:
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.NNNNNNN.svg)](https://doi.org/10.5281/zenodo.NNNNNNN) -->

One paragraph: what this package does and who it is for.

## Paper

If this package accompanies a paper: *Published title*, Journal (year), [doi:10.xxxx/xxxxx](https://doi.org/10.xxxx/xxxxx).

## Install

```
conda env create -f environment.yml
conda activate package-name
pip install -e ".[test]"
```

## Minimal example

```python
import package_name
print(package_name.__version__)
```

## Data

See [data/README.md](data/README.md).

## Maintainer

Name (GitHub @username). Report problems in [Issues](../../issues).

## How to cite

See [CITATION.cff](CITATION.cff), or use **"Cite this repository"** on the GitHub page.

## License

[MIT](LICENSE)
