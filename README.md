# Clear Project Title

![Python 3.11+](https://img.shields.io/badge/Python-3.11%2B-blue?logo=python)
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
![Zenodo DOI pending](https://img.shields.io/badge/Zenodo_DOI-pending-lightgrey)
![Paper DOI pending](https://img.shields.io/badge/Paper_DOI-pending-lightgrey)
![Tests not configured](https://img.shields.io/badge/Tests-not_configured-lightgrey)

> One plain-language sentence saying what this project helps someone do or understand.

## Context and aim

This project began as a **[Master's thesis / PhD research project]** at **[institution and research group]**. It addresses **[problem and why it matters]** in **[study setting]**. The aim is to **[research question or tool purpose]**. Briefly state what the repository contains and the limits of its intended use.

**Project status:** [ongoing / completed; month and year].

## People and roles

| Name | Role | Affiliation | ORCID or profile |
| --- | --- | --- | --- |
| [Name] | Author / student researcher | [Institution] | [Link, if available] |
| [Name] | Supervisor | [Institution] | [Link, if available] |
| [Name] | Examiner (if applicable) | [Institution] | [Link, if available] |
| [Name] | Contributor (describe contribution) | [Institution] | [Link, if available] |

List people under their actual, agreed roles. Add or remove rows as needed.

## Research outputs

- **Thesis:** [Link to the record in DiVA or the Chalmers Master's thesis portal, if applicable.]
- **Archived software or dataset:** [Zenodo DOI link when available; state what the record contains.]
- **Paper:** [Paper DOI link when available; otherwise say “In preparation”, “Submitted”, or “Not applicable”.]
- **How to cite:** See [CITATION.cff](CITATION.cff). Update it before archiving a release.

The paper, thesis, software release, and dataset may have different identifiers. Link each one to the work it identifies.

## Repository structure

```text
README.md               Project overview and entry point
AGENTS.md               Instructions for an assistant reorganizing this repository
CITATION.cff            Citation metadata
LICENSE                 License for repository code
requirements.txt        Python dependencies, if Python is used
data/README.md          Data inventory, provenance, and archive links
docs/                   Methods, assumptions, setup, and reproduction instructions
notebooks/README.md     Guidance for a small tool demo, if relevant
```

Add `src/`, `scripts/`, `tests/`, and `notebooks/*.ipynb` when the project needs them. Keep generated and large data out of Git; describe where to obtain them in [data/README.md](data/README.md).

## Getting started

1. Install **[required software and versions]**. For a Python project, create an environment and install [requirements.txt](requirements.txt). Replace the language badge above if Python is not the primary language.
2. Obtain the small example inputs or archived data listed in [data/README.md](data/README.md).
3. Run **[one exact command that demonstrates the project]**. For a graphical tool, name the file to open and the steps to run one example.
4. Follow [docs/reproduce.md](docs/reproduce.md) to regenerate the main results.

Replace these placeholders with instructions that work from a fresh checkout.

## Documentation

Methods, assumptions, inputs, outputs, and limitations belong in [docs/](docs/README.md). If this repository provides a tool, include a short notebook or demo with a small input and the expected output.

## Funding

[Name funder and grant number, or state “No external funding reported.”]

## License

The repository code is intended to use the [MIT License](LICENSE). Confirm the code license and copyright holders with your supervisor before publication, especially when funder, partner, or institutional terms apply. State the license for any separately archived data in [data/README.md](data/README.md); it may differ from the code license.
