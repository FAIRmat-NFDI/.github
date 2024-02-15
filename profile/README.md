
![FAIRmat Banner](https://github.com/FAIRmat-NFDI/.github/assets/64071335/705d779e-684d-4e3c-843e-4916f3344de1)


# FAIRmat
[![Discord](https://img.shields.io/badge/Join%20our%20Discord-%235865F2.svg?style=&logo=discord&logoColor=white)](https://discord.gg/su9Vy2am9W)

We develop software to support the FAIR principles in the field of condensed-matter physics, the chemical physics of solids and materials science in general. The FAIR principles are a set of guiding principles to make data Findable, Accessible, Interoperable, and Reusable. The FAIRmat consortium is part of the National Research Data Infrastructure ([NFDI](https://www.nfdi.de/?lang=en)) and is funded by the Deutsche Forschungsgemeinschaft (DFG, German Research Foundation | project 460197019).


<center>

| FAIRmat | NOMAD 🏜️ | NOMAD Oasis 🌴 | NOMAD CAMELS 🐪 |
|:---:|:---:|:---:|:---:|
| [🌐](https://www.fairmat-nfdi.eu/) [📰](https://doi.org/10.1038/s41586-022-04501-x)| [🌐](https://nomad-lab.eu/nomad-lab/) [💻]([#](https://nomad-lab.eu/prod/v1/staging/gui/about/information#iss=https%3A%2F%2Fnomad-lab.eu%2Ffairdi%2Fkeycloak%2Fauth%2Frealms%2Ffairdi_nomad_prod)) [📚](https://nomad-lab.eu/prod/v1/staging/docs/index.html) [📰](https://joss.theoj.org/papers/10.21105/joss.05388)| [🌐](https://nomad-lab.eu/nomad-lab/nomad-oasis.html) [📚](https://nomad-lab.eu/prod/v1/staging/docs/howto/oasis/install.html)| [🌐](https://nomad-lab.eu/nomad-lab/nomad-camels.html) [💻](https://github.com/FAU-LAP/NOMAD-CAMELS) [📚](https://fau-lap.github.io/NOMAD-CAMELS/index.html) [📰](https://arxiv.org/pdf/2402.07548.pdf)|
| The NFDI consortium. | The main software. | Your local resource. | Control your lab instruments. |

</center>

# Repositories

A collection of repositories that are part of the FAIRmat consortium.

## NOMAD
<!-- [![NOMAD](https://img.shields.io/badge/Open%20NOMAD-navy)](https://nomad-lab.eu/prod/v1/staging/gui/) -->
[![NOMAD](https://img.shields.io/badge/Open%20NOMAD-lightgray?logo=data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4KPCEtLSBHZW5lcmF0b3I6IEFkb2JlIElsbHVzdHJhdG9yIDI3LjUuMCwgU1ZHIEV4cG9ydCBQbHVnLUluIC4gU1ZHIFZlcnNpb246IDYuMDAgQnVpbGQgMCkgIC0tPgo8c3ZnIHZlcnNpb249IjEuMSIgaWQ9IkxheWVyXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4IgoJIHZpZXdCb3g9IjAgMCAxNTAwIDE1MDAiIHN0eWxlPSJlbmFibGUtYmFja2dyb3VuZDpuZXcgMCAwIDE1MDAgMTUwMDsiIHhtbDpzcGFjZT0icHJlc2VydmUiPgo8c3R5bGUgdHlwZT0idGV4dC9jc3MiPgoJLnN0MHtmaWxsOiMxOTJFODY7c3Ryb2tlOiMxOTJFODY7c3Ryb2tlLXdpZHRoOjE0MS4zMjI3O3N0cm9rZS1taXRlcmxpbWl0OjEwO30KCS5zdDF7ZmlsbDojMkE0Q0RGO3N0cm9rZTojMkE0Q0RGO3N0cm9rZS13aWR0aDoxNDEuMzIyNztzdHJva2UtbWl0ZXJsaW1pdDoxMDt9Cjwvc3R5bGU+CjxwYXRoIGNsYXNzPSJzdDAiIGQ9Ik0xMTM2LjQsNjM2LjVjMTUwLjgsMCwyNzMuMS0xMjEuOSwyNzMuMS0yNzIuMlMxMjg3LjIsOTIuMSwxMTM2LjQsOTIuMWMtMTUwLjgsMC0yNzMuMSwxMjEuOS0yNzMuMSwyNzIuMgoJUzk4NS42LDYzNi41LDExMzYuNCw2MzYuNXoiLz4KPHBhdGggY2xhc3M9InN0MSIgZD0iTTEzMjksOTQ2Yy0xMDYuNC0xMDYtMjc4LjgtMTA2LTM4Ni4xLDBjLTk5LjYsOTkuMy0yNTguNywxMDYtMzY1LjEsMTguMWMtNi43LTcuNi0xMy40LTE2LjItMjEuMS0yMy45CgljLTEwNi40LTEwNi0xMDYuNC0yNzgsMC0zODQuOWMxMDYuNC0xMDYsMTA2LjQtMjc4LDAtMzg0LjlzLTI3OC44LTEwNi0zODYuMSwwYy0xMDcuMywxMDYtMTA2LjQsMjc4LDAsMzg0LjkKCWMxMDYuNCwxMDYsMTA2LjQsMjc4LDAsMzg0LjljLTYzLjIsNjMtODkuMSwxNTAtNzYuNywyMzIuMWM3LjcsNTcuMywzMy41LDExMy43LDc3LjYsMTU3LjZjMTA2LjQsMTA2LDI3OC44LDEwNiwzODYuMSwwCgljMTA2LjQtMTA2LDI3OC44LTEwNiwzODYuMSwwYzEwNi40LDEwNiwyNzguOCwxMDYsMzg2LjEsMEMxNDM1LjQsMTIyNCwxNDM1LjQsMTA1MiwxMzI5LDk0NnoiLz4KPC9zdmc+Cg==)](https://nomad-lab.eu/prod/v1/staging/gui/)

This is the main software that powers the infrastructure and our central deployment. It's a platform for sharing, storing, and analyzing materials data. You can install your own [NOMAD Oasis 🌴](https://nomad-lab.eu/nomad-lab/nomad-oasis.html) and customize it to meet your needs, including features to define your ELNs, custom schemas, parsers, and cloud-based analysis tools (NORTH).


| Repository  | Description                        | Docs                             | Publications |
|-----------------|------------------------------------|:----:|:----:|
| [nomad](https://github.com/nomad-coe/nomad) | The main NOMAD repository. | [📚](https://nomad-lab.eu/prod/v1/staging/docs/) | [📰](https://joss.theoj.org/papers/10.21105/joss.05388) |

## NOMAD Computational Parsers

A collection of parsers for various computational codes. These parsers are used to extract metadata from the output files of the codes and to store the metadata in the NOMAD Archive making the data findable, accessible, interoperable, and reusable (FAIR). Check out the full list of [supported codes](https://nomad-lab.eu/prod/v1/staging/docs/reference/parsers.html).

| Repository  | Description                                                                            | Docs |
|-----------------|----------------------------------------------------------------------------------------|:----:|
| [electronic-parsers](https://github.com/nomad-coe/electronic-parsers) | A collection of the NOMAD parsers for (~40) electronic codes.                         |[📚](https://fairmat-nfdi.github.io/AreaC-DOC/)               |
| [atomistic-parsers](https://github.com/nomad-coe/atomistic-parsers) | A collection of NOMAD parsers for atomistic codes (GROMACS, LAMMPS, ...).             |[📚](https://fairmat-nfdi.github.io/AreaC-DOC/)               |
| [workflow-parsers](https://github.com/nomad-coe/workflow-parsers) | A collection of NOMAD parsers for codes with computational workflows (FHI-vibes, LOBSTER, QuantumEspresso Family, ...). |[📚](https://fairmat-nfdi.github.io/AreaC-DOC/)               |

## NOMAD Plugins for Experiments

A collection of plugins for experimental data, including material processing and measurements. These plugins contain schemas, ELNs and parsers for experimental data.

| Repository  | Description                                                                            | Docs |
|-----------------|----------------------------------------------------------------------------------------|:----:|
| [nomad-materials-processing](https://github.com/FAIRmat-NFDI/nomad-material-processing) | A NOMAD plugin with base sections for material processing.                         |               |
| [nomad-measurements](https://github.com/FAIRmat-NFDI/nomad-measurements) | A NOMAD plugin containing base sections for measurements.            | [📚](https://fairmat-nfdi.github.io/nomad-measurements/)              |

## NeXus-Related Resources

We extend the [NeXus format](https://www.nexusformat.org/) to support the FAIR principles. This is a collection of repositories that are part of the FAIRmat consortium to support the NeXus format.

| Repository  | Description | Docs | PyPI |
|-----------------|-------------|:----:|:----:|
| [pynxtools](https://github.com/FAIRmat-NFDI/pynxtools) | Tool to develop ontologies and to create ontological instances based on the [NeXus format](https://www.nexusformat.org/). | [📚](https://fairmat-nfdi.github.io/pynxtools/) | [📦](https://pypi.org/project/your-package/) |
| [nyaml](https://github.com/FAIRmat-NFDI/nyaml) | A tool for converting NeXus application definitions from YAML (nyaml) to the Nexus Definitions Language (nxdl) format and vice-versa. | | [📦](https://pypi.org/project/nyaml/) |
| [nexus-definitions](https://github.com/FAIRmat-NFDI/nexus-definitions) | NeXus definitions including all the current FAIRmat contributions. | [📚](https://fairmat-nfdi.github.io/nexus_definitions/) |  |
