# ADeLe practical session — classroom subset

Data and notebook for the AI Evaluation practical session at <https://ai-evaluation.org>.

**Goal:** build a per-LLM instance-level **assessor** that predicts whether the LLM gets each instance right, then improve it beyond the paper baseline — either by engineering richer input features or by changing the assessor architecture.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lexzhou/ADeLe-practical-session/blob/main/ADeLe_student_practical.ipynb)

## Contents

- `ADeLe_student_practical.ipynb` — the Colab notebook for the practical.
- `o1_re=low.csv` — instance-level annotations + verification labels for OpenAI o1 (reasoning_effort=low), one of the 15 LLMs in the ADeLe paper.
- `rubrics/` — text descriptions of the 19 ADeLe demand-level rubrics.

## Provenance

This is a one-subject classroom subset of the full ADeLe v1.0 release. For all 15 subjects, all benchmarks, and the full code, see the upstream repo: <https://github.com/Kinds-of-Intelligence-CFI/ADeLe-AIEvaluation> (and the dataset on [HuggingFace](https://huggingface.co/datasets/CFI-Kinds-of-Intelligence/ADeLe_battery_v1dot0)).

## Citation

```bibtex
@article{zhou2026general,
  title={General Scales Unlock AI Evaluation with Explanatory and Predictive Power},
  author={Zhou, Lexin and Pacchiardi, Lorenzo and Mart{\'i}nez-Plumed, Fernando and Collins, Katherine M. and Moros-Daval, Yael and Zhang, Seraphina and Zhao, Qinlin and Huang, Yitian and Sun, Luning and Prunty, Jonathan E. and Li, Zongqian and S{\'a}nchez-Garc{\'i}a, Pablo and Chen, Kexin Jiang and Casares, Pablo A. M. and Zu, Jiyun and Burden, John and Mehrbakhsh, Behzad and Stillwell, David and Cebrian, Manuel and Wang, Jindong and Henderson, Peter and Wu, Sherry Tongshuang and Kyllonen, Patrick C. and Cheke, Lucy and Xie, Xing and Hern{\'a}ndez-Orallo, Jos{\'e}},
  journal={Nature},
  year={2026},
  doi={10.1038/s41586-026-10303-2},
  url={https://www.nature.com/articles/s41586-026-10303-2}
}
```

## Licenses

- Code (`ADeLe_student_practical.ipynb`): MIT — see `LICENSE`.
- Data (`o1_re=low.csv`) and rubrics (`rubrics/*.txt`): CC-BY-SA-4.0, inherited from the upstream ADeLe v1.0 dataset. Attribution: Zhou et al., 2026 (see Citation above).
