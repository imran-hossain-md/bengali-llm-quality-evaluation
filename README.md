# Bengali LLM Quality Evaluation Study

**Bangladesh Locale — Independent Human Evaluation**

**MD. IMRAN HOSSAIN (IMH)**
Independent Human Evaluator | Bengali LLM Quality Evaluation

## Project Overview

This repository documents an independent, self-directed human evaluation of **50 Bengali LLM outputs** conducted to assess linguistic, contextual, instructional, and cultural quality within a **Bangladesh linguistic and cultural context**.

The study uses a structured QA framework to identify substantive and non-material issues and to document evaluation rationale, error categories, severity, corrections, and pass/fail outcomes.

## Evaluation Snapshot

| Metric                |   Result |
| --------------------- | -------: |
| Evaluation cases      |       50 |
| Evaluation categories |       10 |
| Pass                  | 44 (88%) |
| Fail                  |  6 (12%) |
| Major failures        |        2 |
| Minor issues          |        8 |

## Model & Evaluation Context

* **Model:** Gemini Web — “3.6 Flash”
* **Evaluation date:** 1 October 2026
* **Language:** Bengali
* **Locale:** Bangladesh
* **Evaluator:** MD. IMRAN HOSSAIN (IMH)

Five controlled prompts were evaluated in each of the following 10 categories:

1. Grammar
2. Spelling
3. Bangladesh Localization
4. Bangladesh vs. West Bengal
5. Translation Fidelity
6. Meaning Preservation
7. Factuality
8. Instruction Following
9. Tone/Register
10. Formatting/Terminology

## Methodology

Each output was evaluated using a documented error taxonomy and severity framework.

The evaluation framework:

* Distinguishes source-text errors from model errors.
* Recognizes legitimate variation in Bengali phrasing.
* Does not treat stylistic preference alone as a model error.
* Assesses Bangladesh-specific linguistic and cultural context where relevant.
* Records error category and severity when an issue is identified.
* Uses corrected versions where substantive correction is required.
* Uses Pass/Fail to reflect the material outcome of the assigned task.
* Maintains reproducibility notes for the evaluation setup.

### Evaluation Workflow

```text
Prompt
  ↓
Model Output
  ↓
Error Identification
  ↓
Error Category
  ↓
Severity Assessment
  ↓
Evaluation Rationale
  ↓
Corrected Version
  ↓
Pass / Fail
```

## Key Findings

The evaluation produced **44 Pass and 6 Fail cases**.

All sampled cases in the following categories passed:

* Grammar
* Spelling
* Bangladesh Localization
* Factuality
* Instruction Following
* Meaning Preservation

The identified failures included issues involving:

* Bangladesh–West Bengal cultural overgeneralization
* Translation naturalness and fidelity
* Formal Bengali fluency
* Contextual and semantic alignment
* Tone and register
* Terminology consistency

The findings illustrate that Bengali LLM quality assessment requires more than surface-level grammar and spelling checks. **Localization, semantic precision, register, cultural context, and instruction fidelity** can require human judgment.

## Representative Cases

| Case    | Issue Identified                                   |
| ------- | -------------------------------------------------- |
| BQA-018 | Bangladesh–West Bengal cultural overgeneralization |
| BQA-022 | Unnatural primary translation                      |
| BQA-041 | Formal Bengali fluency and redundancy              |
| BQA-043 | Contextual/semantic mismatch                       |
| BQA-045 | Tone shift from request to mandatory instruction   |
| BQA-047 | Terminology consistency issue                      |

Detailed analysis of representative cases is provided in the repository materials.

## Repository Contents

### Reports

* `report/Bangladesh_Locale_Final_Evaluation_Report.pdf`
* `report/Bangladesh_Locale_Portfolio_Project_Overview.pdf`

### Methodology

* `methodology/evaluation-rubric.md`

### Representative Cases

* `examples/representative-cases.md`

### Public Demonstration Dataset

* `dataset/Bengali_LLM_Evaluation_Synthetic_Demo_Dataset.xlsx`

> **Data note:** The public demonstration dataset is synthetic and is intended to demonstrate the evaluation framework and data structure. It does not represent additional empirical model results or reproduce the complete underlying evaluation dataset.

## Deliverables

* 50-case evaluation dataset
* Final evaluation report
* Portfolio project overview
* Representative case analysis
* Evaluation methodology and rubric
* Reproducibility record
* Synthetic public demonstration dataset

## Scope & Limitations

This is an **independent portfolio evaluation**, not a formal benchmark or externally commissioned study.

The findings are limited to the selected prompts, model output set, evaluation rubric, and evaluation date. The results should therefore not be interpreted as a general performance ranking of Bengali LLMs.

The public repository intentionally separates demonstration materials from the complete underlying evaluation data.

## Evaluator Profile

**MD. IMRAN HOSSAIN (IMH)** is a Bengali language professional with experience in editorial review, documentation, data analysis, AI governance, AI auditing, and independent LLM evaluation.

Relevant evaluation experience includes:

* Bengali LLM quality evaluation
* Bangladesh localization and cultural-context review
* Translation fidelity and meaning preservation
* Tone/register and terminology assessment
* Structured rubric-based evaluation
* Error categorization and severity assessment
* AI safety and robustness test-set development

The LLM evaluation work presented here is **independent project experience**, not prior paid AI-evaluator employment.

## Contact

**MD. IMRAN HOSSAIN (IMH)**
Bogura, Bangladesh

* Email: [imran.h.adnan@gmail.com](mailto:imran.h.adnan@gmail.com)
* LinkedIn: https://www.linkedin.com/in/hossain-imran-md/
* GitHub: https://github.com/imran-hossain-md/bengali-llm-quality-evaluation

---

**Independent portfolio project | Bengali LLM quality evaluation | Bangladesh locale | 1 October 2026**
