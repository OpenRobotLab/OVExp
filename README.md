<br>
<p align="center">
<h1 align="center"><strong>OVExp: Open Vocabulary Exploration for Object-Oriented Navigation</strong></h1>
  <p align="center">
  	<!-- <strong>/strong> -->
	<br>
    <a href='https://github.com/kellyiss' target='_blank'>Meng Wei</a>&emsp;
	<a href='https://tai-wang.github.io/' target='_blank'>Tai Wang</a>&emsp;
    <a href='https://yilunchen.com/about/' target='_blank'>Yilun Chen</a>&emsp;
    <a href='https://hanqingwangai.github.io/' target='_blank'>Hanqing Wang</a>&emsp;
    <a href='https://oceanpang.github.io/' target='_blank'>Jiangmiao Pang*</a>&emsp;
	<a href='https://xh-liu.github.io//' target='_blank'>Xihui Liu*</a>&emsp;
    <br>
    The University of Hong Kong&emsp;Shanghai AI Laboratory
    <br>
  </p>
</p>


<div id="top" align="center">

[![arXiv](https://img.shields.io/badge/arXiv-2407.09016-blue)](http://arxiv.org/abs/2407.09016)
[![](https://img.shields.io/badge/Paper-%F0%9F%93%96-blue)](assets/OVEXP.pdf)
[![](https://img.shields.io/badge/Project-%F0%9F%9A%80-blue)](https://ovexp.github.io/)

</div>


## 🏠 About
<!-- ![Teaser](assets/teaser.jpg) -->

<div style="text-align: center;">
    <img src="assets/teaser.png" alt="Dialogue_Teaser" width=100% >
</div>
Object-oriented embodied navigation aims to locate specific objects, defined by
category or depicted in images. Existing methods often struggle to generalize to
open vocabulary goals without extensive training data. We introduce OVExp, a
learning-based framework that integrates VLMs for Open-Vocabulary Exploration.
The simple but effective design of OVExp significantly reduces computational costs
and demonstrates strong generalization abilities to various navigation settings.
Experiments on established benchmarks show OVExp outperforms previous zero-
shot methods, can generalize to diverse scenes, and handle different goal modalities 

## 📦 Method Overview
<p align="center">
  <img src="assets/overview.png" align="center" width="80%">
</p>
The proposed OVExp framework mainly consists of three modules: (1) The
Transferable Vision and Language Mapping module for constructing a visual/language memory
map to comprehend the scene holistically. (2) The Goal-Conditioned Exploration Policy module for
learning scene priors from the map representations and predicting the long-term goal location with a
goal-conditioned exploration network. (3) The Local Policy module for analytical planning which
determines the next waypoint towards the predicted long-term goal.

## 📝 TODO List

- \[ \] Release Semantic Map Dataset and Code for Training the Goal-Conditioned Exploration Policy .
- \[ \] Release Inference Code for Object-Goal Navigation on HM3D and MP3D.
- \[ \] Release Inference Code for InstanceImage-Goal Navigation on HM3D.

## 📄 License

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/80x15.png" /></a>
<br />
This work is under the <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

## 👏 Acknowledgements

This repository benefits significantly from the contributions and resources of [home-robot](https://github.com/facebookresearch/home-robot), [PEANUT](https://github.com/ajzhai/PEANUT), [PONI](https://github.com/srama2512/PONI). 