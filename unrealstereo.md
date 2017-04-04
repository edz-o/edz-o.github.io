---
layout: default
---

<h1 id="unrealstereo-a-synthetic-dataset-for-analyzing-stereo-vision" align="center"><strong>UnrealStereo: A Synthetic Dataset for Analyzing Stereo Vision</strong></h1>

<div>
<img src="/images/img_grad.jpg" width = "100%" height = "" alt="UnrealStereo" align="center" />
</div>

### **Abstract**
<small>Stereo algorithm is important for robotics applications, such as quadcopter and autonomous driving. It needs to be robust enough to handle images of challenging conditions, such as raining or strong lighting. Textureless and specular regions of these images make feature matching difficult and smoothness assumption invalid. It is important to understand whether an algorithm is robust to these hazardous regions. Many stereo benchmarks have been developed to evaluate the performance and track progress. But it is not easy to quantize the effect of these hazardous regions. In this paper, we develop a synthetic image generation tool and build a benchmark with synthetic images. First, we manually tweak hazardous factors in a virtual world, such as making objects more specular or transparent, to simulate corner cases to test the robustness of stereo algorithms. Second, we use ground truth information, such as object mask, material property, to automatically identify hazardous regions and evaluate the accuracy of these regions. Our tool is based on a popular game engine Unreal Engine 4 and will be open-source. Many publicly available realistic game contents can be used by our tool which can provide an enormous resource for algorithm development and evaluation.</small>

