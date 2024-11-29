# MultiGO: Towards Multi-Level Geometry Learning for Monocular 3D Textured Human Reconstruction
<center>
<img src="asset/2row_vis_1115.jpg" width="900px">
</center>
The gallery of paper "MultiGO: Towards Multi-Level Geometry Learning for Monocular 3D Textured Human Reconstruction"

# Abstract

This paper investigates the research task of reconstructing the 3D clothed human body from a monocular image. Due to the inherent ambiguity of single-view input, existing approaches leverage pre-trained SMPL(-X) estimation models or generative models to provide auxiliary information for human reconstruction. However, these methods capture only the general human body geometry and overlook specific geometric details, leading to inaccurate skeleton reconstruction, incorrect joint positions, and unclear cloth wrinkles. In response to these issues, we propose a multi-level geometry learning framework. Technically, we design three key components: skeleton-level enhancement, joint-level augmentation, and wrinkle-level refinement modules. Specifically, we effectively integrate the projected 3D Fourier features into a Gaussian reconstruction model, introduce perturbations to improve joint depth estimation during training, and refine the human coarse wrinkles by resembling the de-noising process of diffusion model. Extensive quantitative and qualitative experiments on two out-of-distribution test sets show the superior performance of our approach compared to state-of-the-art (SOTA) methods. 

# Examples of Human Avatar
<center>
<img src="asset/Ours/Ours_ori_custom_049.glb.gif" width="230px"><img src="asset/Ours/Ours_ori_custom_026.glb.gif" width="230px"><img src="asset/Ours/Ours_ori_thuman_003.glb.gif" width="230px"><img src="asset/Ours/Ours_ori_thuman_055.glb.gif" width="230px">


<img src="asset/Ours/Ours_refined_custom_049.obj.gif" width="230px"><img src="asset/Ours/Ours_refined_custom_026.obj.gif" width="230px"><img src="asset/Ours/Ours_refined_thuman_003.obj.gif" width="230px"><img src="asset/Ours/Ours_refined_thuman_055.obj.gif" width="230px">
</center>

# Compared with SOTA Methods
## Comparisons on Textured Human Avatars
<center>
<table align="center">
  <tr align="center">
    <td align="center">
      <img src="asset/Compare/19_gif/0019.png" alt="Input Image" width="250px" style="max-width: 100%;">
      <div><strong>Input Image</strong></div>
    </td>
    <td align="center">
      <img src="asset/Compare/19_gif/Ours_ori_custom_019.glb.gif" alt="MultiGO" width="250px" style="max-width: 100%;">
      <div><strong>MultiGO</strong></div>
    </td>
    <td align="center">
      <img src="asset/Compare/19_gif/SiTH_custom_019.obj.gif" alt="SiTH" width="250px" style="max-width: 100%;">
      <div><strong>SiTH</strong></div>
    </td>
    <td align="center">
      <img src="asset/Compare/19_gif/SiFU_custom_019.obj.gif" alt="SiFU" width="250px" style="max-width: 100%;">
      <div><strong>SiFU</strong></div>
    </td>
  </tr>
  <tr align="center">
    <td align="center">
      <img src="asset/Compare/19_gif/ECON_custom_019.obj.gif" alt="ECON" width="250px" style="max-width: 100%;">
      <div><strong>ECON</strong></div>
    </td>
    <td align="center">
      <img src="asset/Compare/19_gif/ICON_custom_019.obj.gif" alt="ICON" width="250px" style="max-width: 100%;">
      <div><strong>ICON</strong></div>
    </td>
    <td align="center">
      <img src="asset/Compare/19_gif/GTA_custom_019.obj.gif" alt="GTA" width="250px" style="max-width: 100%;">
      <div><strong>GTA</strong></div>
    </td>
    <td align="center">
      <img src="asset/Compare/19_gif/PiFU_custom_039.obj.gif" alt="PiFU" width="250px" style="max-width: 100%;">
      <div><strong>PiFU</strong></div>
    </td>
  </tr>
