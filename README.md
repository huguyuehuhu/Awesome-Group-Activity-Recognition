# Awesome-Group-Activity-Recognition [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of Group Activity (_a.k.a._, Collective Activity) recognition papers, codes, datasets and other resources.
If you have any problems, suggestions or improvements, please submit an issue or PR.

## TODO <!-- omit in toc -->

- [x] Paper list
- [x] Available codes
- [x] Leaderboard

## Contents <!-- omit in toc -->

- [Datasets](#datasets)
- [Papers](#papers)
  - [arXiv papers](#arxiv-papers)
  - [2019](#2019)
  - [2018](#2018)
  - [2017](#2017)
  - [2016](#2016)
  - [before 2016](#before-2016)
- [LeaderBoard](#LeaderBoard)
  

## Datasets

- (2016) Volleyball Dataset [[Github](https://github.com/mostafa-saad/deep-activity-rec)]
- (2012) Choi's Dataset [[Homepage](http://www-personal.umich.edu/~wgchoi/eccv12/wongun_eccv12.html)]
- (2011) Collective Activity Augmented Dataset [[Homepage](http://vhosts.eecs.umich.edu/vision//activity-dataset.html)]
- (2009) Collective Activity Dataset (CAD) [[Homepage](http://vhosts.eecs.umich.edu/vision//activity-dataset.html)]

This section only shows some popular or new datasets.

## Papers

### arXiv papers

This section only includes the last five papers since 2018 in [arXiv.org](arXiv.org). Note that arXiv papers **without available codes** are not included in [the leaderboard of performance](#leaderboard).

- Progressive Relation Learning for Group Activity Recognition, 2019.08 [[arxiv](https://arxiv.org/abs/1908.02948)]
- A Multi-Stream Convolutional Neural Network Framework for Group Activity Recognition, 2018.12 [[arxiv](https://arxiv.org/abs/1812.10328)]


### journal papers
- **stagNet:** An Attentive Semantic RNN for Group Activity and Individual Action Recognition (**TCSVT 2019**) [[paper](https://ieeexplore.ieee.org/document/8621027)]
- **SPA+KD+GCN:** Learning Semantics-Preserving Attention and Contextual Interaction for Group Activity Recognition (**TIP 2019**) [[paper](https://ieeexplore.ieee.org/document/8709974)]
 

### 2019
- **ARG:** Learning Actor Relation Graphs for Group Activity Recognition (**CVPR 2019**) [[paper](https://arxiv.org/abs/1904.10117)] [[github](https://github.com/wjchaoGit/Group-Activity-Recognition)]
- **CRM:** Convolutional Relational Machine for Group Activity Recognition (**CVPR 2019**) [[paper](http://openaccess.thecvf.com/content_CVPR_2019/papers/Azar_Convolutional_Relational_Machine_for_Group_Activity_Recognition_CVPR_2019_paper.pdf)]


### 2018
- **PCTDM:** Participation-Contributed Temporal Dynamic Model for Group Activity Recognition (**ACM MM 2018**) [[paper](https://dl.acm.org/citation.cfm?id=3240572)] [[github](https://github.com/ruiyan1995/Group-Activity-Recognition)]
- **SPA+KD+OF:** Mining Semantics-Preserving Attention for Group Activity Recog-nition (**ACM MM 2018**) [[paper](https://www.semanticscholar.org/paper/Mining-Semantics-Preserving-Attention-for-Group-Tang-Wang/cecf4ca1790e0ccb2c47a992d950a3e130a916ef)]
- **HRN:** Hierarchical Relational Networks for Group Activity Recognition and Retrieval (**ECCV 2018**) [[paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Mostafa_Ibrahim_Hierarchical_Relational_Networks_ECCV_2018_paper.pdf)] [[github](https://github.com/mostafa-saad/hierarchical-relational-network)]
- **HANs+HCNs:** (**ICASSP 2018**) [[paper](https://doi.org/10.1109/ICASSP.2018.8461770)]
- **SRNN:** Structural recurrent neural network (SRNN) for group activity analysis (**WACV 2018**) [[paper](https://www.computer.org/csdl/proceedings-article/wacv/2018/488601b625/12OmNqI04HX)]
- **MLS-GAN:** A Hierarchical Deep Temporal Model for Group Activity Recognition (**ACCV 2018**) [[paper](https://link.springer.com/chapter/10.1007%2F978-3-030-20887-5_21)]

### 2017
- **SBGAR:** Semantics Based Group Activity Recognition (**ICCV 2017**) [[paper](http://openaccess.thecvf.com/content_ICCV_2017/papers/Li_SBGAR_Semantics_Based_ICCV_2017_paper.pdf)]
- **RMIC:** Recurrent modeling of interaction context for collective activity recognition (CVPR 2017) [[paper](https://ieeexplore.ieee.org/document/8100266)]
- **CERN:** Confidence-energy recurrent network for group activity recognition (**CVPR 2017**) [[paper](https://arxiv.org/abs/1704.03058)]
- **SSU:** Social scene understanding: End-to-end multi-person action localization and collective activity recognition (**CVPR 2017**) [[paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/Bagautdinov_Social_Scene_Understanding_CVPR_2017_paper.pdf)]


### 2016
- **HDTM:** A Hierarchical Deep Temporal Model for Group Activity Recognition (**CVPR 2016**) [[paper](https://arxiv.org/abs/1511.06040)]  Deep Temporal Model for Group Activity Recognition (**CVPR 2016**) [[paper](https://arxiv.org/abs/1511.06040)] [[github](https://github.com/mostafa-saad/deep-activity-rec)] 
- **CRF:** Structure Inference Machines: Recurrent Neural Networks for Analyzing Relations in Group Activity Recognition (**CVPR 2016**) [[paper](https://www.cs.sfu.ca/~mori/research/papers/deng-cvpr16.pdf)]

### before 2016
- omitted

## LeaderBoard

The section is being continually updated. We only show results on Volleyball and CAD datasets.

### Volleyball Dataset

| Year | Methods               | Cross-Subject | Cross-View |
| ---- | --------------------- | :-----------: | :--------: |
| 2014 | Lie Group             |     50.1      |    52.8    |
| 2015 | H-RNN                 |     59.1      |    64.0    |
| 2016 | Part-aware LSTM       |     62.9      |    70.3    |
| 2016 | Trust Gate ST-LSTM    |     69.2      |    77.7    |
| 2017 | Two-stream RNN        |     71.3      |    79.5    |
| 2017 | STA-LSTM              |     73.4      |    81.2    |
| 2017 | Ensemble TS-LSTM      |     74.6      |    81.3    |
| 2017 | Visualization CNN     |     76.0      |    82.6    |
| 2017 | C-CNN + MTLN          |     79.6      |    84.8    |
| 2017 | Temporal Conv         |     74.3      |    83.1    |
| 2017 | VA-LSTM               |     79.4      |    87.6    |
| 2018 | Beyond Joints         |     79.5      |    87.6    |
| 2018 | ST-GCN                |     81.5      |    88.3    |
| 2018 | DPRL                  |     83.5      |    89.8    |
| 2018 | HCN                   |     86.5      |    91.1    |
| 2018 | SR-TSL                |     84.8      |    92.4    |
| 2018 | MAN                   |     82.7      |    93.2    |
| 2019 | RA-GCN                |     85.9      |    93.5    |
| 2019 | AS-GCN                |     86.8      |    94.2    |
| 2019 | AGC-LSTM (Joint&Part) |     89.2      |    95.0    |
| 2019 | 2s-AGCN               |     88.5      |    95.1    |
| 2019 | DGNN                  |   **89.9**    |  **96.1**  |

### Reference

[1] [Awesome-Skeleton-based-Action-Recognition](https://github.com/niais/Awesome-Skeleton-based-Action-Recognition)
