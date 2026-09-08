## **The `data-adhd-psyctr` dataset** 📊

[<img src="https://img.shields.io/badge/DOI-10.5281%2Fzenodo.22663728-blue">](https://doi.org/10.5281/zenodo.22663728)

The `data-adhd-psyctr` dataset is a **meta-analytic research domain** (MARD; see the [MARD framework paper](https://docs.metapsy.org/uploads/ebmental-2022-300509.pdf)), part of the [Metapsy project](https://www.metapsy.org/). It contains study information and effect size data from **randomized trials on behavioral parent or teacher training** for children and adolescents with ADHD **under the age of 18 years** ([Hornstra et al., 2022](https://acamh.onlinelibrary.wiley.com/doi/full/10.1111/camh.12561)).

The dataset includes studies that compared **parent or teacher training** with a control condition, as well as studies that compared a **multimodal intervention** (i.e., a combination of parent, teacher, and/or child training) with a control condition. Reported outcomes (`outcome_category`) are **total ADHD symptoms**, **separate symptoms of inattention and hyperactivity/impulsivity**, and **behavioral problems** (symptoms of oppositional defiant disorder or conduct disorder).

The following rules were applied during data extraction:

- When **no total ADHD symptom score** was available, the separate inattention and hyperactivity-impulsivity scores were pooled, and this aggregate was used as a measure of total ADHD symptoms.
- When a study had **multiple measurement points**, the outcomes closest to the end date of the intervention were selected.
- When there were **multiple informants**, parent-rated outcomes were selected for parent training and teacher-rated outcomes for teacher training. For multimodal interventions, the rating of the informant with whom most training time was spent was selected.
- When parent-rated outcomes were **reported by both parents**, the mother-reported outcomes were selected to increase comparability across studies.
- When the **same construct was measured multiple times**, the measurement most commonly used across the included studies was selected.

**All data were extracted by two independent reviewers.** Risk of bias assessments were performed by two independent reviewers using the **Cochrane Risk of Bias tool (version 2)**.

The dataset follows the [Metapsy data standard](https://docs.metapsy.org/data-preparation/format/).