</table>
</center>


---

<center>
<table align="center">
  <tr align="center"> 
    <td align="center">
      <img src="asset/Compare/21_gif/0021.png" alt="Input Image" width="250px">
      <div><strong>Input Image</strong></div>
    </td>
    <td align="center">
      <img src="asset/Compare/21_gif/Ours_ori_custom_021.glb.gif" alt="MultiGO" width="250px">
      <div><strong>MultiGO</strong></div>
    </td>
    <td align="center">
      <img src="asset/Compare/21_gif/SiTH_custom_021.obj.gif" alt="SiTH" width="250px">
      <div><strong>SiTH</strong></div>
    </td>
    <td align="center">
      <img src="asset/Compare/21_gif/SiFU_custom_021.obj.gif" alt="SiFU" width="250px">
      <div><strong>SiFU</strong></div>
    </td>
  </tr>
  <tr align="center">
    <td align="center">
      <img src="asset/Compare/21_gif/ECON_custom_021.obj.gif" alt="ECON" width="250px">
      <div><strong>ECON</strong></div>
    </td>
    <td align="center">
      <img src="asset/Compare/21_gif/ICON_custom_021.obj.gif" alt="ICON" width="250px">
      <div><strong>ICON</strong></div>
    </td>
    <td align="center">
      <img src="asset/Compare/21_gif/GTA_custom_021.obj.gif" alt="GTA" width="250px">
      <div><strong>GTA</strong></div>
    </td>
    <td align="center">
      <img src="asset/Compare/21_gif/PiFU_custom_043.obj.gif" alt="PiFU" width="250px">
      <div><strong>PiFU</strong></div>
    </td>
  </tr>
</table>
</center>

---

<center>
<table align="center">
  <tr align="center">
    <td align="center">
      <img src="asset/Compare/24_gif/0024.png" alt="Input Image" width="250px">
      <div><strong>Input Image</strong></div>
    </td>
    <td align="center">
      <img src="asset/Compare/24_gif/Ours_ori_custom_024.glb.gif" alt="MultiGO" width="250px">
      <div><strong>MultiGO</strong></div>
    </td>
    <td align="center">
      <img src="asset/Compare/24_gif/SiTH_custom_024.obj.gif" alt="SiTH" width="250px">
      <div><strong>SiTH</strong></div>
    </td>
    <td align="center">
      <img src="asset/Compare/24_gif/SiFU_custom_024.obj.gif" alt="SiFU" width="250px">
      <div><strong>SiFU</strong></div>
    </td>
  </tr>
  <tr align="center">
    <td align="center">
      <img src="asset/Compare/24_gif/ECON_custom_024.obj.gif" alt="ECON" width="250px">
      <div><strong>ECON</strong></div>
    </td>
    <td align="center">
      <img src="asset/Compare/24_gif/ICON_custom_024.obj.gif" alt="ICON" width="250px">
      <div><strong>ICON</strong></div>
    </td>
    <td align="center">
      <img src="asset/Compare/24_gif/GTA_custom_024.obj.gif" alt="GTA" width="250px">
      <div><strong>GTA</strong></div>
    </td>
    <td align="center">
      <img src="asset/Compare/24_gif/PiFU_custom_049.obj.gif" alt="PiFU" width="250px">
      <div><strong>PiFU</strong></div>
    </td>
  </tr>
</table>
</center>

---

