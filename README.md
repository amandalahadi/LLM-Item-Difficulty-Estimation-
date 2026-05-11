# LLM-Item-Difficulty-Estimation

This repository contains the dataset and analysis materials for the paper:

**“The Easy Trap: Why LLMs Underestimate Misconception-Driven Difficulty”**

## Overview

This study investigates whether Large Language Models (LLMs) can accurately estimate the empirical difficulty of mathematics items. The analysis focuses on fraction arithmetic items that are procedurally simple but conceptually challenging due to persistent student misconceptions.

Our findings show that LLM-generated difficulty estimates generally align with procedural complexity, but systematically misjudge misconception-driven difficulty in fraction items. We refer to this phenomenon as the **“Easy Trap.”**

## Repository Contents

* `data/`

  * Empirical item difficulty data
  * LLM-generated difficulty estimates
  * Aggregated evaluation results

* `scripts/`

  * Data preprocessing scripts
  * Statistical analysis scripts
  * Visualization scripts

* `figures/`

  * Figures used in the paper/poster

* `results/`

  * Processed outputs and summary tables

## Dataset Description

The dataset contains:

* Item-level empirical difficulty measures
* LLM-generated difficulty predictions
* Fraction and non-fraction arithmetic item labels
* Repeated-run evaluation results for prediction consistency analysis

All shared data have been anonymized and contain no personally identifiable student information.

## Citation

If you use this repository, please cite the associated paper:

```bibtex
@inproceedings{lahadi2026easytrap,
  title={The Easy Trap: Why LLMs Underestimate Misconception-Driven Difficulty},
  author={La Hadi, Amanda and others},
  year={2026}
}
```

## License

This repository is released under the CC BY 4.0 License. Please provide appropriate attribution when using these materials.

## Contact

For questions or collaboration inquiries, please contact:

Amanda La Hadi 
PhD Researcher in Data Science & AI in Education
amanda.lahadi@monash.edu
GitHub: amandalahadi
