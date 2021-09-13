# The advanced work of Object detection based on FPGAs

This repository provides an up-to-date the list of studies, which is the advanced work of object detection based on FPGAs. We plan to update the platform in the long term. It follows the taxonomy provided in the following paper (please cite the paper if you benefit from this repository):

Tao S, Kai Z, Zhe C, Qian M, Jiawen W, Lu W, "FPGA-based accelerator for object detection:A comprehensive review"

## How to request addition of a paper

If you know of a paper that addresses an imbalance problem concerning generic object detection and is not on this repository, you are welcome to request the addition of that paper by submitting a pull request. In your pull request please briefly state which section of your paper is related to which problem.

Following the methodology in our paper, the papers should be designed for the generic object detection problem (i.e. reporting results on generic object detection datasets such as ILSVRC, Pascal VOC, MS-COCO, Open Images, Objects 365 etc.).

# Table of Contents (Follows the taxonomy in the paper)

1. [Target detection under traditional methods](#1-target-detection-under-traditional-methods)
2. [Target detection under the deep learning method](#2-target-detection-under-the-deep-learning-method)

# 1. Target detection under traditional methods

- [NOVEL FPGA BASED HAAR CLASSIFIER FACE DETECTION ALGORITHM ACCELERATION](https://github.com/vivian13maker/FPGA-based-accelerator-for-object-detection-A-comprehensive-review/blob/main/NOVEL%20FPGA%20BASED%20HAAR%20CLASSIFIER%20FACE%20DETECTION%20ALGORITHM%20ACCELERATION.md#novel-fpga-based-haar-classifier-face-detection-algorithm-acceleration), [[paper]](https://www.researchgate.net/profile/Shih-Lien-Lu/publication/4375375_Novel_FPGA_based_Haar_classifier_face_detection_algorithm_acceleration/links/0fcfd50933e992036b000000/Novel-FPGA-based-Haar-classifier-face-detection-algorithm-acceleration.pdf?origin=publication_detail)
- [Multichannel Pulse-Coupled-Neural-Network-Based Color Image Segmentation for Object Detection](https://github.com/vivian13maker/FPGA-based-accelerator-for-object-detection-A-comprehensive-review/blob/main/Multichannel%20Pulse-Coupled-Neural-Network-Based%20Color%20Image%20Segmentation%20for%20Object%20Detection.md#multichannel-pulse-coupled-neural-network-based-color-image-segmentation-for-object-detection), [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=5991960)
- [A Flexible Parallel Hardware Architecture for AdaBoost-Based Real-Time Object Detection](https://github.com/vivian13maker/FPGA-based-accelerator-for-object-detection-A-comprehensive-review/blob/main/A%20Flexible%20Parallel%20Hardware%20Architecture%20for%20AdaBoost-Based%20Real-Time%20Object%20Detection.md#a-flexible-parallel-hardware-architecture-for-adaboost-based-real-time-object-detection), [[paper]](http://islab.soe.uoguelph.ca/sareibi/TEACHING_dr/ENG6530_RCS_html_dr/outline_W2017/docs/PAPER_REVIEW_dr/2014_dr/GRAD_dr/FPGA_Object_Detection.pdf)
- [ASIC and FPGA Implementation of the Gaussian Mixture Model Algorithm for Real-Time Segmentation of High Definition video](https://github.com/vivian13maker/FPGA-based-accelerator-for-object-detection-A-comprehensive-review/blob/main/ASIC%20and%20FPGA%20Implementation%20of%20the%20Gaussian%20Mixture%20Model%20Algorithm%20for%20Real-Time%20Segmentation%20of%20High%20Definition%20video.md#asic-and-fpga-implementation-of-the-gaussian-mixture-model-algorithm-for-real-time-segmentation-of-high-definition-video), [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6481463)
- [A Multi-Resolution FPGA-Based Architecture for Real-Time Edge and Corner Detection](https://github.com/vivian13maker/FPGA-based-accelerator-for-object-detection-A-comprehensive-review/blob/main/A%20Multi-Resolution%20FPGA-Based%20Architecture%20for%20Real-Time%20Edge%20and%20Corner%20Detection.md#a-multi-resolution-fpga-based-architecture-for-real-time-edge-and-corner-detection), [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6532283&tag=1)
- [Real-time DDoS attack detection using FPGA](https://github.com/vivian13maker/FPGA-based-accelerator-for-object-detection-A-comprehensive-review/blob/main/Real-time%20DDoS%20attack%20detection%20using%20FPGA.md#real-time-ddos-attack-detection-using-fpga), [[paper]](https://pdf.sciencedirectassets.com/271515/1-s2.0-S0140366417X00145/1-s2.0-S0140366416306442/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLWVhc3QtMSJHMEUCIQDroCWGkQN2XzrnwGlmWFagrg%2FRRsU05YF2%2FVUxL1P1hwIgIh2w8AwG%2BTnjOVKUOa9WTeafQZG%2FzWpWHoBASsK6jNIqgwQI1P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAEGgwwNTkwMDM1NDY4NjUiDEDjcyYQxCR6tZrWtCrXA2j%2FQZudCQismE7Xxvc1Z3rL7l1c3wBIj%2BXSlBDaHNjjM%2F0VGzycSbtKXSrXqwaMpxq952ZHEVVV6fc%2BRBALq2uG1cuMHZsDp%2B%2FjvbXYduyH4irAK%2BmOPTSVL9LaWg9RJq0qQg5aEqv1KbBdAsXikVsWS7%2BfY0iWjpPTLD0j%2F4GeYsHQmZdyFBM6x6boxArlQeE0iUuSrJBxhkdWMR6sbuPJQI%2BR462dVjJ2ZfbgCuRey19Zg3sPyAZr0V4Hn%2BwzwyES3oRUDdirTekq%2BEI8mKkazzKLtrLcP2f3lurv37%2F2mEOiCxDRRXx6yqJxQaipllz2dHkp0oEmEb%2FxOxZ%2F1xva5AH92HiET%2FF%2FisU36jF7plkSZUW%2BpHsRgaZsxA%2FPZQap248lZTxUbvt9Mqdwwd2Ab4WDJHPeJnIeM4rf%2Bm4CiZmaugV6Yro%2BO25%2FZqRUURwjoguLjAeKJtLDRfB9QuBGaYokOTI9C0wh8LQoK4hYCYU6r1q1sn4PjPVFGC7laYnjtd9YNVnOkpqcFawGnHLw4G0M2gOMr0buR3KGddiPXkOeLSi7pb3m3HdsyDM%2BIZEo9b%2BCcAx%2F77jNrMsHywKWcPCODpgM6scIauRmhnRAJ%2BodyGfqnjDS5OyJBjqlAfQHx683tsTAPt47PHofPBHAsCvHYCR6mFfbVWombgLQB4zEPVS5c7eGf%2B05MuY87XWqEjmI%2F6x2Qy%2Bs%2BEckVbHBn5nF4DWk9pLb1XilnFXbuzv%2BtR8o9lQxgsKvRzZKa7u26Uzmf9O6nQQ0PLzeNZPyEB9AMnLmFxPp3AxftPsLytIqpvzUd87BHPOkKevKOLmt%2BnmgKiDPxV4%2BdLEvHBtWFBf5CQ%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20210910T115637Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTY5LL4ONHX%2F20210910%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=473fd4c0343cd4decf36e9b537261e1b1c7184b40d35e7a256c7cfcc9f5a0dae&hash=5672e07fbb7e7f767e2d43907a2ce5ba3b82ed6298ef94d6f70127df0c44cc0a&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S0140366416306442&tid=spdf-440306f7-5d6b-47a6-a8ba-597231133837&sid=405589e954c7e4489209b4b6469f22e8ab85gxrqa&type=client)
- [An efficient and cost effective FPGA based implementation of the Viola-Jones face detection algorithm](https://github.com/vivian13maker/FPGA-based-accelerator-for-object-detection-A-comprehensive-review/blob/main/An%20efficient%20and%20cost%20effective%20FPGA%20based%20implementation%20of%20the%20Viola-Jones%20face%20detection%20algorithm.md#an-efficient-and-cost-effective-fpga-based-implementation-of-the-viola-jones-face-detection-algorithm), [[paper]](https://pdf.sciencedirectassets.com/314097/1-s2.0-S2468067217X00023/1-s2.0-S2468067216300116/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLWVhc3QtMSJHMEUCIQDroCWGkQN2XzrnwGlmWFagrg%2FRRsU05YF2%2FVUxL1P1hwIgIh2w8AwG%2BTnjOVKUOa9WTeafQZG%2FzWpWHoBASsK6jNIqgwQI1P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAEGgwwNTkwMDM1NDY4NjUiDEDjcyYQxCR6tZrWtCrXA2j%2FQZudCQismE7Xxvc1Z3rL7l1c3wBIj%2BXSlBDaHNjjM%2F0VGzycSbtKXSrXqwaMpxq952ZHEVVV6fc%2BRBALq2uG1cuMHZsDp%2B%2FjvbXYduyH4irAK%2BmOPTSVL9LaWg9RJq0qQg5aEqv1KbBdAsXikVsWS7%2BfY0iWjpPTLD0j%2F4GeYsHQmZdyFBM6x6boxArlQeE0iUuSrJBxhkdWMR6sbuPJQI%2BR462dVjJ2ZfbgCuRey19Zg3sPyAZr0V4Hn%2BwzwyES3oRUDdirTekq%2BEI8mKkazzKLtrLcP2f3lurv37%2F2mEOiCxDRRXx6yqJxQaipllz2dHkp0oEmEb%2FxOxZ%2F1xva5AH92HiET%2FF%2FisU36jF7plkSZUW%2BpHsRgaZsxA%2FPZQap248lZTxUbvt9Mqdwwd2Ab4WDJHPeJnIeM4rf%2Bm4CiZmaugV6Yro%2BO25%2FZqRUURwjoguLjAeKJtLDRfB9QuBGaYokOTI9C0wh8LQoK4hYCYU6r1q1sn4PjPVFGC7laYnjtd9YNVnOkpqcFawGnHLw4G0M2gOMr0buR3KGddiPXkOeLSi7pb3m3HdsyDM%2BIZEo9b%2BCcAx%2F77jNrMsHywKWcPCODpgM6scIauRmhnRAJ%2BodyGfqnjDS5OyJBjqlAfQHx683tsTAPt47PHofPBHAsCvHYCR6mFfbVWombgLQB4zEPVS5c7eGf%2B05MuY87XWqEjmI%2F6x2Qy%2Bs%2BEckVbHBn5nF4DWk9pLb1XilnFXbuzv%2BtR8o9lQxgsKvRzZKa7u26Uzmf9O6nQQ0PLzeNZPyEB9AMnLmFxPp3AxftPsLytIqpvzUd87BHPOkKevKOLmt%2BnmgKiDPxV4%2BdLEvHBtWFBf5CQ%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20210910T120116Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTY5LL4ONHX%2F20210910%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=0875b362da97b104ef03d345a75fb2c4201dbf6e0286ebfd29eaf0ac80b4c008&hash=0c16728afe2ae300224ec939217fe40889d3e90251ac9a58a0489ce2934af946&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S2468067216300116&tid=spdf-72c81ead-0663-4bd5-86dd-591e268a547d&sid=405589e954c7e4489209b4b6469f22e8ab85gxrqa&type=client)
- [FPGA-Based Real-Time Moving Target Detection System for Unmanned Aerial Vehicle Application](https://github.com/vivian13maker/FPGA-based-accelerator-for-object-detection-A-comprehensive-review/blob/main/FPGA-Based%20Real-Time%20Moving%20Target%20Detection%20System%20for%20Unmanned%20Aerial%20Vehicle%20Application.md#fpga-based-real-time-moving-target-detection-system-for-unmanned-aerial-vehicle-application), [[paper]](https://downloads.hindawi.com/journals/ijrc/2016/8457908.pdf)
- [FPGA acceleration of Hyperspectral Image Processing for High-Speed Detection Applications](https://github.com/vivian13maker/FPGA-based-accelerator-for-object-detection-A-comprehensive-review/blob/main/FPGA%20acceleration%20of%20Hyperspectral%20Image%20Processing%20for%20High-Speed%20Detection%20Applications.md#fpga-acceleration-of-hyperspectral-image-processing-for-high-speed-detection-applications), [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8050773)
- [Energy-Efficient Pedestrian Detection System: Exploiting Statistical Error Compensation for Lossy Memory Data Compression](https://github.com/vivian13maker/FPGA-based-accelerator-for-object-detection-A-comprehensive-review/blob/main/Energy-Efficient%20Pedestrian%20Detection%20System%20Exploiting%20Statistical%20Error%20Compensation%20for%20Lossy%20Memory%20Data%20Compression.md#energy-efficient-pedestrian-detection-system-exploiting-statistical-error-compensation-for-lossy-memory-data-compression), [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8310932)
- [Real-time hardware–software embedded vision system for ITS smart camera implemented in Zynq SoC](https://github.com/vivian13maker/FPGA-based-accelerator-for-object-detection-A-comprehensive-review/blob/main/Real-time%20hardware%E2%80%93software%20embedded%20vision%20system%20for%20ITS%20smart%20camera%20implemented%20in%20Zynq%20SoC.md#real-time-hardwaresoftware-embedded-vision-system-for-its-smart-camera-implemented-in-zynq-soc), [[paper]](https://link.springer.com/content/pdf/10.1007/s11554-016-0588-9.pdf)
- [Towards a Scalable Hardware/Software Co-Design Platform for Real-time Pedestrian Tracking Based on a ZYNQ-7000 Device](https://github.com/vivian13maker/FPGA-based-accelerator-for-object-detection-A-comprehensive-review/blob/main/Towards%20a%20Scalable%20HardwareSoftware%20Co-Design%20Platform%20for%20Real-time%20Pedestrian%20Tracking%20Based%20on%20a%20ZYNQ-7000%20Device.md#towards-a-scalable-hardwaresoftware-co-design-platform-for-real-time-pedestrian-tracking-based-on-a-zynq-7000-device), [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8307853)

# 2. Target detection under the deep learning method

- [A Lightweight YOLOv2: A Binarized CNN with A Parallel Support Vector Regression for an FPGA](https://github.com/vivian13maker/FPGA-based-accelerator-for-object-detection-A-comprehensive-review/blob/main/A%20Lightweight%20YOLOv2%20A%20Binarized%20CNN%20with%20A%20Parallel%20Support%20Vector%20Regression%20for%20an%20FPGA.md#a-lightweight-yolov2-a-binarized-cnn-with-a-parallel-support-vector-regression-for-an-fpga), [[paper]](https://dl.acm.org/doi/pdf/10.1145/3174243.3174266)
- [A High-Throughput and Power-Efficient FPGA Implementation of YOLO CNN for Object Detection](https://github.com/vivian13maker/FPGA-based-accelerator-for-object-detection-A-comprehensive-review/blob/main/A%20High-Throughput%20and%20Power-Efficient%20FPGA%20Implementation%20of%20YOLO%20CNN%20for%20Object%20Detection.md#a-high-throughput-and-power-efficient-fpga-implementation-of-yolo-cnn-for-object-detection), [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8678682)
- [REQ-YOLO A Resource-Aware, Efficient Quantization Framework for Object Detection on FPGAs](https://github.com/vivian13maker/FPGA-based-accelerator-for-object-detection-A-comprehensive-review/blob/main/REQ-YOLO%20A%20Resource-Aware,%20Efficient%20Quantization%20Framework%20for%20Object%20Detection%20on%20FPGAs.md#req-yolo-a-resource-aware-efficient-quantization-framework-for-object-detection-on-fpgas), [[paper]](https://arxiv.org/pdf/1909.13396.pdf)
- [A Real-Time Object Detection Accelerator with Compressed SSDLite on FPGA](https://github.com/vivian13maker/FPGA-based-accelerator-for-object-detection-A-comprehensive-review/blob/main/A%20Real-Time%20Object%20Detection%20Accelerator%20with%20Compressed%20SSDLite%20on%20FPGA.md#a-real-time-object-detection-accelerator-with-compressed-ssdlite-on-fpga), [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8742299)
- [An Object Detector based on Multiscale Sliding Window Search using a Fully Pipelined Binarized CNN on an FPGA](https://github.com/vivian13maker/FPGA-based-accelerator-for-object-detection-A-comprehensive-review/blob/main/An%20Object%20Detector%20based%20on%20Multiscale%20Sliding%20Window%20Search%20using%20a%20Fully%20Pipelined%20Binarized%20CNN%20on%20an%20FPGA.md#an-object-detector-based-on-multiscale-sliding-window-search-using-a-fully-pipelined-binarized-cnn-on-an-fpga), [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8280135)
- [Accelerating Tiny YOLO v3 using FPGA-based Hardware/Software Co-Design](https://github.com/vivian13maker/FPGA-based-accelerator-for-object-detection-A-comprehensive-review/blob/main/Accelerating%20Tiny%20YOLO%20v3%20using%20FPGA-based%20HardwareSoftware%20Co-Design.md#accelerating-tiny-yolo-v3-using-fpga-based-hardwaresoftware-co-design), [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9180843)
- [Angel-Eye: A Complete Design Flow for Mapping CNN Onto Embedded FPGA](https://github.com/vivian13maker/FPGA-based-accelerator-for-object-detection-A-comprehensive-review/blob/main/Angel-Eye%20A%20Complete%20Design%20Flow%20for%20Mapping%20CNN%20Onto%20Embedded%20FPGA.md#angel-eye-a-complete-design-flow-for-mapping-cnn-onto-embedded-fpga), [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7930521)
- [A Novel FPGA Accelerator Design for Real-Time and Ultra-Low Power Deep Convolutional Neural Networks Compared With Titan X GPU](https://github.com/vivian13maker/FPGA-based-accelerator-for-object-detection-A-comprehensive-review/blob/main/A%20Novel%20FPGA%20Accelerator%20Design%20for%20Real-Time%20and%20Ultra-Low%20Power%20Deep%20Convolutional%20Neural%20Networks%20Compared%20With%20Titan.md#a-novel-fpga-accelerator-design-for-real-time-and-ultra-low-power-deep-convolutional-neural-networks-compared-with-titan-x-gpu), [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9108269)
- [SpWA: An Efficient Sparse Winograd Convolutional Neural Networks Accelerator on FPGAs](https://github.com/vivian13maker/FPGA-based-accelerator-for-object-detection-A-comprehensive-review/blob/main/SpWA%20An%20Efficient%20Sparse%20Winograd%20Convolutional%20Neural%20Networks%20Accelerator%20on%20FPGAs.md#spwa-an-efficient-sparse-winograd-convolutional-neural-networks-accelerator-on-fpgas), [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8465842)
- [An Energy-Efficient FPGA-Based Deconvolutional Neural Networks Accelerator for Single Image Super-Resolution](https://github.com/vivian13maker/FPGA-based-accelerator-for-object-detection-A-comprehensive-review/blob/main/An%20Energy-Efficient%20FPGA-Based%20Deconvolutional%20Neural%20Networks%20Accelerator%20for%20Single%20Image%20Super-Resolution.md#an-energy-efficient-fpga-based-deconvolutional-neural-networks-accelerator-for-single-image-super-resolution), [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8584497)
- [A Fully Connected Layer Elimination for a Binarized Convolutional Neural Network on an FPGA](https://github.com/vivian13maker/FPGA-based-accelerator-for-object-detection-A-comprehensive-review/blob/main/A%20Fully%20Connected%20Layer%20Elimination%20for%20a%20Binarized%20Convolutional%20Neural%20Network%20on%20an%20FPGA.md#a-fully-connected-layer-elimination-for-a-binarized-convolutional-neural-network-on-an-fpga), [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8056771)
- [Sparse-YOLO: Hardware/Software Co-Design of an FPGA Accelerator for YOLOv2](https://github.com/vivian13maker/FPGA-based-accelerator-for-object-detection-A-comprehensive-review/blob/main/Sparse-YOLO%20HardwareSoftware%20Co-Design%20of%20an%20FPGA%20Accelerator%20for%20YOLOv2.md#sparse-yolo-hardwaresoftware-co-design-of-an-fpga-accelerator-for-yolov2), [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9122495)
- [LACS: A High-Computational-Efficiency Accelerator for CNNs](https://github.com/vivian13maker/FPGA-based-accelerator-for-object-detection-A-comprehensive-review/blob/main/LACS%20A%20High-Computational-Efficiency%20Accelerator%20for%20CNNs.md#lacs-a-high-computational-efficiency-accelerator-for-cnns), [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8944026)
-  [A new multi-scroll Chua’s circuit with composite hyperbolic tangent-cubic nonlinearity: Complex dynamics, Hardware implementation and Image encryption application](https://github.com/vivian13maker/The-advanced-work-of-Object-detection-based-on-FPGAs/blob/main/A%20new%20multi-scroll%20Chua%E2%80%99s%20circuit%20with%20composite%20hyperbolic%20tangent-cubic%20nonlinearity%20Complex%20dynamics,%20Hardware%20implementation%20and%20Image%20encryption%20application.md#a-new-multi-scroll-chuas-circuit-with-composite-hyperbolic-tangent-cubic-nonlinearity-complex-dynamics-hardware-implementation-and-image-encryption-application), [[paper]](https://pdf.sciencedirectassets.com/271564/1-s2.0-S0167926021X00053/1-s2.0-S0167926021000663/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjENf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLWVhc3QtMSJHMEUCIQC4mre1L12NM3T8s%2BOIGPKfJw%2F36uoGGFXrhPQ8jf%2BmuQIgaZDIAMjeH2Yz0PmbBA0hf95B8mszfMUgm5OFNkbMIYUq%2BgMIMBAEGgwwNTkwMDM1NDY4NjUiDKtqkTaEdFhFdZfQlyrXA0LYbCfntNJ1BO7AcWxpyMOkl6evf6ycYC6WOgyNRQ%2FIPRTPDsJ8H5%2Foox%2BcaR3rGjmpbKxpOBYswW5hCyQzKsll7TH3PeGR8rIXZPNhTuyatx23wsHsdu%2FZP73p0gDB5%2BoGdmAaxOr1Ii3LbP6AcI108r81DVBFqYXjxv9UrWNkjol4ndUbTfZ3x5kMYpqnEcKvkRIyTHx%2FrHdaG1j0bL%2Fw0myvTxy2%2Bya%2B3q0tcQU%2FxYi8Ni1k7rb7O8qe6QKXQazla7mZ%2BzvcrNN11akT%2BvWGwHrrL1Xm1GqCiCGRJS%2FsQw4MD06mlYY1uIyEr2CoOMAzpzguMMwz8h8GZbGLJGLiyB25MWeQN0Llmqehefoe9s2cV%2BznPRHtLSHIXb8Q1bOZdIWRYHGJKcuzb3YqRniiW9gNFKOfRzz5UdQBBiGL3C%2FQY9gHTvUJ8wnHRsLmitQvmcItViaG%2FaFZPHyV21cZDNyJQalKSD%2FiwHQ5MX60DPMKdHZ%2FgnJ%2BDmV1d041FiY2LG754ZwP8bD0VJClmnW0ce4BtmyRiJjs%2F8ew6llguOffYHNPPZTCewCmyfmFGb3Pjoaxf%2BWyLUnEfQuwFrkLXjXF5Offkuv6ICzLpkPI26q19JM8eTCuw%2F2JBjqlAXhCs0pEcONxSXT5Kwbd2I%2B1kfTUvIaeA40%2BPWoPdVWeWjxNfPShYjjgZoE89gzrj%2FIeU6%2BoWOERmES%2Fsdjow3hNkIXDN0OmsQyMvxaeLmkjsdnAtd4z%2Fha9hQv4uik0YB6dbXQfswN7WUtRdAzWG2XXYv22d00BAmigC76f%2F%2Fa2vm8XLsO1yYUF4us4pTgw0%2FjirQ7GUZb2M75DcZ1nEbj21rv%2Baw%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20210913T155307Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTY53S44Q4N%2F20210913%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=6a731e6436933c03f0adb057bbf1c8e620b0722d24b14dd6d411dc4ca451a63c&hash=93668ace5e0bba0a2ab762b7414a44ec2eb4e9f8b510716799a897c8b5090dd4&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S0167926021000663&tid=spdf-724dab76-4710-45e3-bb32-78126f46b369&sid=98e80d873e2c794dad5bd31673eee39b05d5gxrqa&type=client)
-  [A robust and fixed-time zeroing neural dynamics for computing time-variant nonlinear equation using a novel nonlinear activation function](https://github.com/vivian13maker/The-advanced-work-of-Object-detection-based-on-FPGAs/blob/main/A%20robust%20and%20fixed-time%20zeroing%20neural%20dynamics%20for%20computing%20time-variant%20nonlinear%20equation%20using%20a%20novel%20nonlinear%20activation%20function.md#a-robust-and-fixed-time-zeroing-neural-dynamics-for-computing-time-variant-nonlinear-equation-using-a-novel-nonlinear-activation-function), [[paper]](https://pdf.sciencedirectassets.com/271597/1-s2.0-S0925231219X0020X/1-s2.0-S0925231219303935/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEND%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLWVhc3QtMSJGMEQCIEspKihy8mwOpDVKKFtFzS5DDKfTNtUMpw1g%2FWb3Y3wfAiAfFIVnGAOOGhaJaZMW1XHXuf99P5gEF%2BU%2BH8CG9WdexSr6AwgoEAQaDDA1OTAwMzU0Njg2NSIMNOATjMY7B05RKGijKtcDVnZ56ZeNabKKyc8khy1p%2FgJq%2B1TuNvEuwVX6jt8REcGFFlhZmoAIROTBirZAyiDYtHUkZFr8Jq9R%2FdCQSoiP04R3%2Fn5BHeRMHCHOY6MbvqLjhCkZVhAU6ObMQzBa46q5Z3a3Y81fyqU3cQaxZRQrsPXU0cajmeWo7BEcSbimAO51nvJsomDYHTEsnWZlWPWih3nAszIc5qHk6z0JcxiXcSB3bTXHF%2FDIg%2BVEycQVev7NLe%2FnBuAFJtor%2BeVjBE3lqElR4noipu2fzZh8LOk4ZrJb%2F2PzCdiNreG4NwnO%2FNv1TeE%2Bc0oIBLCpopNFaOWIhLWrF1%2BvLKMTNzf8MulFOpfAssCX%2BeWSp2sRueheN9zHfdGENb%2BGEvo1zfMM1YNQyRvNzKr%2Bzo5UHxAaPtuWKd3sJchBKjRjWp%2B%2BrL3qOT12KatCp5C9oalkh%2FPoBdAyc6t4kGdm0RyGwu6PhXDr6k%2FZ0CUD8na3obyO57vCEnMsPlVDzvswarnMisBJ5UDAlLD2IAe8DRH%2FPcHX1KGJgxdoxFgQGzywGcVrDCToGEGzZboOZH%2FCGtwl0uB9Ljh6pF1rhaGj4lKiPrO3EPH%2Bj3rp41fx5DhilAoL8OrAFhK4UKDpkjRxMIL2%2B4kGOqYBJ3dT8A4HftP%2B6S35Opr5Hw%2FaHy4qj11r08q5jTVuxUoauCC89mpv%2FzKG56PXRp760bzQUAd8%2FepDjcoOPX%2FNIPYWDLo7rCKS9raiESlc6nJPB0yXeUybkNL6jdRU8tUMm9%2FRS996gEg2Qf32UYiDAxEIPdO9zMOrq8Uc8u0pihmLjgyr0FCnliGQkO%2BUGfy2SI1NiuVYNv86dCV5xXgymGxA6PngMQ%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20210913T084405Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTYSMKG5QBH%2F20210913%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=ae44f169aadaa4a98adc7ae7a817b2541fdcf70e09120737e2e036eb39113071&hash=803cca3bfa0a86755980c94352f25c4c2ede7493081915ee1e6cdc693d9e5aea&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S0925231219303935&tid=spdf-80700de9-1e32-4ab1-b79d-30a7c86d64e6&sid=4ef55cda9b05b847cf-bb08-cd7b5e0df765gxrqa&type=client
)

# Contact
Please contact Qian M (kmust_mzq@126.com) for your questions about this webpage.