<center>
<table align="center">
  <tr align="center">
    <td align="center">
      <img src="asset/Compare/2_gif/0002.png" alt="Input Image" width="250px">
      <div><strong>Input Image</strong></div>
    </td>
    <td align="center">
      <img src="asset/Compare/2_gif/Ours_ori_thuman_002.glb.gif" alt="MultiGO" width="250px">
      <div><strong>MultiGO</strong></div>
    </td>
    <td align="center">
      <img src="asset/Compare/2_gif/SiTH_thuman_002.obj.gif" alt="SiTH" width="250px">
      <div><strong>SiTH</strong></div>
    </td>
    <td align="center">
      <img src="asset/Compare/2_gif/SiFU_thuman_002.obj.gif" alt="SiFU" width="250px">
      <div><strong>SiFU</strong></div>
    </td>
  </tr>
  <tr align="center">
    <td align="center">
      <img src="asset/Compare/2_gif/ECON_thuman_002.obj.gif" alt="ECON" width="250px">
      <div><strong>ECON</strong></div>
    </td>
    <td align="center">
      <img src="asset/Compare/2_gif/ICON_thuman_002.obj.gif" alt="ICON" width="250px">
      <div><strong>ICON</strong></div>
    </td>
    <td align="center">
      <img src="asset/Compare/2_gif/GTA_thuman_002.obj.gif" alt="GTA" width="250px">
      <div><strong>GTA</strong></div>
    </td>
    <td align="center">
      <img src="asset/Compare/2_gif/PiFU_thuman_005.obj.gif" alt="PiFU" width="250px">
      <div><strong>PiFU</strong></div>
    </td>
  </tr>
</table>
</center>

---

<center>
<table align="center">
  <tr align="center">
    <td align="center">
      <img src="asset/Compare/43_gif/0043.png" alt="Input Image" width="250px" style="max-width: 100%;">
      <div><strong>Input Image</strong></div>
    </td>
    <td align="center">
      <img src="asset/Compare/43_gif/Ours_ori_custom_043.glb.gif" alt="MultiGO" width="250px" style="max-width: 100%;">
      <div><strong>MultiGO</strong></div>
    </td>
    <td align="center">
      <img src="asset/Compare/43_gif/SiTH_custom_043.obj.gif" alt="SiTH" width="250px" style="max-width: 100%;">
      <div><strong>SiTH</strong></div>
    </td>
    <td align="center">
      <img src="asset/Compare/43_gif/SiFU_custom_043.obj.gif" alt="SiFU" width="250px" style="max-width: 100%;">
      <div><strong>SiFU</strong></div>
    </td>
  </tr>
  <tr align="center">
    <td align="center">
      <img src="asset/Compare/43_gif/ECON_custom_043.obj.gif" alt="ECON" width="250px" style="max-width: 100%;">
      <div><strong>ECON</strong></div>
    </td>
    <td align="center">
      <img src="asset/Compare/43_gif/ICON_custom_043.obj.gif" alt="ICON" width="250px" style="max-width: 100%;">
      <div><strong>ICON</strong></div>
    </td>
    <td align="center">
      <img src="asset/Compare/43_gif/GTA_custom_043.obj.gif" alt="GTA" width="250px" style="max-width: 100%;">
      <div><strong>GTA</strong></div>
    </td>
    <td align="center">
      <img src="asset/Compare/43_gif/PiFU_custom_087.obj.gif" alt="PiFU" width="250px" style="max-width: 100%;">
      <div><strong>PiFU</strong></div>
    </td>
  </tr>
</table>
</center>

---

<center>
<table align="center">
  <tr align="center">
    <td align="center">
      <img src="asset/Compare/57_gif/0057.png" alt="Input Image" width="250px" style="max-width: 100%;">
      <div><strong>Input Image</strong></div>
    </td>
    <td align="center">
      <img src="asset/Compare/57_gif/Ours_ori_custom_057.glb.gif" alt="MultiGO" width="250px" style="max-width: 100%;">
      <div><strong>MultiGO</strong></div>
    </td>
    <td align="center">
      <img src="asset/Compare/57_gif/SiTH_custom_057.obj.gif" alt="SiTH" width="250px" style="max-width: 100%;">
      <div><strong>SiTH</strong></div>
    </td>
    <td align="center">
      <img src="asset/Compare/57_gif/SiFU_custom_057.obj.gif" alt="SiFU" width="250px" style="max-width: 100%;">
      <div><strong>SiFU</strong></div>
    </td>
  </tr>
  <tr align="center">
    <td align="center">
      <img src="asset/Compare/57_gif/ECON_custom_057.obj.gif" alt="ECON" width="250px" style="max-width: 100%;">
      <div><strong>ECON</strong></div>
    </td>
    <td align="center">
      <img src="asset/Compare/57_gif/ICON_custom_057.obj.gif" alt="ICON" width="250px" style="max-width: 100%;">
      <div><strong>ICON</strong></div>
    </td>
    <td align="center">
      <img src="asset/Compare/57_gif/GTA_custom_057.obj.gif" alt="GTA" width="250px" style="max-width: 100%;">
      <div><strong>GTA</strong></div>
    </td>
    <td align="center">
      <img src="asset/Compare/57_gif/PiFU_custom_115.obj.gif" alt="PiFU" width="250px" style="max-width: 100%;">
      <div><strong>PiFU</strong></div>
    </td>
  </tr>
