# WSPO

This is the official implementation of WSPO algorithm. 

<img src="./img/pipeline.png" style="zoom:50%;" />

## Installation

```bash
conda create -n wspo python=3.10
conda activate wspo
cd weak-to-strong-preference-optimization
pip install -e ".[torch,metrics]"
```


## Citation

```
@inproceedings{
zhu2025weaktostrong,
title={Weak-to-Strong Preference Optimization: Stealing Reward from Weak Aligned Model},
author={Wenhong Zhu and Zhiwei He and Xiaofeng Wang and Pengfei Liu and Rui Wang},
booktitle={The Thirteenth International Conference on Learning Representations},
year={2025},
url={https://openreview.net/forum?id=f7KxfUrRSb}
}
```


## Acknowledgments

- We run our experiments based on [LLama-Factory](https://github.com/hiyouga/LLaMA-Factory).

