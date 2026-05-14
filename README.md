# CPQL: Peng's Q(λ) for Conservative Value Estimation in Offline Reinforcement Learning

[![arXiv](https://img.shields.io/badge/arXiv-2210.07105-b31b1b.svg)](https://arxiv.org/abs/2210.07105)

🧵 This paper introduces CPQL: Conservative Peng's Q($\lambda$), mitigates overly-pessimistic value estimation, achieves the performance greater than (or equal to) that of the behavior policy, and provides near-optimal performance guarantees. Code is heavily inspired by [CORL](https://github.com/tinkoff-ai/CORL) for offlilne RL codebase.<br/>

## Getting started

```bash
git clone https://github.com/tinkoff-ai/CORL.git && cd CORL
pip install -r requirements/requirements_dev.txt

# alternatively, you could use docker
docker build -t <image_name> .
docker run --gpus=all -it --rm --name <container_name> <image_name>
```


## Citing CORL

If you use CORL in your work, please use the following bibtex
```bibtex
@inproceedings{
tarasov2022corl,
  title={{CORL}: Research-oriented Deep Offline Reinforcement Learning Library},
  author={Denis Tarasov and Alexander Nikulin and Dmitry Akimov and Vladislav Kurenkov and Sergey Kolesnikov},
  booktitle={3rd Offline RL Workshop: Offline RL as a ''Launchpad''},
  year={2022},
  url={https://openreview.net/forum?id=SyAS49bBcv}
}
```
