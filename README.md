# GLOVAL-BibData

**GLOVAL-BibData** is a Python library designed to support bibliometric analysis and PRISMA-based systematic review workflows. It provides tools to integrate, standardize, clean, and analyze bibliographic records exported in `.bib` format from **Web of Science (WoS)** and **Scopus**.

The library facilitates the creation of unified bibliographic databases, the identification and removal of duplicate records, and the generation of analytical outputs and visualizations to support scientific research.

Developed by **Gloria Gómez and Valentina Carrillo**.

**Version:** 0.1.0

## General Objective

To develop a Python-based toolkit that automates the integration, processing, and bibliometric analysis of bibliographic data from Web of Science and Scopus, while supporting PRISMA-based systematic review workflows in a reproducible and user-friendly environment.

## Main Features

- **Database integration:** Import and standardize bibliographic records from Web of Science and Scopus.
- **Data cleaning:** Process metadata and identify and remove duplicate records.
- **PRISMA workflow:** Support the organization and reporting of records throughout the stages of systematic reviews.
- **Exploratory analysis:** Examine bibliographic metadata and research trends.
- **Bibliometric analysis:** Analyze scientific production, keywords, countries, institutions, and collaboration networks.
- **Data visualization:** Generate graphical representations of bibliometric indicators and relationships.

## Installation

GLOVAL-BibData is distributed as a compiled Python wheel.

**Requirements:**
- Python 3.13
- Linux x86_64 environment (the current binary release)
- Internet connection for installation and dependencies

Install the library using:

```python
!pip install https://github.com/carrillovale12/GLOVAL-BibData/releases/download/v0.1.0
