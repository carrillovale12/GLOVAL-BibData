# GLOVAL-BibData

**A Python library for bibliometric analysis of Scopus and Web of Science databases.**

GLOVAL-BibData is a Python library designed to support bibliometric research through the integration, processing, analysis, and visualization of bibliographic records retrieved from Web of Science (WoS) and Scopus.

The library provides tools for database standardization, duplicate detection, PRISMA flow diagrams, exploratory analysis, bibliometric indicators, and graphical representations of scientific production and research collaboration.

The package is distributed as a compiled Python wheel. Its source code is not publicly distributed.

## Main Features

GLOVAL-BibData provides tools for:

- **Bibliographic database processing:** Reading, cleaning, standardizing, and integrating records from Web of Science and Scopus.
- **Duplicate detection:** Identifying and removing duplicate records based on DOI and title.
- **PRISMA diagrams:** Generating PRISMA flow diagrams to support systematic reviews.
- **Exploratory analysis:** Processing bibliographic information and exploring research variables.
- **Bibliometric analysis:** Analyzing scientific production, keywords, journals, authors, institutions, and countries.
- **Keyword analysis:** Exploring keyword frequency, cumulative production, bursts, and word clouds.
- **Scientific collaboration:** Analyzing cooperation relationships between countries, institutions, and other research entities.
- **Data visualization:** Creating bar plots, area plots, network visualizations, Sankey diagrams, and other bibliometric graphics.

## Installation

GLOVAL-BibData is distributed through precompiled wheel files available in the GitHub Releases section.

### Requirements

The current release requires:

- Python 3.13
- Linux x86_64 architecture

### Install from GitHub

Install the package directly using:

```python
%pip install https://github.com/carrillovale12/GLOVAL-BibData/releases/download/v0.1.0/gloval_bibdata-0.1.0-cp313-cp313-linux_x86_64.whl
```

After installation, restart the Python runtime if requested.

### Import the library

```python
from gloval_bibdata import (
    ReadDatabase,
    GlovalBibData,
    MergeDatabase,
    delete_duplicates,
    Prisma,
    ExploratoryAnalysis,
    donutplot,
    BarPlots,
    stacked_line_plot,
    AreaPlots,
    CumulativeKeywords,
    KeywordBursts,
    KeywordWordCloud,
    ProductionByYear,
    CooperationRelationships,
    SankeyFlows
)
```

## Google Colab Tutorial

A public Google Colab notebook is available to guide users through the installation and use of GLOVAL-BibData.

The notebook includes installation instructions, bibliographic database preparation, database integration and cleaning, PRISMA diagrams, bibliometric analysis, and visualization examples.

**[Open GLOVAL-BibData in Google Colab](https://colab.research.google.com/github/carrillovale12/GLOVAL-BibData/blob/main/GLOVAL_BibData.ipynb)**

Users can run the notebook in Google Colab without installing Python locally.

## SCImago Journal Rank Dataset

The `scimagojr_2025_area.csv` file is a dataset compiled and prepared for GLOVAL-BibData using publicly available information from SCImago Journal Rank (SJR).

- **Source:** SCImago Journal Rank
- **Data year:** 2025
- **File format:** CSV
- **Delimiter:** Semicolon (`;`)

This dataset is used by the `GlovalBibData.process_data()` function to support the classification and processing of bibliographic records.

The dataset is available in the repository under the `data/scimagojr_2025_area.csv` directory.

## Version and Compatibility

| Information | Details |
|---|---|
| Package | GLOVAL-BibData |
| Current release | 0.1.0 |
| Python version | 3.13 |
| Platform | Linux x86_64 |
| Distribution | Compiled wheel (.whl) |

The current wheel is built specifically for Python 3.13 on Linux x86_64. Compatibility with other Python versions and operating systems is not guaranteed.

## License

GLOVAL-BibData is distributed under a proprietary academic and non-commercial use license.

The license permits use for academic research and educational purposes, subject to its terms and conditions.

Commercial use, modification, redistribution, and other uses not expressly permitted require prior written authorization from the authors.

See the [LICENSE](LICENSE) file for the complete terms.

## Citation

If you use GLOVAL-BibData in academic research, publications, theses, or other scientific outputs, please acknowledge and cite the software.

A DOI will be provided through Zenodo once the repository has been connected and the software release has been archived.

## Authors

**Gloria Gómez**  
Email: gloriagomezosorio@gmail.com  
ORCID: [0009-0000-0704-5250](https://orcid.org/0009-0000-0704-5250)

**Valentina Carrillo**  
Email: carrillo.vale@gmail.com  
ORCID: [0009-0003-6923-0402](https://orcid.org/0009-0003-6923-0402)

## Repository and Releases

- **GitHub repository:** [GLOVAL-BibData](https://github.com/carrillovale12/GLOVAL-BibData)
- **GitHub Releases:** [Available versions](https://github.com/carrillovale12/GLOVAL-BibData/releases)
- **Google Colab tutorial:** [Open notebook](https://colab.research.google.com/github/carrillovale12/GLOVAL-BibData/blob/main/GLOVAL_BibData.ipynb)

---

Copyright © 2026 Gloria Gómez and Valentina Carrillo. All rights reserved.
