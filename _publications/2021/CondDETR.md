---
title:          "Conditional DETR for Fast Training Convergence"
date:           2021-7-14 00:00:00 +0800
selected:       true
pub:            "International Conference on Computer Vision (ICCV)"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2021"

abstract: >-
  <details class="pub-abstract">
    <summary>Abstract</summary>
    <div class="abstract-content" style="margin-top:">
    We solve the slow convergence of Detection Transformer (DETR) with our Conditional Spatial Query method. DETR converges slowly because it struggles to find key extremity regions of an object (e.g., an elephant's feet, back, or trunk), which are vital for accurate localization and recognition. Our method explicitly finds these extremity regions in space, constrains the search area, and speeds up DETR's convergence by 6-10x. This was one of the first works to address DETR's slow training, inspiring many later algorithms like DAB-DETR and DINO.
    </div>
  </details>

cover: /_publications/2021/CondDETR.png
authors:
  - Xiaokang Chen*
  - Depu Meng*
  - Zejia Fan
  - Gang Zeng
  - Houqiang Li, 
  - Yuhui Yuan, 
  - Lei Sun
  - Jingdong Wang
links:
  Paper: https://arxiv.org/abs/2108.06152
  Code: https://git.io/ConditionalDETR
  中文解读: https://zhuanlan.zhihu.com/p/401916664
---
