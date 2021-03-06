 ## Github Repository For CURE
## Regularize The Curvature Of Patch Manifold Via Biharmonic Extension


Code for "CURE: Curvature Regularization Via Weighted Nonlocal BiHarmonic For Missing Data Recovery"

Thanks Prof. Zuoqiang Shi and Dr. Wei Zhu for their code for LDMM and WNLL.

### Requirement: 

- vlfeat-0.9.21 <a href="http://www.vlfeat.org/">download</a>
- matlab2016b+

### Image Inpainting

(Ground Turth, Inpainting, Sample Rate:20%)

<img src="Fig/bar.png" width = "200" height = "140"  /><img src="Fig/bari.png" width = "200" height = "140"  />

(Ground Turth, W-CUBE:28.56dB, WNLL:27.78dB)

<img src="Fig/bar1.png" width = "200" height = "140"  /><img src="Fig/barCUBE.png" width = "200" height = "140"  /><img src="Fig/barWNLL.png" width = "200" height = "140"  />


PSNR

<img src="Inpainting/PSNR.png" width = "600" height = "300"  />

SSIM

<img src="Inpainting/SSIM.png" width = "600" height = "300"  />

### Semi-supervised Learning

In our test, we label 700, 100, 70, 50 and 35 images in MNIST respectively. The labeled images are selected at random in 70,000 images. For each sampling rate, we take 10 different random samples for comparisons.
<center>
<img src="Fig/average.png" width = "300" height = "200"  />
</center>

### Image Denoising

On going work.....


### Cite

```
@article{dong2019cure,
  title={CURE: Curvature Regularization For Missing Data Recovery},
  author={Dong, Bin and Ju, Haocheng and Lu, Yiping and Shi, Zuoqiang},
  journal={arXiv preprint arXiv:1901.09548},
  year={2019}
}
```
