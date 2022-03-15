![avatar](./536781636098208_.pic_hd.jpg)
![avatar](./29771647309659_.pic.jpg)


<!-- ## Octopus: Versatile Wideband MIMO Sensing Platform for Edge Intelligence in AIoT -->
<div align='center' ><font size='5'>Octopus: Versatile Wideband MIMO Sensing Platform for Edge Intelligence in AIoT</font></div><br>
<!-- <center>Organizers: Jun Luo, Zhe Chen, Zhiping Jiang</center> -->

<div align='center'><font size='4'>Organizers: Jun Luo, Zhe Chen, Zhiping Jiang </font></div><br>

### News and Announcements
Despite the best efforts of the whole organizing committee, the tail of the pandemic is preventing us from running CPS-IoT Week with an in-person component, as we planned originally. CPS-IoT Week will therefore run as a virtual event. Opting for this choice instead of a hybrid event was a tough decision where we had to strike a balance among several constraints. Detailed information, including registration options, will be available shortly on the website of CPS-IoT Week and of all its conferences and related events.


### Introduction
Radio frequency (RF) technologies have changed our world and obtained a significant success in both communication and sensing. On one hand, a wide range of RF signals have been employed for wireless communication such as Wi-Fi and LTE, delivering a ubiquitous connectivity to us. On the other hand, RF signals are further exploited for sensing in recent year, and promising progress has since been achieved. Novel sensing models and algorithms have been developed for user localization or tracking, human activities/gesture recognition, and vital signs monitoring. Compared with traditional device-based sensing approaches, RF sensing has the unique advantages of being both device-free and contact-free.

Though promising, most sensing solutions are hosted on Commercial Off-The-Shelf (COTS) chipset such as Wi-Fi cards and Software Defined Radio (SDR) platforms. However, the high-end hardware components (e.g., the high sampling rate ADCs) of SDR platforms are prohibitively expensive and hence unlikely to be available on commodity hardware. Therefore, the better performance of SDR can hardly be relevant to real-life deployments. Meanwhile, great efforts have been devoted to Wi-Fi sensing using Intel and Atheros Wi-Fi chipsets. While optimistic results have been achieved in controlled setups under lab environments, severe performance degradation caused by the communication-oriented design of Wi-Fi may take place in real-life deployments. Finally, most up-to-date RF sensing systems do not operate in a standalone basis, as they often require an external computing device to perform signal processing. This seriously limits their ability in wide-scale edge deployments.

Octopus as a compact and programmable wideband MIMO platform dedicated to RF sensing. It aims to tackle all the aforementioned challenges faced by existing platforms, by exploiting, in particular, ultra-wideband (UWB) radio, large-scale MIMO, and a standalone implementation with inexpensive commercial-grade components. Essentially, Octopus leverages its novel RF components (including both IR-UWB radios and MIMO antenna arrays) to obtain RF In-phase and Quadrature (IQ) baseband signal samples. Under the standalone mode, these samples are processed only by the hardware and software computing modules of Octopus. 

The hardware component formed by FPGA-ARM heterogeneous computing modules contains DSP and AI libraries (e.g., FFT and neural networks) to accelerate essential data processing. It also a reconfigurable ability, allowing different applications to be flexibly (re)deployed. The software component executes control function to, for example, toggle Octopus between sleep and active modes for energy saving, and it also facilitate the deployments of standalone applications. If necessary, Octopus can offload IQ baseband samples to a host computer for quickly verifying proof-of-concept prototypes. Therefore, Octopus is capable of closing the gap between novel sensing techniques and realistic deployment requirements, and it may open up new opportunities for RF sensing design and development.

