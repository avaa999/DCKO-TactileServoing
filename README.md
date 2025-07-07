# Dynamic Contrastive Koopman Operator for Tactile Servo of Deformable Linear Objects

## The paper is accepted by IEEE TRANSACTIONS ON INDUSTRIAL ELECTRONICS.

![The proposed framework](pictures/Overview.png)
<!--
## Requirements
The code has been tested under
* Ubuntu 20.04 + NVIDIA GeForce RTX 1080Ti (CUDA 12.2)
* PyTorch 1.12.1

## Environment Setup
### Setup anaconda environment
```
$ conda create --name DCKO python=3.7.6 -y
$ conda activate DCKO
$ pip install -r /path/to/your/requirements.txt
```
-->
## Abstract
Strong nonlinearities and infinite degrees of freedom pose intractable challenges for the manipulation of deformable linear objects (DLOs). This paper proposes a novel modeling method based on a deep Koopman operator for nonlinear systems with high-dimensional inputs, enabling precise tactile servo performance. Initially, a dynamic contrastive learning algorithm is proposed to approximate the Koopman operator for the unknown dynamic system in the embedded space. During the training phase, a dynamic negative sampling strategy based on a task-oriented state distance measurement is employed to ensure consistency between the distance metrics in the embedded and the original spaces. Furthermore, a Koopman-based model predictive controller is developed to compensate for modeling errors, with stability conditions explicitly outlined. Extensive experiments demonstrate that the proposed method  outperforms the representative deep Koopman algorithms in modeling performance, with 17% and 7% improvements in correlation distance measures. In the downstream DLO manipulation task relying on tracking the desired in-hand tactile state, our framework achieves the lowest average tracking error, a 100% following rate, and reduces the inference time to 1/22 of the state-of-the-art method, highlighting its superior prediction and control capabilities in the high- dimensional tactile servoing task.  

## Experiment
The vedio of extensive robotic experiments could be found at [here](https://youtu.be/pHUMUcxe_zc)

![The proposed framework](pictures/hose_following.png)
![The proposed framework](pictures/hose_routing.png)
<!--
## Dataset Preparation

* dataset_DCKO_tactileServo_DLO: Click [here](https://drive.google.com/file/d/18ZH7K1uB_Ob6gg9SgTeLdVKl9XT1iL7-/view?usp=sharing)
-->
