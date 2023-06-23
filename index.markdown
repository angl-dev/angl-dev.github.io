---
layout: single
title: false
author_profile: true
analytics: true

sidebar:
  - text: <p class="home-nav"><a href="#-about-me"><i class="fas fa-child-reaching"></i> About Me</a></p>
  - text: <p class="home-nav"><a href="#-latest-news"><i class="fas fa-newspaper"></i> Latest News</a></p>
  - text: >-
      <p class="home-nav"><a href="#-projects"><i class="fas fa-screwdriver-wrench"></i> Projects</a></p>

  - comments: >-
      <ul class="home-nav fa-ul">
          <li><span class="fa-li"><i class="fas fa-meteor"></i></span><a href="#feature_prga">PRGA</a></li>
          <li><span class="fa-li"><i class="fas fa-meteor"></i></span><a href="#feature_duet">Duet</a></li>
          <li><span class="fa-li"><i class="fas fa-meteor"></i></span><a href="#feature_gem5_duet">Gem5-Duet</a></li>
          <li><span class="fa-li"><i class="fas fa-meteor"></i></span><a href="#feature_cifer">CIFER</a></li>
          <li><span class="fa-li"><i class="fas fa-meteor"></i></span><a href="#feature_decades">DECADES</a></li>
          <li><span class="fa-li"><i class="fas fa-meteor"></i></span><a href="#feature_order">ORDER</a></li>
      </ul>

  - text: <p class="home-nav"><a href="#-referred-publications--full-list"><i class="fas fa-box-archive"></i> Referred Publications</a></p>
  - text: <p class="home-nav"><a href="#-teaching"><i class="fas fa-person-chalkboard"></i> Teaching</a></p>

unused:
  - text: <p class="home-nav"><a href="#vision">Vision</a></p>

