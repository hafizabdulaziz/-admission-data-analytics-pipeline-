# Admission Data Analytics Pipeline

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Logic: Analytics](https://img.shields.io/badge/Logic-Analytics-red?style=for-the-badge)
![Process: Spec-Driven](https://img.shields.io/badge/Process-Spec--Driven-green?style=for-the-badge)

An automated academic data analytics pipeline for student eligibility validation, criterion filtering, and admission records persistence.

## Overview

The Admission Data Analytics Pipeline evaluates applicant qualifications against institutional academic criteria across distinct departmental faculties (such as Engineering and Medical). Utilizing structured Python data structures and spec-driven logic, the pipeline screens credentials, checks prerequisites, and archives candidate outcomes.

## Key Features

- **Departmental Criterion Filtering**: Categorizes and sorts candidates according to declared departmental preferences and calculated merit thresholds.
- **Automated Eligibility Verification**: Validates academic prerequisites including minimum percentage marks, mandatory subject combinations, and age boundaries.
- **Defensive Input Validation**: Protects against malformed applicant records, missing fields, and type discrepancies.
- **Record Persistence**: Serializes candidate outcomes and evaluation metrics to structured files for auditing and downstream reporting.

## Technology Stack

- **Language**: Python
- **Standard Library Modules**: `json` (data persistence), `os`, `sys`
- **Methodology & Pattern**: Spec-Driven Architecture

## Setup & Local Execution

### Prerequisites
- Python 3.8+

### Execution Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/hafizabdulaziz/-admission-data-analytics-pipeline-.git
   cd -admission-data-analytics-pipeline-
   ```

2. **Execute the Analytics Engine**:
   ```bash
   python admission_analyzer.py
   ```

---

<p align="center">Part of the <a href="https://github.com/hafizabdulaziz">AI-Native Developer Portfolio</a> by Abdul Aziz</p>
