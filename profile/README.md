
![FAIRmat Banner](https://github.com/FAIRmat-NFDI/.github/assets/64071335/0625f13f-18ec-47ff-a5ed-f52f0110d553)


# FAIRmat
[![Discord](https://img.shields.io/badge/Discord-Join%20us-navy)](https://discord.gg/su9Vy2am9W)

We develop software to support the FAIR principles in the field of condensed-matter physics, the chemical physics of solids and materials science in general. The FAIR principles are a set of guiding principles to make data Findable, Accessible, Interoperable, and Reusable. The FAIRmat consortium is part of the National Research Data Infrastructure ([NFDI](https://www.nfdi.de/?lang=en)) and is funded by the Deutsche Forschungsgemeinschaft (DFG, German Research Foundation | project 460197019).


<center>

| FAIRmat | NOMAD 🏜️ | NOMAD Oasis 🌴 | NOMAD CAMELS 🐪 |
|:---:|:---:|:---:|:---:|
| [🌐](https://www.fairmat-nfdi.eu/) | [🌐](https://nomad-lab.eu/nomad-lab/) [💻]([#](https://nomad-lab.eu/prod/v1/staging/gui/about/information#iss=https%3A%2F%2Fnomad-lab.eu%2Ffairdi%2Fkeycloak%2Fauth%2Frealms%2Ffairdi_nomad_prod)) [📚](https://nomad-lab.eu/prod/v1/staging/docs/index.html)| [🌐](https://nomad-lab.eu/nomad-lab/nomad-oasis.html) [📚](https://nomad-lab.eu/prod/v1/staging/docs/howto/oasis/install.html)| [🌐](https://nomad-lab.eu/nomad-lab/nomad-camels.html) [💻](https://github.com/FAU-LAP/NOMAD-CAMELS) [📚](https://fau-lap.github.io/NOMAD-CAMELS/index.html)|
| The NFDI consortium. | The main software. | Your local resource. | Control your lab instruments. |

</center>

# Repositories

A collection of repositories that are part of the FAIRmat consortium.

## NOMAD
[![NOMAD](https://img.shields.io/badge/Open%20NOMAD-navy)](https://nomad-lab.eu/prod/v1/staging/gui/)

This is the main software that powers the infrastructure and our central deployment. It's a platform for sharing, storing, and analyzing materials data. You can install your own [NOMAD Oasis 🌴](https://nomad-lab.eu/nomad-lab/nomad-oasis.html) and customize it to meet your needs, including features to define your ELNs, custom schemas, parsers, and cloud-based analysis tools (NORTH).


| Repository Name | Description                        | Docs                             |
|-----------------|------------------------------------|:----:|
| [nomad](https://github.com/nomad-coe/nomad) | The main NOMAD repository. | [📚](https://nomad-lab.eu/prod/v1/staging/docs/) |

## NOMAD Computational Parsers

A collection of parsers for various computational codes. These parsers are used to extract metadata from the output files of the codes and to store the metadata in the NOMAD Archive making the data findable, accessible, interoperable, and reusable (FAIR). Check out the full list of [supported codes](https://nomad-lab.eu/prod/v1/staging/docs/reference/parsers.html).

| Repository  | Description                                                                            | Docs |
|-----------------|----------------------------------------------------------------------------------------|:----:|
| [electronic-parsers](https://github.com/nomad-coe/electronic-parsers) | A collection of the NOMAD parsers for (~40) electronic codes.                         |               |
| [atomistic-parsers](https://github.com/nomad-coe/atomistic-parsers) | A collection of NOMAD parsers for atomistic codes (GROMACS, LAMMPS, ...).             |               |
| [workflow-parsers](https://github.com/nomad-coe/workflow-parsers) | A collection of NOMAD parsers for codes with computational workflows (FHI-vibes, LOBSTER, QuantumEspresso Family, ...). |               |

## NOMAD Plugins for Experiments

| Repository  | Description                                                                            | Docs |
|-----------------|----------------------------------------------------------------------------------------|:----:|
| [nomad-materials-processing](https://github.com/FAIRmat-NFDI/nomad-material-processing) | A plugin with base sections for material processing.                         |               |
| [nomad-measurements](https://github.com/FAIRmat-NFDI/nomad-measurements) | A NOMAD plugin containing base sections for measurements.            |               |

## NeXus-Related Resources

We extend the [NeXus format](https://www.nexusformat.org/) to support the FAIR principles. This is a collection of repositories that are part of the FAIRmat consortium to support the NeXus format.

| Repository  | Description | Docs | PyPI |
|-----------------|-------------|:----:|:----:|
| [pynxtools](https://github.com/FAIRmat-NFDI/pynxtools) | Tool to develop ontologies and to create ontological instances based on the [NeXus format](https://www.nexusformat.org/). | [📚](https://fairmat-nfdi.github.io/pynxtools/) | [📦](https://pypi.org/project/your-package/) |
| [nyaml](https://github.com/FAIRmat-NFDI/nyaml) | A tool for converting NeXus application definitions from YAML (nyaml) to the Nexus Definitions Language (nxdl) format and vice-versa. | | [📦](https://pypi.org/project/nyaml/) |