feature_prga:
  image_path: /assets/images/prga_logo.png
  image_link: https://parallel.princeton.edu/prga/
  title: <i class="fas fa-meteor"></i> PRGA - Princeton Reconfigurable Gate Array
  image_position: left
  excerpt: >-
    A silicon-proven, open-source project for generating customized, synthesizable
    FPGA with complementary, RTL-to-bitstream CAD toolchain.

    <ul class="fa-ul">
        <li><span class="fa-li"><i class="far fa-file"></i></span>
        PRGA has been <a href="/publications/#-pub-item-fpga21">published</a> and presented at <a href="https://www.isfpga.org/past/fpga2021">FPGA'21</a>!
        </li>
        <li><span class="fa-li"><i class="far fa-file"></i></span>
        Cycle-free FPGA has been <a href="/publications/#-pub-item-fpl20">published</a> and presented at <a href="https://www.fpl2020.org">FPL'20</a>!
        </li>
        <li><span class="fa-li"><i class="fas fa-microchip"></i></span>
        PRGA has been used in three silicon prototypes: <a href="/#feature_cifer">CIFER</a>, <a href="/#feature_decades">DECADES</a>, and <a href="/#feature_order">ORDER</a>. CIFER and DECADES have been tested and functional in our lab!
        </li>
    </ul>

    [<i class="ai ai-doi"/> DOI](https://doi.org/10.1145/3431920.3439294){: .btn .btn--primary }
    [<i class="far fa-file-pdf"/> PDF](http://parallel.princeton.edu/papers/FPGA21-Li.pdf){: .btn .btn--primary }
    [<i class="fab fa-github"></i> GitHub](https://github.com/PrincetonUniversity/prga){: .btn .btn--primary }
    [<i class="fas fa-atlas"></i> Website](https://parallel.princeton.edu/prga/){: .btn .btn--primary }

feature_duet:
  title: <i class="fas fa-meteor"></i> Duet - Harmonious CPU-FPGA Integration
  image_path: /assets/images/arch_duet.png
  image_position: right
  narrow_body: yes
  excerpt: >-
    A novel approach to integrate manycores and multiple eFPGA fabrics to
    exploit fine-grained acceleration opportunities in the broad application
    domain.

    <ul class="fa-ul">
        <li><span class="fa-li"><i class="far fa-file"></i></span>
        Duet has been <a href="/publications/#-pub-item-hpca23">published</a> and presented at <a href="https://hpca-conf.org/2023">HPCA'23</a>!
        </li>
        <li><span class="fa-li"><i class="fas fa-newspaper"></i></span>
        Media coverage by <a
        href="https://semiengineering.com/manycore-fpga-architecture-employing-novel-duet-adapters-to-integrate-efpgas-in-a-scalable-non-intrusive-cache-coherent-manner-princeton/">
        Semiconductor Engineering
        </a> and <a
        href="https://news.accelerationrobotics.com/hardware-acceleration-in-robotics-43/#duet-creating-harmony-between-processors-and-embedded-fpgas">Acceleration
        Robotics</a>!
        </li>
    </ul>

    [arXiv](https://arxiv.org/abs/2301.02785){: .btn .btn--primary }
    [<i class="ai ai-doi"/> DOI](https://doi.org/10.1109/HPCA56546.2023.10070989){: .btn .btn--primary }
    [<i class="far fa-file-pdf"/> PDF](/assets/pdfs/HPCA23_Ang_Li.pdf){: .btn .btn--primary }
    [<i class="fab fa-github"></i> GitHub](https://github.com/PrincetonUniversity/Duet){: .btn .btn--primary }

feature_gem5_duet:
  title: <i class="fas fa-meteor"></i> gem5 x Duet
  image_path: /assets/images/gem5ColorVert.png
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
        <li><span class="fa-li"><i class="far fa-file"></i></span>
        Redwood, a research project using gem5-Duet has been 
        <a href="/publications/#-pub-item-ispass23">published</a> and presented at <a href="https://ispass.org/ispass2023">ISPASS'23</a>!
        </li>
    </ul>

    [<i class="fab fa-github"></i> GitHub](https://github.com/angl-dev/gem5-duet){: .btn .btn--primary }

feature_cifer:
  image_path: /assets/images/cifer_logo.png
  image_position: right
  title: <i class="fas fa-meteor"></i> CIFER
  excerpt: >-
    A heterogeneous, cache-coherent, manycore-eFPGA SoC.
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
        CIFER has been <a href="#-pub-item-cicc23_cifer">published</a> and presented at <a href="https://www.ieee-cicc.org">CICC'23</a>!
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

    [<i class="far fa-file-pdf"/> PDF](/assets/pdfs/CIFER_CICC23.pdf){: .btn .btn--primary }

feature_decades:
  image_path: /assets/images/decades_logo.png
  image_link: https://decades.cs.princeton.edu
  image_position: left
  title: <i class="fas fa-meteor"></i> DECADES
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
        DECADES has been <a href="#-pub-item-cicc23_decades">published</a> and presented at <a href="https://www.ieee-cicc.org">CICC'23</a>!
        </li>
    </ul>

    [<i class="far fa-file-pdf"/> PDF](/assets/pdfs/DECADES_CICC23.pdf){: .btn .btn--primary }
    [<i class="fas fa-atlas"></i> Website](https://decades.cs.princeton.edu){: .btn .btn--primary }

feature_order:
  image_path: https://camo.githubusercontent.com/e091743c32246b3f4ba2ce1671d715574d7ef87764b0b8e14464d01001b08956/68747470733a2f2f656661626c6573732d70726f64756374696f6e2d6d61726b6574706c6163652e73332e616d617a6f6e6177732e636f6d2f6174746163686d656e74732f70726f6a656374732f35633865356532302d366238342d346135612d613163312d6133376664306331636266382f436170747572652e504e47
  image_link: https://github.com/angl-dev/caravel_mpw5_prga
  image_position: right
  title: <i class="fas fa-meteor"></i> ORDER
  excerpt: >-
    ORDER is a microcontroller-eFPGA SoC designed with fully open-source
    hardware projects
    ([Caravel](https://caravel-harness.readthedocs.io/en/latest/) and
    [PRGA](#feature_prga)),
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

<p class="notice--info">
I am officially joining the <a href="https://www.ece.uw.edu/">Department of Electrical and Computer Engineering</a>
at the University of Washington (UW ECE) as an assistant professor in 2023 fall! Super excited for the journey ahead!
</p>

# <i class="fas fa-child-reaching"></i> About Me

I am a final-year Ph.D. candidate in the ECE department, Princeton University.
I am supervised by [Prof. David Wentzlaff](https://www.princeton.edu/~wentzlaf/)
who leads the [Princeton Parallel Group](http://parallel.princeton.edu/).

I am interested in all aspects of computer architecture and digital VLSI design,
especially heterogeneous and reconfigurable systems for both high-performance and
low-power applications.
I enjoy building chips so as to validate and evaluate my ideas with high
fidelity.
I am also an advocate of open-source hardware/research as they
increase research credibility/reproducibility and encourage community-wide
collaboration.

# <i class="fas fa-newspaper"></i> Latest News

<ul>
{% for news in site.data.news reversed limit:10 %}
  <li>
  {{ news.date | date: "%D" }} {{ news.content | markdownify | remove: "<p>" | remove: "</p>" }}
  </li>
{% endfor %}
</ul>

# <i class="fas fa-screwdriver-wrench"></i> Projects

{% include feature_section id="feature_prga" %}
{% include feature_section id="feature_duet" %}
{% include feature_section id="feature_gem5_duet" %}
{% include feature_section id="feature_cifer" %}
{% include feature_section id="feature_decades" %}
{% include feature_section id="feature_order" %}

# <i class="fas fa-box-archive"></i> Referred Publications | [Full List](/publications)

<div class="pub">
  {% include pub_item id="ispass23" %}
  {% include pub_item id="cicc23_cifer" %}
  {% include pub_item id="cicc23_decades" %}
  {% include pub_item id="hpca23" %}
  {% include pub_item id="fpga21" %}
  {% include pub_item id="fpl20" %}
</div>

# <i class="fas fa-person-chalkboard"></i> Teaching

* Teaching Assistant, ECE 462/562 (also COS 462), _Design of Very Large-Scale
  Integrated (VLSI) Systems_, 2022 Fall
* Teaching Assistant, ECE 475/575 (also COS 475), _Computer Architecture_, 2018
  Fall
* FOSSi Mentor, [Google Summer of Code](https://www.fossi-foundation.org/2020/05/04/gsoc2020-intro), 2020 Summer
  - Ansh Puvvada, _Automating hardware and bitstream verification for PRGA with cocotb_
* Co-Advisory of Undergraduate Research
  - Jaebyoek Yoon, _Architecture and Physical Design of Specialized FPGAs_
  - Marlon Escobar, _CPU-FPGA Integration_
  - Kevin Liu, _Creating Multimode Logic Elements for a Reconfigurable Gate
    Array_
