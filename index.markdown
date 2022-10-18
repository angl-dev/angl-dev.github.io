---
layout: single
title: false
author_profile: true
analytics: true

sidebar:
  - text: <p class="home-nav"><a href="#about-me">About Me</a></p>
  - text: >-
      <p class="home-nav"><a href="#projects">Projects</a></p>
      <ul class="home-nav">
          <li><a href="#feature_prga">PRGA</a></li>
          <li><a href="#feature_duet">Duet</a></li>
          <li><a href="#feature_gem5_duet">Gem5-Duet</a></li>
          <li><a href="#feature_cifer">CIFER</a></li>
          <li><a href="#feature_decades">DECADES</a></li>
          <li><a href="#feature_order">ORDER</a></li>
      </ul>

  - text: <p class="home-nav"><a href="#referred-publications">Publications</a></p>
  - text: <p class="home-nav"><a href="#teaching">Teaching</a></p>

unused:
  - text: <p class="home-nav"><a href="#vision">Vision</a></p>

feature_prga:
  image_path: /assets/images/prga_logo.png
  image_link: https://parallel.princeton.edu/prga/
  title: PRGA - Princeton Reconfigurable Gate Array
  image_position: left
  excerpt: >-
    A silicon-proven, open-source project for generating customized, synthesizable
    FPGA with complementary, RTL-to-bitstream CAD toolchain.
    <br/>
    <br/>
    [<i class="ai ai-doi"/> DOI](https://doi.org/10.1145/3431920.3439294){: .btn .btn--primary }
    [<i class="far fa-file-pdf"/> PDF](http://parallel.princeton.edu/papers/FPGA21-Li.pdf){: .btn .btn--primary }
    [<i class="fab fa-github"></i> GitHub](https://github.com/PrincetonUniversity/prga){: .btn .btn--primary }
    [<i class="fas fa-atlas"></i> Documentation](https://parallel.princeton.edu/prga/){: .btn .btn--primary }

feature_duet:
  title: Duet - Harmonious CPU-FPGA Integration
  image_path: /assets/images/arch_duet.png
  image_position: right
  excerpt: >-
    A novel approach to integrate manycores and multiple eFPGA fabrics to
    exploit fine-grained acceleration opportunities in the broad application
    domain.

    <ul class="fa-ul">
        <li><span class="fa-li"><i class="far fa-file"></i></span>
        Paper accepted to HPCA'23!
        </li>
        <li><span class="fa-li"><i class="far fa-file"></i></span>
        arXiv preprint coming soon!
        </li>
    </ul>

feature_gem5_duet:
  title: gem5 x Duet
  image_path: https://www.gem5.org/assets/img/gem5logo/Color/noBackground/vertical/gem5ColorVert.png
  image_position: left
  excerpt: >-
    A [gem5](https://www.gem5.org/) extension for simulating tightly-integrated,
    ASIC or FPGA-based accelerators.
    Gem5-Duet achieves C/C++-level simulation speed with cycle-level accuracy by
    compiling the High-Level Synthesis (HLS) source code into the simulator and
    applying post-HLS timing annotation in the runtime configuration script.

    <!--
    Gem5-Duet allows multiple CPU threads (hardware or software) to share
    multiple, heterogeneous accelerators that are integrated into the on-chip
    cache hierarchy.
    -->

    <ul class="fa-ul">
        <li><span class="fa-li"><i class="far fa-handshake"></i></span>
        In use by researchers at Princeton and UCSC
        </li>
    </ul>

    [<i class="fab fa-github"></i> GitHub](https://github.com/angl-dev/gem5-duet){: .btn .btn--primary }

feature_cifer:
  image_path: /assets/images/cifer_logo.png
  image_position: right
  title: CIFER
  excerpt: >-
    An open-source, heterogeneous, cache-coherent, manycore-eFPGA SoC.
    CIFER integrates OS-capable cores, parallel tiny core clusters, and eFPGA
    fabrics in a coherent cache system, covering both ends of the
    parallelization-specialization spectrum.

    <ul class="fa-ul">
        <li><span class="fa-li"><i class="far fa-handshake"></i></span>
        In collab with <a href="https://www.csl.cornell.edu/~cbatten/">Prof. Christopher Batten's group</a>
        </li>
        <li><span class="fa-li"><i class="fas fa-microchip"></i></span>
        Prototype chip fabricated and tested
        </li>
        <li><span class="fa-li"><i class="far fa-file"></i></span>
        Paper under review
        </li>
    </ul>

    <!--
    The key idea is to partition real-world applications into smaller tasks and
    run the tasks on the most efficient compute unit.
    The tiny core clusters and the eFPGAs cover both ends of the
    parallelization-specialization spectrum, while the OS-capable cores handle
    dynamic control flow, memory/IO-bound tasks, or any other non-acceleratable
    parts of an application.
    -->

feature_decades:
  image_path: /assets/images/decades_logo.png
  image_link: https://decades.cs.princeton.edu
  image_position: left
  title: DECADES
  excerpt: >-
    A heterogeneous, cache-coherent SoC with processors, specialized
    accelerators, intelligent storage units, and eFPGAs.
    The project is part of an effort to create hardware and software that can be
    reconfigured on the fly to accelerate important applications.

    <ul class="fa-ul">
        <li><span class="fa-li"><i class="far fa-handshake"></i></span>
        In collab with <a href="https://www.princeton.edu/~mrm/">Prof. Margaret Martonosi's group</a>
        </li>
        <li><span class="fa-li"><i class="far fa-handshake"></i></span>
        In collab with <a href="http://www.cs.columbia.edu/~luca/">Prof. Luca Carloni's group</a>
        </li>
        <li><span class="fa-li"><i class="fas fa-microchip"></i></span>
        Prototype chip fabricated and tested
        </li>
        <li><span class="fa-li"><i class="far fa-file"></i></span>
        Paper under review
        </li>
    </ul>

    [<i class="fas fa-atlas"></i> Website](https://decades.cs.princeton.edu){: .btn .btn--primary }

feature_order:
  image_path: https://camo.githubusercontent.com/e091743c32246b3f4ba2ce1671d715574d7ef87764b0b8e14464d01001b08956/68747470733a2f2f656661626c6573732d70726f64756374696f6e2d6d61726b6574706c6163652e73332e616d617a6f6e6177732e636f6d2f6174746163686d656e74732f70726f6a656374732f35633865356532302d366238342d346135612d613163312d6133376664306331636266382f436170747572652e504e47
  image_link: https://github.com/angl-dev/caravel_mpw5_prga
  image_position: right
  title: ORDER
  excerpt: >-
    ORDER is a microcontroller-eFPGA SoC designed with fully open-source
    hardware projects
    ([Caravel](https://caravel-harness.readthedocs.io/en/latest/) and
    [PRGA](#feature-prga)),
    PDK ([SkyWater130](https://skywater-pdk.readthedocs.io/en/main/)), and EDA
    toolchain ([OpenROAD](https://theopenroadproject.org)).

    <ul class="fa-ul">
        <li><span class="fa-li"><i class="fas fa-microchip"></i></span>
        Selected for <a href="https://efabless.com/open_shuttle_program">OpenMPW-6</a>. Fabrication in progress.
        </li>
    </ul>

    [<i class="fab fa-github"></i> GitHub](https://github.com/angl-dev/caravel_mpw5_prga){: .btn .btn--primary }
    [<i class="far fa-clipboard"></i> Efabless Project](https://platform.efabless.com/projects/1026){: .btn .btn--primary }

---

# About Me

I am a final-year Ph.D. candidate in the ECE department, Princeton University.
I am supervised by [Prof. David Wentzlaff](https://www.princeton.edu/~wentzlaf/)
who leads the [Princeton Parallel Group](http://parallel.princeton.edu/).

I am interested in all aspects of computer architecture, especially
heterogeneous and reconfigurable architectures for both high-performance and
low-power applications.
I am also interested in the VLSI design methodology and software programming
model for these architectures.
I enjoy building chips so as to validate and evaluate my ideas with high
fidelity.
I am also an advocator of open-source hardware/research as they
increase research credibility/reproducibility and encourage community-wide
collaboration.

**I am on the job market this year. You can find my latest CV [here](/assets/pdfs/CV.pdf).**

<!--
# Vision

The stagnation of transistor scaling has motivated vertical integration
across the conventional layers of abstraction in computer systems.
Software-hardware co-design has shown promising performance and energy
efficiency gains in emerging domains such as artificial intelligence,
edge/IoT, robotics, etc.
However, such hardware specialization faces two key challenges: the
immense cost/complexity in VLSI design, and the long time-to-market in
chip manufacturing.
I believe that the key to these challenges is _flexibility_.

Addressing the first challenge, we must revolutionize the
hardware design methodology to achieve _design-time flexibility_.
In particular, design generators with integrated verification and modeling
can greatly speed up design space exploration and tolerate software
uncertainty during software-hardware co-design;
high-level synthesis enables trade-offs between human effort and
quality-of-result, ideally making hardware design accessible to software
developers;
a composable, open-source hardware ecosystem facilitates
collaboration, sharing, and design reuse.

Addressing the second challenge, we must provision against 
software/algorithm changes after system deployment, i.e.
achieving _post-fabrication flexibility_.
Reconfigurable architectures are an ideal candidate, yet fine-grained
reconfigurable architectures such as FPGA suffer from low energy/transistor
efficiency, while coarse-grained reconfigurable architectures (CGRA) are
in an early but rapid-growing stage.
The huge design space of reconfigurable architectures is yet to be explored, and
the software support (e.g. compiler) for these novel architectures is also in
urgent need for research.
-->

<!--
During my Ph.D., I had the opportunity to work on multiple projects
spanning across the abstraction layers with a focus at the architecture level.

- I developed [PRGA](https://parallel.princeton.edu/prga/), an open-source FPGA
  prototyping and research platform which generates a synthesizable FPGA _(the
  reconfigurable fabric itself, not LUT-emulated designs)_ and an
  RTL-to-bitstream CAD tool chain according to user specifications.
- I led three chip tapeouts, specifically two OS-capable manycore-eFPGA SoCs in
  12nm FinFET, and one microcontroller-eFPGA SoC in 130nm CMOS, each of which
  integrates a unique, PRGA-generated FPGA.
- My latest project, Duet _(currently under review and will be open-sourced after
  paper acceptance)_, explores novel programming paradigms on CPU-FPGA hybrid
  systems and the required architectural supports.
  -->

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

{% include feature_section id="feature_prga" %}
{% include feature_section id="feature_duet" %}
{% include feature_section id="feature_gem5_duet" %}
{% include feature_section id="feature_cifer" %}
{% include feature_section id="feature_decades" %}
{% include feature_section id="feature_order" %}

# Referred Publications

## Conference Publications

<div class="pub">
  <div class="conf"><span>HPCA'23</span></div>
  <div class="pub-info">
    <p class="title">Duet: Creating Harmony between Processors and Embedded FPGAs</p>
    <p class="authors"><b><u>Ang Li</u></b>, August Ning, David Wentzlaff</p>
    <p class="venue">The 29th IEEE International Symposium on High-Performance Computer Architecture (<a href="https://hpca-conf.org/2023/">HPCA-29</a>), Feb-Mar 2023, Montreal, QC, Canada</p>
  </div>

  <div class="conf"><span>FPGA'21</span></div>
  <div class="pub-info">
    <p class="title">PRGA: An Open-Source FPGA Research and Prototyping Framework</p>
    <p class="links">
      <a class="link" href="https://doi.org/10.1145/3431920.3439294"><i class="ai ai-doi"></i> DOI</a>
      <a class="link" href="http://parallel.princeton.edu/papers/FPGA21-Li.pdf"><i class="far fa-file-pdf"></i> PDF</a>
      <a class="link" href="https://dl.acm.org/doi/10.1145/3431920.3439294#"><i class="far fa-file-video"></i> Recorded Presentation</a>
    </p>
    <p class="authors"><b><u>Ang Li</u></b>, David Wentzlaff</p>
    <p class="venue">The 29th ACM/SIGDA International Symposium on Field-Programmable Gate Arrays (<a href="https://www.isfpga.org/past/fpga2021/">FPGA-21</a>), Feb-Mar 2021, Virtual</p>
  </div>

  <div class="conf"><span>FPL'20</span></div>
  <div class="pub-info">
    <p class="title">Automated Design of FPGAs Facilitated by Cycle-Free Routing</p>
    <p class="links">
      <a class="link" href="https://doi.org/10.1109/FPL50879.2020.00042"><i class="ai ai-doi"></i> DOI</a>
      <a class="link" href="http://parallel.princeton.edu/papers/FPL20-Li.pdf"><i class="far fa-file-pdf"></i> PDF</a>
    </p>
    <p class="authors"><b><u>Ang Li</u></b>, Ting-Jung Chang, David Wentzlaff</p>
    <p class="venue">The 30th International Conference on Field-Programmable Logic and Applications (<a href="https://www.fpl2020.org/">FPL-20</a>), Aug-Sep 2020, Virtual</p>
  </div>

  <div class="conf"><span>ASPLOS'20</span></div>
  <div class="pub-info">
    <p class="title">BYOC: A "Bring Your Own Core" Framework for Heterogeneous-ISA Research</p>
    <p class="links">
      <a class="link" href="https://doi.org/10.1145/3373376.3378479"><i class="ai ai-doi"></i> DOI</a>
      <a class="link" href="http://parallel.princeton.edu/papers/aspl20-balkind.pdf"><i class="far fa-file-pdf"></i> PDF</a>
    </p>
    <p class="authors">Jonathan Balkind, Katie Lim, Michael Schaffner, Fei Gao, Grigory Chirkov, <b><u>Ang Li</u></b>, Alexey Lavrov, Tri M. Nguyen, Yaosheng Fu, Florian Zaruba, Kunal Gulati, Luca Benini, David Wentzlaff</p>
    <p class="venue">The 25th International Conference on Architectural Support for Programming Languages and Operating Systems (<a href="https://asplos-conference.org/2020/">ASPLOS-20</a>), Mar 2020, Lausanne, Switzerland</p>
  </div>

  <!--
  <div class="conf"><span>ISLPED'15</span></div>
  <div class="pub-info">
    <p class="title">Leveraging Emerging Nonvolatile Memory in High-Level Synthesis with Loop Transformations</p>
    <p class="links">
      <a class="link" href="https://doi.org/10.1109/ISLPED.2015.7273491"><i class="ai ai-doi"></i> DOI</a>
    </p>
    <p class="authors">Shuangchen Li, <b><u>Ang Li</u></b>, Yuan Zhe, Yongpan Liu, Peng Li, Guangyu Sun, Yu Wang, Huazhong Yang, Yuan Xie</p>
    <p class="venue">2015 IEEE/ACM International Symposium on Low Power Electronics and Design (<a href="http://islped.org/2015/">ISPLED-15</a>), July 2015, Rome, Italy</p>
  </div>

  <div class="conf"><span>ASPDAC'15</span></div>
  <div class="pub-info">
    <p class="title">Nonvolatile Memory Allocation and Hierarchy Optimization for High-Level Synthesis</p>
    <p class="links">
      <a class="link" href="https://doi.org/10.1109/ASPDAC.2015.7058999"><i class="ai ai-doi"></i> DOI</a>
    </p>
    <p class="authors">Shuangchen Li, <b><u>Ang Li</u></b>, Yongpan Liu, Yuan Xie, Huazhong Yang</p>
    <p class="venue">The 20th Asia and South Pacific Design Automation Conference (<a href="https://www.aspdac.com/aspdac2015/">ASPDAC-15</a>), Jan 2015, Chiba/Tokyo, Japan</p>
  </div>
  -->

</div>

## Journal Publications

<div class="pub">
  <div class="conf"><span>IEEE Micro</span></div>
  <div class="pub-info">
    <p class="title">OpenPiton at 5: A Nexus for Open and Agile Hardware Design</p>
    <p class="links">
      <a class="link" href="https://doi.org/10.1109/MM.2020.2997706"><i class="ai ai-doi"></i> DOI</a>
      <a class="link" href="http://parallel.princeton.edu/papers/ieee20-balkind.pdf"><i class="far fa-file-pdf"></i> PDF</a>
    </p>
    <p class="authors">Jonathan Balkind, Ting-Jung Chang, Paul J. Jackson, Georgios Tziantzioulis, <b><u>Ang Li</u></b>, Fei Gao, Alexey Lavrov, Grigory Chirkov, Jinzheng Tu, Mohammad Shahrad, David Wentzlaff</p>
    <p class="venue">IEEE Micro Vol. 40, No. 1, Jul-Aug 2020</p>
  </div>
</div>

## Workshops and Posters

<div class="pub">
  <div class="conf"><span>FPGA'20</span></div>
  <div class="pub-info">
    <p class="title">(Poster) Cycle-Free FPGA Routing Graphs</p>
    <p class="links">
      <a class="link" href="https://doi.org/10.1145/3373087.3375354"><i class="ai ai-doi"></i> DOI</a>
      <a class="link" href="/assets/pdfs/fpga20.pdf"><i class="far fa-file-pdf"></i> PDF</a>
      <a class="link" href="/assets/pdfs/fpga20_poster.pdf"><i class="far fa-file-pdf"></i> Poster</a>
    </p>
    <p class="authors"><b><u>Ang Li</u></b>, David Wentzlaff</p>
    <p class="venue">The 28th ACM/SIGDA International Symposium on Field-Programmable Gate Arrays (<a href="https://www.isfpga.org/past/fpga2020/">FPGA-20</a>), Feb 2020, Seaside, California, USA</p>
  </div>
</div>

<!--
* **[OSDA'19, Workshop]** **<u>Ang Li</u>**, and David Wentzlaff, _"PRGA: An
  Open-source Framework for Building and Using Custom FPGAs"_, 1st Workshop on
  Open-Source Design Automation, Mar. 2019

  [<i class="far fa-file-pdf"/> PDF](/assets/pdfs/osda19.pdf){: .btn .btn--primary .btn--small }

* **[WOSET'18, Workshop]** Jonathan Balkind, Alexey Lavrov, Michael McKeown, Yaosheng Fu, Tri Nguyen, Mohammad Shahrad, **<u>Ang Li</u>**, Katie Lim, Yanqi Zhou, Ting-Jung Chang, Paul Jackson, Adi Fuchs, Samuel Payne, Xiaohua Liang, Matthew Matl, and David Wentzlaff, _"OpenPiton: An Emerging Standard for Open-Source EDA Tool Development"_, Workshop on Open-Source EDA Technology, Nov. 2018
-->

# Teaching

* Teaching Assistant, ECE 462/562 (also COS 462), _Design of Very Large-Scale
  Integrated (VLSI) Systems_, 2022 Fall
* Mentor, Google Summer of Code, _PRGA + FASM: Open-Source Bitgen for FPGAs_,
  2020 Summer
* Teaching Assistant, ECE 475/575 (also COS 475), _Computer Architecture_, 2018
  Fall
* Co-Advisory of Undergraduate Research
  - Jaebyoek Yoon, _Architecture and Physical Design of Specialized FPGAs_
  - Marlon Escobar, _CPU-FPGA Integration_
  - Kevin Liu, _Creating Multimode Logic Elements for a Reconfigurable Gate
    Array_
