# Perceptual Contrast Stretching on Target Feature for Speech Enhancement
**This is the post-processing PCS part.**  
  
Enhanced audios are generated by different baseline models to which post-processing PCS is then applied.  
The experimental results are as follows:  
<img src="https://github.com/RoyChao19477/PCS/blob/main/imgs/Post-processing%20PCS.png" height="324">

#### catalog
[Introduction](#introduction)  
[PCS-tools](#pcs-tools)  
[SpeechMetrics-tools](#scoring-tools)  
[Citation](#citation)  
[References](#reference)  

<a name="headers"/>

## Introduction
"PCS is derived based on the critical band importance function and applied to modify the targets of the SE model."  
"It can also be used as a post-processing (PP) method to further sharpen the structure of enhanced speech and suppress residual noise."  
  
More details can be found in here: [**http://arxiv.org/abs/2203.17152**](http://arxiv.org/abs/2203.17152)
  
**This repo is only dedicated to the post processing PCS.**  
<img src="https://github.com/RoyChao19477/PCS/blob/main/imgs/spec.png" height="172">  

## PCS-tools
Post-processing PCS tools can be found at `/PCS`. So you can simply post-process the audio with PCS.  

## Scoring-tools
Speech metric scores were computed with `/speech_metrics`.

## Citation:
If you find the code useful in your research, please cite:
> Waiting for google scholar ...  
``
@article{}  
``
arXiv : https://arxiv.org/pdf/2203.17152

## Reference:
#### SEGAN: 
arXiv: https://arxiv.org/pdf/1703.09452.pdf
<!-- 
```
@article{pascual2017segan,
  title={SEGAN: Speech enhancement generative adversarial network},
  author={Pascual, Santiago and Bonafonte, Antonio and Serra, Joan},
  journal={arXiv preprint arXiv:1703.09452},
  year={2017}
}
```
-->

#### Wiener filter:
wikipedia: https://en.wikipedia.org/wiki/Wiener_filter
<!-- 
```
@article{brown1997introduction,
  title={Introduction to random signals and applied Kalman filtering: with MATLAB exercises and solutions},
  author={Brown, Robert Grover and Hwang, Patrick YC},
  journal={Introduction to random signals and applied Kalman filtering: with MATLAB exercises and solutions},
  year={1997}
}
```
-->

#### Transformer T(c) / T(nc)
arXiv: https://arxiv.org/pdf/2006.10296.pdf
<!-- 
```
@inproceedings{fu2020boosting,
  title={Boosting objective scores of a speech enhancement model by metricgan post-processing},
  author={Fu, Szu-Wei and Liao, Chien-Feng and Hsieh, Tsun-An and Hung, Kuo-Hsuan and Wang, Syu-Siang and Yu, Cheng and Kuo, Heng-Cheng and Zezario, Ryandhimas E and Li, You-Jin and Chuang, Shang-Yi and others},
  booktitle={2020 Asia-Pacific Signal and Information Processing Association Annual Summit and Conference (APSIPA ASC)},
  pages={455--459},
  year={2020},
  organization={IEEE}
}
```
-->

#### CRNN
arXiv: https://arxiv.org/pdf/1805.00579.pdf
<!-- 
```
@inproceedings{zhao2018convolutional,
  title={Convolutional-recurrent neural networks for speech enhancement},
  author={Zhao, Han and Zarar, Shuayb and Tashev, Ivan and Lee, Chin-Hui},
  booktitle={2018 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)},
  pages={2401--2405},
  year={2018},
  organization={IEEE}
}
```
-->

#### MetricGAN+
arXiv: https://arxiv.org/pdf/2104.03538.pdf  
From SpeechBrain: https://huggingface.co/speechbrain/metricgan-plus-voicebank
<!-- 
```
@article{fu2021metricgan+,
  title={Metricgan+: An improved version of metricgan for speech enhancement},
  author={Fu, Szu-Wei and Yu, Cheng and Hsieh, Tsun-An and Plantinga, Peter and Ravanelli, Mirco and Lu, Xugang and Tsao, Yu},
  journal={arXiv preprint arXiv:2104.03538},
  year={2021}
}
```
-->

#### DPT-FSNet:
arXiv: https://arxiv.org/pdf/2104.13002.pdf  
Reproduced and denoted as DPT\*
<!-- 
```
@article{dang2021dpt,
  title={DPT-FSNet: Dual-path Transformer Based Full-band and Sub-band Fusion Network for Speech Enhancement},
  author={Dang, Feng and Chen, Hangting and Zhang, Pengyuan},
  journal={arXiv preprint arXiv:2104.13002},
  year={2021}
}
```
-->
