---
layout: single
author_profile: true

feature_section_0:
  image_path: /assets/images/prga_logo.png
  image_link: https://parallel.princeton.edu/prga/
  title: Princeton Reconfigurable Gate Array
  excerpt: >-
    A silicon-proven, open-source project for generating customizable, synthesizable
    FPGA design with complementary, RTL-to-bitstream CAD toolchain.
    <br/>
    <br/>
    [GitHub](https://github.com/PrincetonUniversity/prga){: .btn .btn--primary }
    [Documentation](https://parallel.princeton.edu/prga/){: .btn .btn--primary }
---

# About Me

I am a final-year Ph.D. candidate in the ECE department, Princeton University.
I am supervised by [Prof. David Wentzlaff](https://www.princeton.edu/~wentzlaf/)
who leads the [Princeton Parallel Group](http://parallel.princeton.edu/).

**I am on the job market this year. You can find my latest CV [here](/assets/pdfs/CV.pdf).**

# Vision

The stagnation of transistor scaling has motivated vertical integration
across the conventional abstraction layers.
Software-hardware co-design has shown promising performance and energy
efficiency gains in emerging domains such as artificial intelligence,
edge/IoT, robotics, etc.
However, hardware specialization faces two key challenges: the immense
cost/complexity in VLSI design, and the long time-to-market in chip
manufacturing.
I believe that the keyword to address these challenges is _flexibility_.

Addressing the first challenge, we must revolutionize the hardware design
methodology to achieve _design-time flexibility_.
In particular, design generators with embedded testing and modeling
can greatly speed up design space exploration and tolerate software
uncertainty during software-hardware co-design;
high-level synthesis enables trade-offs between human effort and
quality-of-result;
an inclusive, open-source hardware ecosystem facilitates collaboration,
sharing, and reuse.

Addressing the second challenge, we must provision against 
software/algorithm changes after system deployment, i.e.
achieving _post-fabrication flexibility_.
Reconfigurable architectures are an ideal candidate, yet fine-grained
reconfigurable architectures such as FPGA suffer from low energy/transistor
efficiency, while coarse-grained reconfigurable architectures (CGRA) are
in an early but rapid-growing stage.
The huge design space of reconfigurable architectures is yet to be explored, and
the software support (e.g. compiler) for these novel architectures is also an
exciting field to work on.

<!--
I believe that a thorough understanding of the interplay between VLSI,
architecture, programming model, and applications is the key to advancing the
computing industry.
As such, I spent my Ph.D. gaining insights across multiple disciplines, including:

- Developing and contributing to multiple silicon-proven, open-source hardware
  research platforms such as [PRGA](https://parallel.princeton.edu/prga/)
  and [OpenPiton](http://parallel.princeton.edu/openpiton/).
- Leading multiple chip tapeouts and bringups, including two OS-capable,
  manycore-eFPGA SoCs at 12nm and one microcontroller-eFPGA SoC at 130nm.
- Studying heterogeneous integration and its programming model.

These experiences 
-->

# Projects

{% include feature_section id="feature_section_0" %}

# Publications

## Conference Publications

* **[FPGA'21]** **Ang Li**, David Wentzlaff, _"PRGA: An Open-Source FPGA Research and Prototyping Framework"_, 29th ACM/SIGDA International Symposium on Field-Programmable Gate Arrays, Feb./Mar. 2021 ([ACM DL](https://doi.org/10.1145/3431920.3439294) \| [PDF](http://parallel.princeton.edu/papers/FPGA21-Li.pdf) \| [Recorded Presentation](https://dl.acm.org/doi/10.1145/3431920.3439294#))
* **[FPL'20]** **Ang Li**, Ting-Jung Chang, David Wentzlaff, _"Automated Design
  of FPGAs Facilitated by Cycle-Free Routing"_, 30th International Conference on
  Field-Programmable Logic and Applications, Aug./Sep. 2020
  ([IEEE Xplore](https://doi.org/10.1109/FPL50879.2020.00042) \|
  [PDF](http://parallel.princeton.edu/papers/FPL20-Li.pdf))
* **[ASPLOS'20]** Jonathan Balkind, Katie Lim, Michael Schaffner, Fei Gao, Grigory Chirkov, **Ang Li**, Alexey Lavrov, Tri M. Nguyen, Yaosheng Fu, Florian Zaruba, Kunal Gulati, Luca Benini, and David Wentzlaff, _"BYOC: A "Bring Your Own Core" Framework for Heterogeneous-ISA Research"_, 25th International Conference on Architectural Support for Programming Languages and Operating Systems, Mar. 2020 ([ACM DL](https://dl.acm.org/doi/10.1145/3373376.3378479) \| [PDF](http://parallel.princeton.edu/papers/aspl20-balkind.pdf))
* **[ISLPED'15]** Shuangchen Li, **Ang Li**, Yuan Zhe, Yongpan Liu, Peng Li, Guangyu Sun, Yu Wang, Huazhong Yang, and Yuan Xie, _"Leveraging emerging nonvolatile memory in high-level synthesis with loop transformations"_, International Symposium on Low Port Electronics and Design, Jul. 2015 ([IEEE Xplore](https://ieeexplore.ieee.org/document/7273491))
* **[ASPDAC'15]** Shuangchen Li, **Ang Li**, Yongpan Liu, Yuan Xie, and Huazhong Yang, _"Nonvolatile memory allocation and hierarchy optimization for high-level synthesis"_, 20th Asia and South Pacific Design Automation Conference, Jan. 2015 ([IEEE Xplore](https://ieeexplore.ieee.org/document/7058999))

## Journal Publications

* **[IEEE Micro]** Jonathan Balkind, Ting-Jung Chang, Paul J. Jackson, Georgios Tziantzioulis, **Ang Li**, Fei Gao, Alexey Lavrov, Grigory Chirkov, Jinzheng Tu, Mohammad Shahrad, and David Wentzlaff, "OpenPiton at 5: A Nexus for Open and Agile Hardware Design", IEEE Micro Vol. 40, No. 1, Jul./Aug. 2020 ([IEEE Xplore](https://ieeexplore.ieee.org/document/9099948) \| [PDF](http://parallel.princeton.edu/papers/ieee20-balkind.pdf))

## Workshops and Posters

* **[FPGA'20, Poster]** **Ang Li**, and David Wentzlaff, _"Cycle-Free FPGA Routing Graphs"_, 28th ACM/SIGDA International Symposium on Field-Programmable Gate Arrays, Feb. 2020
* **[OSDA'19, Workshop]** **Ang Li**, and David Wentzlaff, _"PRGA: An
  Open-source Framework for Building and Using Custom FPGAs"_, 1st Workshop on
  Open-Source Design Automation, Mar. 2019
* **[WOSET'18, Workshop]** Jonathan Balkind, Alexey Lavrov, Michael McKeown, Yaosheng Fu, Tri Nguyen, Mohammad Shahrad, **Ang Li**, Katie Lim, Yanqi Zhou, Ting-Jung Chang, Paul Jackson, Adi Fuchs, Samuel Payne, Xiaohua Liang, Matthew Matl, and David Wentzlaff, _"OpenPiton: An Emerging Standard for Open-Source EDA Tool Development"_, Workshop on Open-Source EDA Technology, Nov. 2018
