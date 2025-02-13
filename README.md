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

## Run Training

All experiments were conducted on a 4×H100 setup, each with 80GB of memory.  

### LoRA Training  
- Training examples can be found in the `weak-to-strong-preference-optimization/examples/train_lora` folder.  

### Full Fine-Tuning  
To set up the environment, install the required dependencies:  
```bash
pip install deepspeed==0.15.4
pip install transformers==4.45.0
```  
- Training examples are available in the `weak-to-strong-preference-optimization/examples/train_full` folder.  

The trained models will be uploaded in the coming days.

## Performance

<img src="./img/performance.png" style="zoom:50%;" />


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