### **Paper**
>*UnrealStereo: A Synthetic Dataset for Analyzing Stereo Vision*  
>Yi Zhang, Weichao Qiu, Qi Chen, Xiaolin Hu, and Alan Yuille  
>Technical report, Dec. 2016  
>[arXiv](https://arxiv.org/abs/1612.04647)

### **Dataset**
- Six publicly available game scenes including **a small indoor room**, **a large temple scene**, **three houses** and **one block of street**. Different layouts in these houses such as living room, kitchen and bathroom. 

- The largest scene contains more than **1,000 objects** while hundreds on average, including those with **high reflectance** such as mirrors, bathtubs and metal statues, **transparent objects** such as glass, glassdoors and windows. **Subtle visual effects** are included, e.g. leather sofa and the specular surface of a TV. 

- Rich groundtruth including **disparity**, **instance segmentation**, **hazardous regions** can be generated automatically using our tool.

#### **Screenshot**

<div>
<table border="0" cellspacing="0" cellpadding="0">
  <tr align="center"><td><b>Left Image</b></td><td><b>Disparity</b></td><td><b>Object mask</b></td><td><b>Hazardous Regions</b></td></tr>
  <tr><td><img src="/images/arch1_913_270_sup_imL.png" width = "100%" height = "" alt="arch1_imL" align="center" /></td>
  <td><img src="/images/arch1_913_270_sup_disp.png" width = "100%" height = "" alt="arch1_disp" align="center" /></td>
  <td><img src="/images/arch1_913_270_sup_obj.png" width = "100%" height = "" alt="arch1_obj" align="center" /></td>
  <td><img src="/images/arch1_913_270_sup_hazard.png" width = "100%" height = "" alt="arch1_hazard" align="center" /></td></tr>

  <tr><td><img src="/images/arch1_913_806_sup_imL.png" width = "100%" height = "" alt="arch1_imL" align="center" /></td>
  <td><img src="/images/arch1_913_806_sup_disp.png" width = "100%" height = "" alt="arch1_disp" align="center" /></td>
  <td><img src="/images/arch1_913_806_sup_obj.png" width = "100%" height = "" alt="arch1_obj" align="center" /></td>
  <td><img src="/images/arch1_913_806_sup_hazard.png" width = "100%" height = "" alt="arch1_hazard" align="center" /></td></tr>

  <tr><td><img src="/images/arch2_1071_403_sup_imL.png" width = "100%" height = "" alt="arch1_imL" align="center" /></td>
  <td><img src="/images/arch2_1071_403_sup_disp.png" width = "100%" height = "" alt="arch1_disp" align="center" /></td>
  <td><img src="/images/arch2_1071_403_sup_obj.png" width = "100%" height = "" alt="arch1_obj" align="center" /></td>
  <td><img src="/images/arch2_1071_403_sup_hazard.png" width = "100%" height = "" alt="arch1_hazard" align="center" /></td></tr>

  <tr><td><img src="/images/arch2_1071_526_sup_imL.png" width = "100%" height = "" alt="arch1_imL" align="center" /></td>
  <td><img src="/images/arch2_1071_526_sup_disp.png" width = "100%" height = "" alt="arch1_disp" align="center" /></td>
  <td><img src="/images/arch2_1071_526_sup_obj.png" width = "100%" height = "" alt="arch1_obj" align="center" /></td>
  <td><img src="/images/arch2_1071_526_sup_hazard.png" width = "100%" height = "" alt="arch1_hazard" align="center" /></td></tr>

  <tr><td><img src="/images/arch2_highpos_1071_285_sup_imL.png" width = "100%" height = "" alt="arch1_imL" align="center" /></td>
  <td><img src="/images/arch2_highpos_1071_285_sup_disp.png" width = "100%" height = "" alt="arch1_disp" align="center" /></td>
  <td><img src="/images/arch2_highpos_1071_285_sup_obj.png" width = "100%" height = "" alt="arch1_obj" align="center" /></td>
  <td><img src="/images/arch2_highpos_1071_285_sup_hazard.png" width = "100%" height = "" alt="arch1_hazard" align="center" /></td></tr>

  <tr><td><img src="/images/arch3_highpos_1851_1349_sup_imL.png" width = "100%" height = "" alt="arch1_imL" align="center" /></td>
  <td><img src="/images/arch3_highpos_1851_1349_sup_disp.png" width = "100%" height = "" alt="arch1_disp" align="center" /></td>
  <td><img src="/images/arch3_highpos_1851_1349_sup_obj.png" width = "100%" height = "" alt="arch1_obj" align="center" /></td>
  <td><img src="/images/arch3_highpos_1851_1349_sup_hazard.png" width = "100%" height = "" alt="arch1_hazard" align="center" /></td></tr>

  <tr><td><img src="/images/rr_573_120_sup_imL.png" width = "100%" height = "" alt="arch1_imL" align="center" /></td>
  <td><img src="/images/rr_573_120_sup_disp.png" width = "100%" height = "" alt="arch1_disp" align="center" /></td>
  <td><img src="/images/rr_573_120_sup_obj.png" width = "100%" height = "" alt="arch1_obj" align="center" /></td>
  <td><img src="/images/rr_573_120_sup_hazard.png" width = "100%" height = "" alt="arch1_hazard" align="center" /></td></tr>

  <tr><td><img src="/images/suntemple_850_167_sup_imL.png" width = "100%" height = "" alt="arch1_imL" align="center" /></td>
  <td><img src="/images/suntemple_850_167_sup_disp.png" width = "100%" height = "" alt="arch1_disp" align="center" /></td>
  <td><img src="/images/suntemple_850_167_sup_obj.png" width = "100%" height = "" alt="arch1_obj" align="center" /></td>
  <td><img src="/images/suntemple_850_167_sup_hazard.png" width = "100%" height = "" alt="arch1_hazard" align="center" /></td></tr>

  <tr><td><img src="/images/urbancity_1732_618_sup_imL.png" width = "100%" height = "" alt="arch1_imL" align="center" /></td>
  <td><img src="/images/urbancity_1732_618_sup_disp.png" width = "100%" height = "" alt="arch1_disp" align="center" /></td>
  <td><img src="/images/urbancity_1732_618_sup_obj.png" width = "100%" height = "" alt="arch1_obj" align="center" /></td>
  <td><img src="/images/urbancity_1732_618_sup_hazard.png" width = "100%" height = "" alt="arch1_hazard" align="center" /></td></tr>

</table>
</div>

#### **Compiled Games**
  Pre-compiled game binaries can be found [here](#).

#### **Data generation**
> Data generation tool coming soon.
