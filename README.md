# GLOBECOM2023-MetaLearningLocalizationCSI  

This repository contains the code and dataset for the paper **"A Meta-Learning-Based Generalizable Indoor Localization Model Using Channel State Information"**, presented at the IEEE Global Communications Conference (GLOBECOM) 2023.  

<div align="center">  
  <img src="https://github.com/user-attachments/assets/772ac8a9-82ae-4cc0-81c4-2757dbf53a65" alt="Image" width="400"/>  
</div>  

The code includes the implementation of the proposed meta-learning algorithm, **Task-Biased Model-Agnostic Meta-Learning (TB-MAML)**, along with the meta-learning framework for indoor localization based on CSI data.  

<div align="center">  
  <img src="https://github.com/user-attachments/assets/4753bc1c-e0da-4896-80cb-33a97d51886e" alt="Image" width="400"/>  
</div>  

## Dataset  

<div align="center">  
  <img src="https://github.com/user-attachments/assets/5c68e3ad-f441-4e36-a3ab-5c68f8ad309c" alt="Image" width="400"/>  
</div>  

<div align="center">  
  <img src="https://github.com/user-attachments/assets/7ecdadd9-2c1b-4e4d-bdb8-7022900a0c05" alt="Image" width="400"/>  
</div>  

All CSI data files follow this naming convention:  

x0_y0_p100_b40_s1_t1.mat


- `x` and `y` specify the coordinates of the reference point within the reference point map.  
- `t` indicates the location where the CSI data was collected (34 locations in total).  
- `p`, `b`, and `s` remain constant for the scenarios collected in this paper and can be ignored.  

## Citation  

If you use this work or the dataset in your research, please cite the following paper:  

```bibtex  
@inproceedings{owfi2023meta,  
  title={A Meta-Learning-Based Generalizable Indoor Localization Model Using Channel State Information},  
  author={Owfi, Ali and Lin, ChunChih and Guo, Linke and Afghah, Fatemeh and Ashdown, Jonathan and Turck, Kurt},  
  booktitle={GLOBECOM 2023-2023 IEEE Global Communications Conference},  
  pages={4607--4612},  
  year={2023},  
  organization={IEEE}  
}  
