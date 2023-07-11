# toon2face : Inference of U-GAT-IT
## KUBIG 2023 Spring CV 웹툰 가상캐스팅 프로젝트 - 웹툰 실사화 모델 based on U-GAT-IT
---
### Dataset used
- A : 3000 cropped faces from Naver webtoons
- B : 3000 Korean celeb's faces

### Code
**Some alterations have been made to the original code, and minor changes in file `UGATIT.py` will be mandatory**
1. `git clone`

2. Training
```
!python /path/to/code/main.py --dataset /path/to/datasets --phase train --iteration 8000 --batch_size 1 --n_dis 4 --save_freq 1600
```
Enter `--light True` if needed (Takes up a lot of GPU)
  
3. Testing
```
!python /path/to/code/main.py --dataset /path/to/datasets --phase test
```

### Results
[WIP]

### Reference
GitHub :  
[U-GAT-IT, pytorch](https://github.com/taki0112/UGATIT)

- U-GAT-IT: Unsupervised Generative Attentional Networks with Adaptive Layer-Instance Normalization for Image-to-Image Translation
- Junho Kim and Minjae Kim and Hyeonwoo Kang and Kwang Hee Lee
- International Conference on Learning Representations, 2020
- [Paper](https://openreview.net/forum?id=BJlZ5ySKPH)
