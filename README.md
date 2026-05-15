# CPQL: Peng's Q(λ) for Conservative Value Estimation in Offline Reinforcement Learning

[![arXiv](https://img.shields.io/badge/arXiv-2605.14779-b31b1b.svg)](https://arxiv.org/abs/2605.14779)

🧵 This paper introduces CPQL: Conservative Peng's Q($\lambda$), mitigates overly-pessimistic value estimation, achieves the performance greater than (or equal to) that of the behavior policy, and provides near-optimal performance guarantees. This codebase is heavily inspired by [CORL](https://github.com/tinkoff-ai/CORL), an offline RL codebase.<br/>

## Getting started

For first-time installation, please follow the installation instructions provided in the [CORL](https://github.com/tinkoff-ai/CORL) GitHub repository.
```bash
git clone https://github.com/tinkoff-ai/CORL.git && cd CORL
pip install -r requirements/requirements_dev.txt
```

## Training
To train d4rl datasets,
```
python algorithms/cpql.py --config configs/cpql/hopper/random_v2.yaml
```

## Citing CORL

If you use CORL in your work, please use the following bibtex
```bibtex
@inproceedings{kim2026peng,
  title={Peng's Q ($$\backslash$lambda $) for Conservative Value Estimation in Offline Reinforcement Learning},
  author={Kim, Byeongchan and Oh, Min-hwan},
  booktitle={The Fourteenth International Conference on Learning Representations},
  year={2026}
}
```