</table>
</center>

## Comparisions on Human Geometry

<center>
<table align="center">
  <tr align="center">
    <td align="center">
      <img src="asset/Geo/20_gif/0020.png" alt="Input Image" width="250px">
      <div><strong>Input Image</strong></div>
    </td>
    <td align="center">
      <img src="asset/Geo/20_gif/Ours_refined_thuman_020.obj.gif" alt="MultiGO" width="250px">
      <div><strong>MultiGO</strong></div>
    </td>
    <td align="center">
      <img src="asset/Geo/20_gif/HILO_thuman_020.obj.gif" alt="SiTH" width="250px">
      <div><strong>HiLo</strong></div>
    </td>
    <td align="center">
      <img src="asset/Geo/20_gif/VS_thuman_020.obj.gif" alt="SiFU" width="250px">
      <div><strong>VS</strong></div>
    </td>
  </tr>
  <tr align="center">
    <td align="center">
      <img src="asset/Geo/20_gif/SiTH_thuman_020.obj.gif" alt="ECON" width="250px">
      <div><strong>SiTH</strong></div>
    </td>
    <td align="center">
      <img src="asset/Geo/20_gif/SiFU_thuman_020.obj.gif" alt="ICON" width="250px">
      <div><strong>SiFU</strong></div>
    </td>
    <td align="center">
      <img src="asset/Geo/20_gif/ICON_thuman_020.obj.gif" alt="GTA" width="250px">
      <div><strong>ICON</strong></div>
    </td>
    <td align="center">
      <img src="asset/Geo/20_gif/GTA_thuman_020.obj.gif" alt="PiFU" width="250px">
      <div><strong>GTA</strong></div>
    </td>
  </tr>
</table>
</center>

---

<center>
<table align="center">
  <tr align="center">
    <td align="center">
      <img src="asset/Geo/22_gif/0022.png" alt="Input Image" width="250px">
      <div><strong>Input Image</strong></div>
    </td>
    <td align="center">
      <img src="asset/Geo/22_gif/Ours_refined_thuman_022.obj.gif" alt="MultiGO" width="250px">
      <div><strong>MultiGO</strong></div>
    </td>
    <td align="center">
      <img src="asset/Geo/22_gif/HILO_thuman_022.obj.gif" alt="SiTH" width="250px">
      <div><strong>HiLo</strong></div>
    </td>
    <td align="center">
      <img src="asset/Geo/22_gif/VS_thuman_022.obj.gif" alt="SiFU" width="250px">
      <div><strong>VS</strong></div>
    </td>
  </tr>
  <tr align="center">
    <td align="center">
      <img src="asset/Geo/22_gif/SiTH_thuman_022.obj.gif" alt="ECON" width="250px">
      <div><strong>SiTH</strong></div>
    </td>
    <td align="center">
      <img src="asset/Geo/22_gif/SiFU_thuman_022.obj.gif" alt="ICON" width="250px">
      <div><strong>SiFU</strong></div>
    </td>
    <td align="center">
      <img src="asset/Geo/22_gif/ICON_thuman_022.obj.gif" alt="GTA" width="250px">
      <div><strong>ICON</strong></div>
    </td>
    <td align="center">
      <img src="asset/Geo/22_gif/GTA_thuman_022.obj.gif" alt="PiFU" width="250px">
      <div><strong>GTA</strong></div>
    </td>
  </tr>
