# RingMoEDatasets
The pre-training dataset and downstream datasets for RingMoE foundation model

## Pre-training dataset RingMOSS
The RingMOSS pre-training dataset comprises 400 million multi-modal RS images collected from international public platforms and proprietary datasets, covering four modalities: Opt, MS, SAR-L1, and SAR-L2.

However, due to proprietary restrictions and confidentiality agreements, data from private sources cannot be publicly disclosed. To support reproducibility and further research, we have released a subset of the RingMOSS dataset collected from public platforms.

This ensures compliance with data usage policies while enabling the community to leverage a significant portion of the data for exploration and benchmarking.

The public data are continuously being uploaded.

## Downstream benchmarks for RingMoE evaluation

The majority of the downstream task datasets used in this study are publicly available for training and validation.
They can be accessed from the following sources:

### Scene classification

1. NWPU-RESISC45: Cheng G, Han J, Lu X. Remote sensing image scene classification: Benchmark and state of the art[J]. Proceedings of the IEEE, 2017, 105(10): 1865-1883. https://onedrive.live.com/?authkey=%21AHHNaHIlzp%5FIXjs&id=5C5E061130630A68%21107&cid=5C5E061130630A68&parId=root&parQt=sharedby&o=OneUp
2. AID: Xia G S, Hu J, Hu F, et al. AID: A benchmark data set for performance evaluation of aerial scene classification[J]. IEEE Transactions on Geoscience and Remote Sensing, 2017, 55(7): 3965-3981. https://captain-whu.github.io/AID/

### Semantic segmentation
1. iSAID: Waqas Zamir S, Arora A, Gupta A, et al. isaid: A large-scale dataset for instance segmentation in aerial images[C]//Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops. 2019: 28-37. https://captain-whu.github.io/iSAID/dataset.html

2. Potsdam: https://www.isprs.org/education/benchmarks/UrbanSemLab/Default.aspx

3. Dyna.-pla: Toker A, Kondmann L, Weber M, et al. Dynamicearthnet: Daily multi-spectral satellite dataset for semantic change segmentation[C]//Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2022: 21158-21167. https://github.com/aysim/dynnet?tab=readme-ov-file

4. AIR-POLSAR-SEG: Wang Z, Zeng X, Yan Z, et al. AIR-PolSAR-Seg: A large-scale data set for terrain segmentation in complex-scene PolSAR images[J]. IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing, 2022, 15: 3830-3841. https://github.com/AICyberTeam/AIR-PolSAR-Seg

5. SARSegL1: SARSegL1 dataset cannot be publicly released due to proprietary restrictions, confidentiality agreements, and security-related considerations associated with its SAR imagery sources.

6. WHU-OPT-SAR: Li X, Zhang G, Cui H, et al. MCANet: A joint semantic segmentation framework of optical and SAR images for land use classification[J]. International Journal of Applied Earth Observation and Geoinformation, 2022, 106: 102638. https://github.com/AmberHen/WHU-OPT-SAR-dataset.git

7. DFC23: https://www.grss-ieee.org/community/technical-committees/2023-ieee-grss-data-fusion-contest/

### Object detection
1. DIOR/DIOR-R: Ke Li, Gang Wan, Gong Cheng*, Liqiu Meng, Junwei Han*. Object detection in optical remote sensing images: a survey and a new benchmark. ISPRS Journal of Photogrammetry and Remote Sensing, 159: 296-307, 2020. https://gcheng-nwpu.github.io

3. HRSC2016: Liu Z, Yuan L, Weng L, et al. A high resolution optical satellite image dataset for ship recognition and some new baselines[C]//International conference on pattern recognition applications and methods. SciTePress, 2017, 2: 324-331. http://www.escience.cn/people/liuzikun/DataSet.html

4. HRSID: Wei S, Zeng X, Qu Q, et al. HRSID: A high-resolution SAR images dataset for ship detection and instance segmentation[J]. Ieee Access, 2020, 8: 120234-120254. https://github.com/chaozhong2010/HRSID

5. SAR-AIRcraft-1.0: WANG Zhirui, KANG Yuzhuo, ZENG Xuan, et al. SAR-AIRcraft-1.0: High-resolution SAR aircraft detection and recognition dataset[J]. Journal of Radars, 2023, 12(4): 906–922. doi:  10.12000/JR23043. https://radars.ac.cn/web/data/getData?newsColumnId=f896637b-af23-4209-8bcc-9320fceaba19

### Object tracking

1. AIR-MOT: He Q, Sun X, Yan Z, et al. Multi-object tracking in satellite videos with graph-based multitask modeling[J]. IEEE Transactions on Geoscience and Remote Sensing, 2022, 60: 1-13.

2. AIR-HSAO: Ren L, Yin W, Diao W, et al. Motion-Guided Multi-Object Tracking Model for High-Speed Aerial Objects in Satellite Videos[J]. IEEE Transactions on Geoscience and Remote Sensing, 2024.

### Change detection

1. LEVIR-CD: Chen H, Shi Z. A spatial-temporal attention-based method and a new dataset for remote sensing image change detection[J]. Remote Sensing, 2020, 12(10): 1662. https://chenhao.in/LEVIR/

2. CDD: Lebedev M A, Vizilter Y V, Vygolov O V, et al. Change detection in remote sensing images using conditional adversarial networks[J]. The International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences, 2018, 42: 565-571. https://drive.google.com/file/d/1GX656JqqOyBi_Ef0w65kDGVto-nHrNs9/edit?pli=1

### Depth estimation
1. ISPRS Vaihingen：https://www.isprs.org/education/benchmarks/UrbanSemLab/2d-sem-label-vaihingen.aspx

2. ISPRS Potsdam：https://www.isprs.org/education/benchmarks/UrbanSemLab/2d-sem-label-potsdam.aspx

### Unseen-class recognition
1. NWPU-RESISC45: Cheng G, Han J, Lu X. Remote sensing image scene classification: Benchmark and state of the art[J]. Proceedings of the IEEE, 2017, 105(10): 1865-1883. https://onedrive.live.com/?authkey=%21AHHNaHIlzp%5FIXjs&id=5C5E061130630A68%21107&cid=5C5E061130630A68&parId=root&parQt=sharedby&o=OneUp

2. WHU-RS19: Sheng G, Yang W, Xu T, et al. High-resolution satellite scene classification using a sparse coding based multiple feature combination[J]. International journal of remote sensing, 2012, 33(8): 2395-2412. https://paperswithcode.com/dataset/whu-rs19

3. UCMerced: Yang Y, Newsam S. Bag-of-visual-words and spatial extensions for land-use classification[C]//Proceedings of the 18th SIGSPATIAL international conference on advances in geographic information systems. 2010: 270-279. https://vision.ucmerced.edu/datasets/

4. iSAID: Waqas Zamir S, Arora A, Gupta A, et al. isaid: A large-scale dataset for instance segmentation in aerial images[C]//Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops. 2019: 28-37. https://captain-whu.github.io/iSAID/dataset.html

5. LoveDA: Wang J, Zheng Z, Ma A, et al. LoveDA: A remote sensing land-cover dataset for domain adaptive semantic segmentation[J]. arXiv preprint arXiv:2110.08733, 2021. https://github.com/Junjue-Wang/LoveDA