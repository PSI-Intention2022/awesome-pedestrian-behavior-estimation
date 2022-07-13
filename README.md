# Awesome Pedestrian Behavior Estimation
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

Papers and resources collection about pedestrian behavior estimation

# Contents
- [Awesome Pedestrian Behavior Estimation](#awesome-pedestrian-behavior-estimation)
- [Contents](#contents)
- [Papers](#papers)
  - [Ego-view](#ego-view)
  - [Top-down view](#top-down-view)
- [Datasets](#datasets)
  - [Vision](#vision)
  - [Multi-sensor](#multi-sensor)
  - [Simulator](#simulator)
- [Library](#library)
- [Lectures and Tutorials](#lectures-and-tutorials)
- [Other Resources](#other-resources)
- [Non-pedestrian Trajectory](#non-pedestrian-trajectory)

# Papers

## Ego-view

**Survey**

**Conference**
- Pedestrian and Ego-vehicle Trajectory Prediction from Monocular Camera [[2021 CVPR]](https://openaccess.thecvf.com/content/CVPR2021/papers/Neumann_Pedestrian_and_Ego-Vehicle_Trajectory_Prediction_From_Monocular_Camera_CVPR_2021_paper.pdf)
- Bifold and Semantic Reasoning for Pedestrian Behavior Prediction [[2021 ICCV]](https://openaccess.thecvf.com/content/ICCV2021/papers/Rasouli_Bifold_and_Semantic_Reasoning_for_Pedestrian_Behavior_Prediction_ICCV_2021_paper.pdf) [[Code]]()
- TITAN: Future Forecast using Action Priors [[2020 CVPR]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Malla_TITAN_Future_Forecast_Using_Action_Priors_CVPR_2020_paper.pdf) [[Data]](https://usa.honda-ri.com/titan)
- Spatiotemporal Relationship Reasoning for Pedestrian Intent Prediction [[2020 IEEE RA-L & ICRA]](https://arxiv.org/pdf/2002.08945.pdf) [[Project]](https://stip.stanford.edu) [[Data]](https://stip.stanford.edu/dataset.html) [[Code]](https://github.com/StanfordVL/STR-PIP/)
- PIE: A Large-Scale Dataset and Models for Pedestrian Intention Estimation and Trajectory Prediction [[2019 CVPR]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Rasouli_PIE_A_Large-Scale_Dataset_and_Models_for_Pedestrian_Intention_Estimation_ICCV_2019_paper.pdf) [[Project]](https://data.nvision2.eecs.yorku.ca/PIE_dataset/) [[Code-annoatation]](https://github.com/aras62/PIE) [[Code-model]](https://github.com/aras62/PIEPredict)

**Journal**

**Workshop**
- Are They Going to Cross? A Benchmark Dataset and Baseline for Pedestrian Crosswalk Behavior [[2017 ICCV Workshop]](https://openaccess.thecvf.com/content_ICCV_2017_workshops/papers/w3/Rasouli_Are_They_Going_ICCV_2017_paper.pdf)


**Preprints**

## Top-down view
- End-to-End Trajectory Distribution Prediction Based on Occupancy Grid Maps [[2022 CVPR]](https://openaccess.thecvf.com/content/CVPR2022/papers/Guo_End-to-End_Trajectory_Distribution_Prediction_Based_on_Occupancy_Grid_Maps_CVPR_2022_paper.pdf)
- Remember Intentions: Retrospective-Memory-based Trajectory Prediction [[2022 CVPR]](https://openaccess.thecvf.com/content/CVPR2022/papers/Xu_Remember_Intentions_Retrospective-Memory-Based_Trajectory_Prediction_CVPR_2022_paper.pdf)
- Non-Probability Sampling Network for Stochastic Human Trajectory Prediction [[2022 CVPR]](https://openaccess.thecvf.com/content/CVPR2022/papers/Bae_Non-Probability_Sampling_Network_for_Stochastic_Human_Trajectory_Prediction_CVPR_2022_paper.pdf)
- Human Trajectory Prediction with Momentary Observation [[2022 CVPR]](https://openaccess.thecvf.com/content/CVPR2022/papers/Sun_Human_Trajectory_Prediction_With_Momentary_Observation_CVPR_2022_paper.pdf)
- Whose Track Is It Anyway? Improving Robustness to Tracking Errors with Affinity-based Trajectory Prediction [[2022 CVPR]](https://openaccess.thecvf.com/content/CVPR2022/papers/Weng_Whose_Track_Is_It_Anyway_Improving_Robustness_to_Tracking_Errors_CVPR_2022_paper.pdf)
- How many Observations are Enough? Knowledge Distillation for Trajectory Forecasting [[2022 CVPR]](https://openaccess.thecvf.com/content/CVPR2022/papers/Monti_How_Many_Observations_Are_Enough_Knowledge_Distillation_for_Trajectory_Forecasting_CVPR_2022_paper.pdf)
- GroupNet: Multiscale Hypergraph Neural Networks for Trajectory Prediction with Relational Reasoning [[2022 CVPR]](https://openaccess.thecvf.com/content/CVPR2022/papers/Xu_GroupNet_Multiscale_Hypergraph_Neural_Networks_for_Trajectory_Prediction_With_Relational_CVPR_2022_paper.pdf)

# Datasets
## Vision
**Ego-vehicle**
- Pedestrian Situated Intent Dataset (PSI) (2022) [[Data]](http://pedestriandataset.situated-intent.net)
- Spatiotemporal Relationship Reasoning for Pedestrian Intent Prediction (STIP) (2020) [[Data]](https://stip.stanford.edu)
- Trajectory Infer- ence using Targeted Action priors Network (TITAN) (2020) [[Data]](https://usa.honda-ri.com/titan)
- Pedestrian Intention Estimation (PIE) (2019) [[Data]](https://data.nvision2.eecs.yorku.ca/PIE_dataset/)
- Joint Attention in Autonomous Driving (JAAD) (2017) [[Data]](https://data.nvision2.eecs.yorku.ca/JAAD_dataset/)
- ETH-Person (2010) [[Data]](https://data.vision.ee.ethz.ch/cvl/aess/)

**Top-down View**
- inD (2020) [[Data]](https://www.ind-dataset.com)
- Vehicle-Crowd Intraction (VCI) - DUT Dataset (2019) [[Data]](https://github.com/dongfang-steven-yang/vci-dataset-dut)
- Forum Pedestrian Dataset (2010) [[Data]](https://homepages.inf.ed.ac.uk/rbf/FORUMTRACKING/)

**Surveillance Camera**
- TRAF (2019 CVPR) [[Data]](https://gamma.umd.edu/researchdirections/autonomousdriving/trafdataset/) [[Paper]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Chandra_TraPHic_Trajectory_Prediction_in_Dense_and_Heterogeneous_Traffic_Using_Weighted_CVPR_2019_paper.pdf)
- WildTrack (2017) [[Data]](https://exposing.ai/wildtrack/)
- VIRAT (2011 CVPR) [[Data]](https://viratdata.org) [[Paper]](http://www.cs.columbia.edu/~vondrick/vatic/virat.pdf)
- TownCentre (2009) [[Data]](https://exposing.ai/oxford_town_centre/)

## Multi-sensor
- L-CAS (2018) [[Data]](https://lcas.lincoln.ac.uk/wp/research/data-sets-software/l-cas-multisensor-people-dataset/)
- CitySpaces [[Data]](https://www.cityscapes-dataset.com/dataset-overview/)
- KITTI 360 (2012) [[Data]](http://www.cvlibs.net/datasets/kitti/)

## Simulator
- The Garden of Forking Paths (2020) [[Data]](https://next.cs.cmu.edu/multiverse/index.html) [[Paper (2020 CVPR)]](https://arxiv.org/abs/1912.06445) [[Paper (2020 ECCV)]](https://arxiv.org/abs/2004.02022)

# Library

# Lectures and Tutorials

# Other Resources

- "Trajectory Prediction Papers" [[GitHub]](https://github.com/aras62/vision-based-prediction)

# Non-pedestrian Trajectory
- MUSE-VAE: Multi-Scale VAE for Environment-Aware Long Term Trajectory Prediction [[2022 CVPR]](https://openaccess.thecvf.com/content/CVPR2022/papers/Lee_MUSE-VAE_Multi-Scale_VAE_for_Environment-Aware_Long_Term_Trajectory_Prediction_CVPR_2022_paper.pdf)
- M2I: From Factored Marginal Trajectory Prediction to Interactive Prediction [[2022 CVPR]](https://openaccess.thecvf.com/content/CVPR2022/papers/Sun_M2I_From_Factored_Marginal_Trajectory_Prediction_to_Interactive_Prediction_CVPR_2022_paper.pdf)
- On Adversarial Robustness of Trajectory Prediction for Autonomous Vehicles [[2022 CVPR]](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhang_On_Adversarial_Robustness_of_Trajectory_Prediction_for_Autonomous_Vehicles_CVPR_2022_paper.pdf)
- Neural Prior for Trajectory Estimation [[2022 CVPR]](https://openaccess.thecvf.com/content/CVPR2022/papers/Wang_Neural_Prior_for_Trajectory_Estimation_CVPR_2022_paper.pdf)