# robofruit
[![DOI](https://img.shields.io/badge/DOI-10.1109%2FICRA46639.2022.9812303-blue)](https://doi.org/10.1109/ICRA46639.2022.9812303)

![Alt text](https://github.com/rick-dn/robofruit/blob/main/icra_2022_strawberry_final.pdf.png)

****Summary****

This repository contains the code and datasets for our paper "Strawberry picking point localization ripeness and weight estimation" by Tafuro et al.

In this paper, we address the challenges of robotic strawberry harvesting, focusing on the crucial aspect of fruit picking perception. We highlight the difficulties in accurately determining picking points due to factors like noise, occlusion, and the varying shapes and orientations of strawberries.

To tackle these issues, we present two novel datasets of strawberries. These datasets are unique in that they are annotated with not only picking points but also key-points on the strawberries, information about their weight and size, and "pluckability" (suitability for picking).

We conducted experiments using Detectron-2, a Mask-RCNN-based model with key-point detection capabilities. Our results demonstrate that the key-point detection approach is effective for localizing picking and grasping points. Furthermore, we introduce a novel baseline model for weight estimation that outperforms several state-of-the-art deep networks.

****Key Contributions****

* We introduce two novel datasets of strawberries, containing annotations for picking points, key-points, weight, and size.
   
* We present a method for picking point and orientation detection using key-point detection.
   
* We propose a novel baseline method for weight estimation that outperforms several state-of-the-art deep networks.

****Important Notes****

* The datasets and annotations are available at [https://github.com/imanlab/strawberry-pp-w-r-dataset](https://github.com/imanlab/strawberry-pp-w-r-dataset).
   
* This repository provides the code and datasets for our research.
   
* For detailed information about the dataset, model architecture, experimental setup, and results, please refer to the original paper.

  ****For citing this work****

  @inproceedings{tafuro2022strawberry,
  title={Strawberry picking point localization ripeness and weight estimation},
  author={Tafuro, Alessandra and Adewumi, Adeayo and Parsa, Soran and Amir, Ghalamzan E and Debnath, Bappaditya},
  booktitle={2022 International Conference on Robotics and Automation (ICRA)},
  pages={2295--2302},
  year={2022},
  organization={IEEE}
}
