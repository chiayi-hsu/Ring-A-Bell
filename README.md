# Ring-A-Bell


Code for reproducing the results in the paper "Ring-A-Bell! How Reliable are Concept Removal Methods For Diffusion Models?".

## Framework of Ring-A-Bell
![image](https://github.com/chiayi-hsu/Ring-A-Bell/blob/main/model_architecture.png)

### 📌 Concept Extraction
The code of **Concept Extraction** is in ```Get_Concept_Vector.ipynb```.
### 📌 Prompt Discovery
The code of **Prompt Discovery** is in ```InversePrompt.ipynb```.
<br>
<br>
You can get the problematic prompts after you conduct ```InversePrompt.ipynb```. Then you can use problematic prompts to evaluate the effectiveness of the concept removal methods.
<br>
<br>

## Citation
Please feel free to email us at ```chiayihsu8315@gmail.com```. If this work is useful in your own research, please consider citing our work!
```
@inproceedings{
ringabell,
title={Ring-A-Bell! How Reliable are Concept Removal Methods For Diffusion Models?},
author={Yu-Lin Tsai*, Chia-Yi Hsu*, Chulin Xie, Chih-Hsun Lin, Jia-You Chen, Bo Li, Pin-Yu Chen, Chia-Mu Yu, Chun-Ying Huang},
booktitle={The Twelfth International Conference on Learning Representations},
year={2024},
url={https://openreview.net/forum?id=lm7MRcsFiS}
}
```
