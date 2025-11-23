# Introduction 
Fire-ART is a firefighting asset recognition dataset comprising 2,626 images and 6,627 annotated instances.

The dataset integrates four image sources: (1) an enhanced FireNet image set (Boehm et al., 2019), (2) publicly available images, (3) self-captured photographs, and (4) a modified subset of the HKU Building Image Dataset (HBD) (Wong et al., 2024). The self-captured images were collected from six regions: the United Kingdom, the United States, Mainland China, Macau SAR, France, and Greece.

It includes 15 common categories of firefighting equipment: fire extinguisher, fire exit sign, fire door sign, fire alarm, emergency light, smoke detector, fire hose reel, piping system, sprinkler, fire call point, emergency door release, fire blanket, fire equipment sign, firefighting lift switch, and hidden fire equipment.

Fire-ART is designed to support the development of computer vision models for object detection and segmentation, with the aim of advancing automation in indoor fire safety management and smart facility management.

Fire-ART is available at: https://zenodo.org/records/17102363

<img width="866" height="633" alt="image" src="https://github.com/user-attachments/assets/a8c305bd-8ffe-49e9-9e7d-f89bbbdd1cc3" />


# Dataset Citation
This dataset accompanies the manuscript: 

Wen, Y., Qiao, Y., Lam, C.C., Brilakis, I., Lee, S. and Wong, M.O.*, 2025. Semantic BIM enrichment for firefighting assets: Fire-ART dataset and panoramic image-based 3D reconstruction. ISPRS Journal of Photogrammetry and Remote Sensing 231, 679–703. https://doi.org/10.1016/j.isprsjprs.2025.11.015

# External Data Source Attribution
1. The FireNet dataset (Boehm et al., 2019) is publicly available at:
https://www.firenet.xyz/

Please download the FireNet dataset from the above link.

2. The HBD dataset (Wong et al., 2024) is publicly avilable at:
https://github.com/EnochYing/Image2BIM/tree/main/HBD 

Please download the HBD dataset from the above link.

Reference: Wong, M.O., Ying, H., Yin, M., Yi, X., Xiao, L., He, C., & Tang, L. (2024). 3D Semantic Reconstruction-oriented Image Dataset for Building Element Segmentation. Automation in Construction 165.

# How to Use
This repository hosts the images and annotations of the Fire-ART dataset.

Images: The collection includes (1) the FireNet dataset, (2) publicly available images, (3) self-captured photographs, and (4) a modified subset of the HBD dataset. For images from (1) the FireNet dataset, please download the originals directly from the official source:
https://rdr.ucl.ac.uk/articles/dataset/FireNet/9137798

Annotations: Annotations for all four image sources are provided in this repository. Please note that for FireNet images, you should use our enhanced annotations (rather than the original ones) to ensure consistency with the 15 defined firefighting asset categories.

# Licensing & Terms of Use
This dataset is published under the Creative Commons Attribution 4.0 International License (CC BY 4.0). You are free to use, share, and adapt the dataset with proper attribution.

For enquires, please feel free to contact Yutong Qiao (yc37467@connect.um.edu.mo), Ya Wen (yw710@cam.ac.uk), or Mun On Wong (mowong@um.edu.mo).