</table>
</center>

---

<center>
<table align="center">
  <tr align="center">
    <td align="center">
      <img src="asset/Geo/39_gif/0039.png" alt="Input Image" width="250px">
      <div><strong>Input Image</strong></div>
    </td>
    <td align="center">
      <img src="asset/Geo/39_gif/Ours_refined_thuman_039.obj.gif" alt="MultiGO" width="250px">
      <div><strong>MultiGO</strong></div>
    </td>
    <td align="center">
      <img src="asset/Geo/39_gif/HILO_thuman_039.obj.gif" alt="SiTH" width="250px">
      <div><strong>HiLo</strong></div>
    </td>
    <td align="center">
      <img src="asset/Geo/39_gif/VS_thuman_039.obj.gif" alt="SiFU" width="250px">
      <div><strong>VS</strong></div>
    </td>
  </tr>
  <tr align="center">
    <td align="center">
      <img src="asset/Geo/39_gif/SiTH_thuman_039.obj.gif" alt="ECON" width="250px">
      <div><strong>SiTH</strong></div>
    </td>
    <td align="center">
      <img src="asset/Geo/39_gif/SiFU_thuman_039.obj.gif" alt="ICON" width="250px">
      <div><strong>SiFU</strong></div>
    </td>
    <td align="center">
      <img src="asset/Geo/39_gif/ICON_thuman_039.obj.gif" alt="GTA" width="250px">
      <div><strong>ICON</strong></div>
    </td>
    <td align="center">
      <img src="asset/Geo/39_gif/GTA_thuman_039.obj.gif" alt="PiFU" width="250px">
      <div><strong>GTA</strong></div>
    </td>
  </tr>
</table>
</center>

---

<center>
<table align="center">
  <tr align="center">
    <td align="center">
      <img src="asset/Geo/44_gif/0044.png" alt="Input Image" width="250px">
      <div><strong>Input Image</strong></div>
    </td>
    <td align="center">
      <img src="asset/Geo/44_gif/Ours_refined_thuman_044.obj.gif" alt="MultiGO" width="250px">
      <div><strong>MultiGO</strong></div>
    </td>
    <td align="center">
      <img src="asset/Geo/44_gif/HILO_thuman_044.obj.gif" alt="SiTH" width="250px">
      <div><strong>HiLo</strong></div>
    </td>
    <td align="center">
      <img src="asset/Geo/44_gif/VS_thuman_044.obj.gif" alt="SiFU" width="250px">
      <div><strong>VS</strong></div>
    </td>
  </tr>
  <tr align="center">
    <td align="center">
      <img src="asset/Geo/44_gif/SiTH_thuman_044.obj.gif" alt="ECON" width="250px">
      <div><strong>SiTH</strong></div>
    </td>
    <td align="center">
      <img src="asset/Geo/44_gif/SiFU_thuman_044.obj.gif" alt="ICON" width="250px">
      <div><strong>SiFU</strong></div>
    </td>
    <td align="center">
      <img src="asset/Geo/44_gif/ICON_thuman_044.obj.gif" alt="GTA" width="250px">
      <div><strong>ICON</strong></div>
    </td>
    <td align="center">
      <img src="asset/Geo/44_gif/GTA_thuman_044.obj.gif" alt="PiFU" width="250px">
      <div><strong>GTA</strong></div>
    </td>
  </tr>
</table>
</center>

---

