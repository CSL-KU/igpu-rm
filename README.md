# Real-Time Computing Infrastructure for Integrated CPU-GPU SoC Platforms

Intelligent Cyber-Physical Systems (CPS), such as autonomous cars and drones, demand high computing performance to process massive amount of real-time data while also keeping their size, weight, power and cost to an acceptable level. Graphics processing unit (GPU) is specially designed hardware to efficiently process such large data. Therefore, GPUs are increasingly being integrated in new generations of computer chips. Unfortunately, such integrated chips often exhibit unpredictable timing behaviors---due to unregulated use of shared hardware resources—that can prevent timely execution of critical tasks. This project is focusing on creating a new real-time computing infrastructure for GPU integrated computer chips to provide predictable timing and high-performance. 

## Artifacts
* [Anytime-Lidar](https://github.com/CSL-KU/Anytime-Lidar): Deadline-aware 3D Object Detection
* [DeepPicarMicro](https://github.com/CSL-KU/DeepPicarMicro): Applying TinyML to Autonomous Cyber Physical Systems
* [GTCOS-DoS](https://github.com/mbechtel2/GTCOS-DoS): Denial-of-Service Attacks on Shared Resources in Intel's Integrated CPU-GPU Platforms
* [MemoryAware-DoS](https://github.com/mbechtel2/MemoryAwareDOS): Memory-Aware Cache DOS Attacks
* [RTG-Sync](https://github.com/ahmedius2/RTG-Sync): Virtual Gang based Scheduling of Parallel Real-Time Tasks
* [BRU](https://github.com/CSL-KU/bru-firesim): Bandwidth Regulation Unit (BRU) for RISC-V
* [RT-Gang](https://github.com/CSL-KU/RT-Gang): RT-Gang: Real-Time Gang Scheduling for Safety Critical Systems
* [NVDLA-FireSim](https://github.com/CSL-KU/firesim-nvdla): NVIDIA Deep Learning Accelerator (NVDLA) Integrated with RISC-V SoC on the Amazon FPGA Cloud
* [BWLOCK++](https://github.com/wali-ku/BWLOCK-GPU): Real-Time GPU kernel protection mechanism for Integrated CPU-GPU SoC
* [DeepPicar](https://github.com/mbechtel2/DeepPicar-v2): End-to-end deep learning based autonomous RC car.

## Publications

* [C] Ahmet Soyyigit, Shuochao Yao and Heechul Yun. Anytime-Lidar: Deadline-aware 3D Object Detection. IEEE International Conference on Embedded and Real-Time Computing Systems and Applications (RTCSA), 2022 [paper](http://www.ittc.ku.edu/~heechul/papers/anytime_lidar-rtcsa2022-camera.pdf) 
* [C] Michael Bechtel, Qitao Weng and Heechul Yun. DeepPicarMicro: Applying TinyML to Autonomous Cyber Physical Systems. IEEE International Conference on Embedded and Real-Time Computing Systems and Applications (RTCSA), 2022 [paper](http://www.ittc.ku.edu/~heechul/papers/DeepPicarMicro-rtcsa2022-camera.pdf), [hackers.io](https://www.hackster.io/news/deeppicarmicro-crams-nvidia-s-pilotnet-autonomous-vehicle-neural-network-into-a-raspberry-pi-pico-2a0b8a38e18e)
* [C] Michael Garrett Bechtel and Heechul Yun. Denial-of-Service Attacks on Shared Resources in Intel’s Integrated CPU-GPU Platforms. IEEE International Symposium on Real-Time Distributed Computing (ISORC), 2022 [paper](http://www.ittc.ku.edu/~heechul/papers/intelcpugpuattack-isorc2022-camera.pdf)
* [J] Michael Garrett Bechtel and Heechul Yun. Memory-Aware Denial-of-Service Attacks on Shared Cache in Multicore Real-Time Systems. IEEE Transactions on Computers, 2021. [paper](http://www.ittc.ku.edu/~heechul/papers/hp_attack-tc2021.pdf)
* [C] Shengzhong Liu, Shuochao Yao, Xinzhe Fu, Huajie Shao, Rohan Tabish, Simon Yu, Ayoosh Bansal, Heechul Yun, Lui Sha, Tarek Abdelzaher. Taming Algorithmic Priority Inversion in Mission-critical Perception Pipelines. Communications of ACM, 2022 
* [C] Bansal, A., Yu, S., Kim, H., Li, B., Hovakimyan, N., Caccamo, M. and Sha, L., 2022. Synergistic Redundancy: Towards Verifiable Safety for Autonomous Vehicles. arXiv preprint arXiv:2209.01710. Under review at IEEE Conference on Secure and Trustworthy Machine Learning (SaTML) 2023.
* [C] Bansal, A., Kim, H., Yu, S., Li, B., Hovakimyan, N., Caccamo, M. and Sha, L., 2022. Verifiable Obstacle Detection. arXiv preprint arXiv:2208.14403. Accepted for publication at the 33rd IEEE International Symposium on Software Reliability Engineering (ISSRE) 2022.
* [J] Shengzhong Liu, Shuochao Yao, Xinzhe Fu, Huajie Shao, Rohan Tabish, Simon Yu, Ayoosh Bansal, Heechul Yun, Lui Sha, Tarek Abdelzaher. Real-Time Task Scheduling for Machine Perception in In Intelligent Cyber-Physical Systems. IEEE Transactions on Computers, 2021
* [J] Rohan Tabish, Jen-Yang Wen, Rodolfo Pellizzoni, Renato Mancuso, Heechul Yun, Marco Caccamo, Lui Raymond Sha. An analyzable inter-core communication framework for high-performance multicore embedded systems. Journal of Systems Architecture, 2021
* [C] Waqar Ali, Rodolfo Pellizzoni, Heechul Yun. Virtual Gang based Scheduling of Parallel Real-Time Tasks. Design, Automation and Test in Europe Conference (DATE), February 2021. [[paper](http://www.ittc.ku.edu/~heechul/papers/virtualgang-date2020-camera.pdf)] [[slides](http://www.ittc.ku.edu/~heechul/papers/2021-01-VirtualGang-DATE21-wali-v2.pdf)]
* [C] Shengzhong Liu, Shuochao Yao, Xinzhe Fu, Rohan Tabish, Simon Yu, Ayoosh Bansal, Heechul Yun, Lui Sha and Tarek Abdelzaher. On Removing Algorithmic Priority Inversion from Mission-critical Machine Inference Pipelines. IEEE Real-Time Systems Symposium (RTSS), December 2020. (Best Paper Award)
* [C] Homa Aghilinasab, Waqar Ali, Heechul Yun, Rodolfo Pellizzoni. Dynamic Memory Bandwidth Allocation for Real-Time GPU-Based SoC Platforms. ACM/IEEE Intl. Conference on Embedded Software (EMSOFT), September 2020
* [C] Rohan Tabish, Jen-Yang Wen, Rodolfo Pellizzoni, Renato Mancuso, Heechul Yun, Marco Caccamo and Lui Sha. SCE-Comm: A Real-Time Inter-Core Communication Framework for Strictly Partitioned Multi-core Processors. Mediterranean Conference on Embedded Computing (MECO), June 2020
* [C] Farzad Farshchi, Qijing Huang, and Heechul Yun. BRU: Bandwidth Regulation Unit for Real-Time Multicore Processors. IEEE Intl. Conference on Real-Time and Embedded Technology and Applications Symposium (RTAS), April 2020. [[paper](http://www.ittc.ku.edu/~heechul/papers/bru-rtas2020-camera.pdf)] [[slides](http://www.ittc.ku.edu/~heechul/papers/bru-rtas2020-slides.pdf)]
* [O] Waqar Ali, Rodolfo Pellizzoni, Heechul Yun. Virtual Gang based Scheduling of Real-Time Tasks on Multicore Platforms, arXiv preprint arXiv:1912.10959, February 2020. [[arXiv](https://arxiv.org/abs/1912.10959)]
* [W] Waqar Ali, Michael Bechtel and Heechul Yun. "Analyzable and Practical Real-Time Gang Scheduling on Multicore Using RT-Gang," _Workshop on Operating Systems Platforms for Embedded Real-Time applications (OSPERT)_, July 2019. [[abstract](http://www.ittc.ku.edu/~heechul/papers/rtgang-ospert2019-abstract.pdf)] [[slides](http://www.ittc.ku.edu/~heechul/papers/rtgang-ospert2019-slides.pdf)]
* [C] Waqar Ali and Heechul Yun. "RT-Gang: Real-Time Gang Scheduling Framework for Safety-Critical Systems," _IEEE Intl. Conference on Real-Time and Embedded Technology and Applications Symposium (RTAS)_, 2019 [[paper](http://www.ittc.ku.edu/~heechul/papers/rtgang-rtas2019-camera.pdf)][[slides](http://www.ittc.ku.edu/~heechul/papers/rtgang-rtas2019-slides.pdf)]
* [W] Farzad Farshchi, Qijing Huang, and Heechul Yun. "Integrating NVIDIA Deep Learning Accelerator (NVDLA) with RISC-V SoC on FireSim," _Workshop on Energy Efficient Machine Learning and Cognitive Computing for Embedded Applications (EMC^2)_, 2019. [[paper](http://www.ittc.ku.edu/~heechul/papers/nvdla-emc2019-camera.pdf)] [[slides](http://www.ittc.ku.edu/~heechul/papers/nvdla-emc2019-slides.pdf)]
* [C] Waqar Ali, Heechul Yun. "Protecting Real-Time GPU Applications on Integrated CPU-GPU SoC Platforms," _Euromicro Conference on Real-Time Systems (ECRTS)_, 2018 [[paper](http://drops.dagstuhl.de/opus/volltexte/2018/8983/pdf/LIPIcs-ECRTS-2018-19.pdf)] [[slides](https://www.slideshare.net/saiparan/protecting-realtime-gpu-kernels-in-integrated-cpugpu-soc-platforms-104996587)]
* [C] Michael Garrett Bechtel, Elise McEllhiney, Minje Kim, Heechul Yun. "DeepPicar: A Low-cost Deep Neural Network-based Autonomous Car." _IEEE International Conference on Embedded and Real-Time Computing Systems and Applications (RTCSA)_, 2018 [[paper]](https://arxiv.org/pdf/1712.08644.pdf) [[slides](https://www.slideshare.net/saiparan/protecting-realtime-gpu-kernels-in-integrated-cpugpu-soc-platforms-104996587)]


## People

#### Faculty 
  * [Heechul Yun](https://ittc.ku.edu/~heechul), KU
  * [Lui Sha](http://publish.illinois.edu/cpsintegrationlab/people/lui-sha/), UIUC

#### Students
  * Waqar Ali, KU
  * Michael Garrett Bechtel, KU
  * Farzad Farshchi, KU
  * Ayoosh Bansal, UIUC
  * Rohan Tabish, UIUC
  
## Sponsor

* National Science Foundation (NSF): [CNS-1815959](https://nsf.gov/awardsearch/showAward?AWD_ID=1815959&HistoricalAwards=false)