Octopus, with its multiple variations, is developed by Nanyang Technological University and is now produced by [AIWiSe](https://aiwise.wirush.ai/), a spinoff under Singapore-China International Joint Research Institute. Its software framework is freely accessible by anybody in the research community at [Octopus](https://github.com/DeepWiSe888/Octopus). We believe that a tutorial on Octopus is timely and relevant to the CPS-IoT community as it should provide attendees with a clear introduction on how to access the hardware/software of it, as well as how to deploy innovative deep learning modules so as to enable AIoT applications on it. Particularly, using several of our recently publications as examples, we will demonstrate how to apply Octopus in a set of relevant scenarios including human activity recognition, vital signs monitoring, general vibration sensing, and RF-imaging. Essentially, we aim to showcase a full-cycle development of AI-driven RF sensing applications, including design, configuration, programming, experiments, and test, all based on a compact platform.

As a middleware component of the overall Octopus ecosystem, [PicoScenes](https://ps.zpj.io) is versatile and powerful in supporting general RF sensing research. It helps researchers to overcome two key barriers: inadequate sensing hardware and incapable measurement software. In hardware aspect, PicoScenes accommodates most models of RF sensing hardware including various versions of Octopus, commercial Wi-Fi NICs, and USRP. In software aspect, PicoScenes supports the plugin mechanism by which users can prototype interactive and complex baseband measurements. It also supports multi-device concurrent measurements, significantly simplifying MIMO-driven baseband measurements.



### Knowledge that the Audience will Gather with the Tutorial
We will explain the fundamentals of RF-sensing and how Octopus approaches it with its compact yet versatile design. Then we use our hands-on experience to demonstrate how these components can be leveraged to construct various edge sensing capabilities for AIoT applications. By the end of the tutorial the attendees will have a unified view on the variety of RF sensing techniques/platforms; they will learn how Octopus performs RF-sensing differently from existing proposals, which makes it practical for edge deployment in AIoT scenarios; the will also how to readily access the functionalities provided by Octopus (partially supported by PicoScenes) and hence ready to adopt it for their own developments.

<!-- As we are not sure if we can make it to the conference site for an in-person presentation, the tutorial is currently schedule as an online one, though adapting it to an in-person tutorial is very straightforward. Because Octopus is not a pure software platform, we may not be able to let the attendees to experience via hands-on experiments, so we plan to conduct simple demonstrations that can be readily understandable even in the online mode. -->

The tutorial is currently schedule as an online one. Octopus is not a pure software platform, we may not be able to let the attendees to experience via hands-on experiments, so we plan to conduct simple demonstrations that can be readily understandable even in the online mode.

### Format

The Octopus tutorial is scheduled as a half-day tutorial (4 hours), organized into two sessions.

The first session will be made up of two presentations followed by a Q&A. It will include an introduction to a unified RF sensing model and how it is leveraged in Octopus, followed by another discussion on AI-driven RF sensing, and how to deploy these AI modules into Octopus to enable various edge sensing capabilities. This session will be conducted by Prof. Luo, and a short Q&A is allocated to solve question concerning the first session.

The second session focuses on Octopus itself, providing more technical details about how it is constructed and how to make use of its individual components. We would also like to introduce PicoScenes, a middleware component of the overall Octopus ecosystem, simultaneously supporting both radar and Wi-Fi sensing (including USRP). This is then followed by a few demonstrations conducted according to the sensing capabilities discussed in earlier sessions. We also plan to have a final Q&A at the end of the tutorial to address questions towards the whole tutorial, while providing guidelines and support for the researchers who are interested to adopt Octopus for their research. This session will be jointed conducted by Dr. Chen and Dr. Jiang, but all three organizers will be there to address the overall questions.


### Tentative Schedule

| Time         | Topic |
| ----------- | ----------- |
| 9.00am - 10.15am      | Session 1|
| 10.15am - 10.30am| Break |
| 10.30am - 11.30am | Session 2 |
| 11.30am - 11.45am| Break |
| 11.45am - 12.45am | Session 3 |

### Organizer Bios
Prof. Jun Luo is a tenured professor in the School of Computer Science and Engineering, Nanyang Technological University (NTU) in Singapore. He has spent the past 20 years in developing networked computing and sensing systems for serving IoT applications, and his current research interests include mobile and pervasive computing, machine learning and computer vision, as well as applied operations research. He has served in the TPC and Editorial Board of several international conferences and journals, including an Area TPC Chair for IEEE INFOCOM. More information can be found [here](https://personal.ntu.edu.sg/junluo). 

Dr. Zhe Chen is the Co-Founder of [AIWiSe Ltd. Inc.](https://aiwise.wirush.ai/). He obtained his PhD degree from Fudan University, China, with a 2019 ACM SIGCOMM Doctoral Dissertation Award. Before joining AIWiSe, he worked as a research fellow in NTU for two years, and his research achievements, along with his efforts in launching products based on them, have thus earned him 2021 ACM SIGMOBILE Rising Star Award recently. His current research interests including wireless networking, mobile and pervasive computing, and embedded systems. More information can be found [here](https://rabbitnick.github.io). 

Dr. Zhiping Jiang is a Lecturer in the School of Computer Science and Technology, Xidian University, Xi’an, China. He has published 30 papers in Wi-Fi/RFID/acoustic-based wireless sensing. Since 2018, he and his team have started developing the PicoScenes Wi-Fi sensing middleware and high-performance Wi-Fi baseband implementation for SDR. His current research interests include wireless sensing, pervasive computing, wireless/ acoustic wideband communication, and embedded system. More information can be found [here](https://zpj.io).