<center>
<table align="center">
  <tr align="center">
    <td align="center">
      <img src="asset/Geo/53_gif/0053.png" alt="Input Image" width="250px">
      <div><strong>Input Image</strong></div>
    </td>
    <td align="center">
      <img src="asset/Geo/53_gif/Ours_refined_thuman_053.obj.gif" alt="MultiGO" width="250px">
      <div><strong>MultiGO</strong></div>
    </td>
    <td align="center">
      <img src="asset/Geo/53_gif/HILO_thuman_053.obj.gif" alt="SiTH" width="250px">
      <div><strong>HiLo</strong></div>
    </td>
    <td align="center">
      <img src="asset/Geo/53_gif/VS_thuman_053.obj.gif" alt="SiFU" width="250px">
      <div><strong>VS</strong></div>
    </td>
  </tr>
  <tr align="center">
    <td align="center">
      <img src="asset/Geo/53_gif/SiTH_thuman_053.obj.gif" alt="ECON" width="250px">
      <div><strong>SiTH</strong></div>
    </td>
    <td align="center">
      <img src="asset/Geo/53_gif/SiFU_thuman_053.obj.gif" alt="ICON" width="250px">
      <div><strong>SiFU</strong></div>
    </td>
    <td align="center">
      <img src="asset/Geo/53_gif/ICON_thuman_053.obj.gif" alt="GTA" width="250px">
      <div><strong>ICON</strong></div>
    </td>
    <td align="center">
      <img src="asset/Geo/53_gif/GTA_thuman_053.obj.gif" alt="PiFU" width="250px">
      <div><strong>GTA</strong></div>
    </td>
  </tr>
</table>
</center>

---

# Visualization for Ablation Study
## Visualizations on WLR Module
<center>
<img src="asset/Abl/refined_supp1.png" width="900px">
</center>
We provide further insights into the impact of the WLR module by comparing results before and after its implementation. The results clearly illustrate that the WLR module significantly enhances the geometric quality of the reconstructed mesh, particularly in capturing intricate details such as clothing wrinkles and facial features. The first row shows the normal map that has not been processed by the WLR module, while the second row shows the optimized normal map.

---

## Visualizations on SLE Module
<center>
<img src="asset/Abl/SLE_supp.png" width="900px">
</center>

We presents additional results that highlight the effects of incorporating the Skeleton-Level Enhancement (SLE) module. The comparison reveals that the SLE module effectively aids in reconstructing the target human geometry, resulting in a reconstructed mesh that closely resembles the ground truth (GT) mesh. The first row illustrates our method without the SLE module, while the second row shows our methods incorporating this module. The last rows present the GT for reference.

---

# Animatable 3D Avatars
<center>
<table align="center">
  <tr align="center">
    <td align="center">
      <img src="asset/animation/3.gif" alt="1" width="250px">
    </td>
    <td align="center">
      <img src="asset/animation/8.gif" alt="2" width="250px">
    </td>
    <td align="center">
      <img src="asset/animation/7.gif" alt="3" width="250px">
    </td>
    <td align="center">
      <img src="asset/animation/4.gif" alt="4" width="250px">
    </td>
  </tr>
  <tr align="center">
    <td align="center">
      <img src="asset/animation/5.gif" alt="5" width="250px">
    </td>
    <td align="center">
      <img src="asset/animation/6.gif" alt="6" width="250px">
    </td>
    <td align="center">
      <img src="asset/animation/1.gif" alt="7" width="250px">
    </td>
    <td align="center">
      <img src="asset/animation/2.gif" alt="8" width="250px">
    </td>
  </tr>
</table>
</center>

# How MultiGO Works
<center>
<img src="asset/Overview_1115.png" width="900px">
</center>
Our method, MultiGO, addresses monocular textured 3D human reconstruction by introducing a multi-level geometry learning framework that significantly enhances reconstruction quality. To accurately capture the human body's posture, we propose the SLE module, which projects 3D Fourier features into the 2D space of the input image, allowing the Gaussian reconstruction model to fully utilize prior human shape knowledge. For improved depth estimation of human joints, the JLA strategy applies controlled perturbations during training, increasing the model's robustness to depth inaccuracies during inference. To refine geometric details like body wrinkles, the WLR module resembles the final de-noising steps in diffusion theory, treating coarse meshes as Gaussian noise and using the high-quality texture of reconstructed Gaussian as conditions to refine wrinkles.