## 📘 Towards Fair Rankings: Leveraging LLMs for Gender Bias Detection and Measurement

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

This repository accompanies the paper **"Towards Fair Rankings: Leveraging LLMs for Gender Bias Detection and Measurement"**, which presents a method for detecting gender bias in documents and introduces a novel fairness evaluation metric for ranking models. It also includes a manually annotated dataset of gender bias for a subset of the MS MARCO Passage Ranking Collection, providing a valuable resource for future research on fairness in information retrieval.

---

## 🔗 Paper

The full paper is available on arXiv: [arXiv:YYYY.NNNNN](https://arxiv.org/abs/YYYY.NNNNN)

---

## 📦 Dataset Overview

🔹 **MSMGenderBias.csv**

- A set of manually annotated passages from the MS MARCO Passage Ranking collection with gender bias labels.
- Fields:
  - doc_id: MS MARCO passage identifier
  - gender_bias: Gender bias label (**N** (Neutral (no bias)), **M** (Male (biased towards male)), **F** (Female (biased towards female)))

**⚠️ Note:** The original MS MARCO dataset is not redistributed here. These files contain only IDs and annotations. You must request access to MS MARCO separately from https://microsoft.github.io/msmarco/.

---

## 📬 Contact

For questions or collaborations, please contact:  
✉️ maryamalsadat.mousavian@usi.ch  
Or open an issue in this repository.

---

## 📚 Citation

If you use this dataset, please cite our paper:  

@inproceedings{mousavian2025towards,  
  title={Towards Fair Rankings: Leveraging LLMs for Gender Bias Detection and Measurement},  
  author={Maryam Mousavian, Zahra Abbasiantaeb, Mohammad Aliannejadi, Fabio Crestani},  
  booktitle={ICTIR},  
  year={2025}  
}

---

## 🙏 Acknowledgments

We thank the MS MARCO team at Microsoft for making their dataset available to the research community.
