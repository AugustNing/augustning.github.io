---
layout: home
---

<div align="center" style="text-align: center">
	<div class="circular-portrait" align="center">
		<img src="{{ site.profile_photo_filepath }}" alt="August Ning"/>
	</div>
	<br>
	<br>
	<div style="display: inline-block; text-align: center;">
		Email: {{site.email}}
		<br>
		Twitter: <a href="https://twitter.com/{{site.twitter}}">@{{site.twitter}}</a>
		<br>
		Linkedin: <a href="https://linkedin.com/in/{{site.linkedin}}">@{{site.linkedin}}</a>
	</div>
</div>

***

<span style="color:red">**I am graduating in 2025 and am on the job market for industry research and academic postdoc positions. Please reach out if you think we'll have a good fit. Thank you!**</span>

I am a senior Electrical and Computer Engineering PhD candidate at Princeton. I am advised by [Prof. David Wentzlaff](https://princeton.edu/~wentzlaf/) in the [Princeton Parallel Group](https://parallel.princeton.edu/).

I did my undergrad at Duke in Electrical and Computer Engineering. I was advised by [Prof. Krishnendu Chakrabarty](https://search.asu.edu/profile/4669916) and his graduate students and conducted research on VLSI testing.

I spent summer 2023 interning at AMD Research, mentored by Yasuko Eckert.

I am supported by Princeton's Gordon Y. S. Wu Fellowship and the NSF Graduate Research Fellowship Program.

***

### **News**

* Jun 2024 - Presenting LLMCompass at ISCA 2024. LLMCompass is open source! Check out our [lightning talk](https://www.youtube.com/watch?v=OlF5D0HDJTE), [full paper](assets/papers/llmcompass-isca-2024.pdf), [Github repo](https://github.com/PrincetonUniversity/llmCompass/), and let's chat in Buenos Aires!
* May 2024 - Mentoring two undergrad students this summer for the Princeton-Intel REU program
* Mar 2024 - Presented at NYU Computer Architecture Day
* Mar 2024 - LLMCompass accepted at ISCA 2024! The preprint is on [arxiv](https://arxiv.org/abs/2312.03134)
* Mar 2024 - Gave a talk for Princeton ACM about "Why You Should (and Should Not!) Go to Grad School"
* Feb 2024 - I will be serving on the ISCA 2024 Artifact Evaluation Committee
* Dec 2023 - New preprint up on arxiv: [A Hardware Evaluation Framework for Large Language Model Inference](https://arxiv.org/abs/2312.03134)
* Sep 2023 - Incredibly fortunate to receive a Princeton ECE Graduate Student Service Award
* Aug 2023 - An extend version of our CIFER paper has been accepted in IEEE Solid-State Circuits Letters
* Jun 2023 - Modeling for Supply Chain Aware Computer Architecture is open sourced. Check it out! [github.com/PrincetonUniversity/ttm-cas/](https://github.com/PrincetonUniversity/ttm-cas/)

***

### **Research Interests**
My research focuses on computer architecture under (very broadly defined) economics constraints. I am interested in how semiconductor supply chains, manufacturing costs, and economic trends ultimately affect chip and system designs. 

Closer to traditional computer architecture, I am interested in sustainability, hardware security, chiplet architectures, and software-hardware co-design via the [DECADES Project](https://decades.cs.princeton.edu/).

Additionally, I am passionate about building research and student communities. I serve on the [Computer Architecture Student Association](https://sigarch.org/casa/) steering committee and often organize social events with the Princeton computer architects. I am the graduate liason for [Princeton ACM](https://princeton.acm.org/). If you're ever in the Princeton area or meet me at a conference, please reach out and say hello!

***
<!-- authors, "title in quotes,", *conference in italics*, city, state, country, month year -->
<!-- ### **Preprints**

<ul class='no_marker'>
	<li><b>A Hardware Evaluation Framework for Large Language Model Inference</b></li>
	<li>Hengrui Zhang, August Ning, Rohan Prabhakar, and David Wentzlaff</li>
	<li>Dec 2023</li>
	<li><a href="https://arxiv.org/abs/2312.03134">[arxiv]</a> <a href="assets/papers/llm-hardware-eval-arxiv-2023.pdf">[pdf]</a></li>
</ul> -->

<!-- authors, "title in quotes,", *conference in italics*, city, state, country, month year -->
### **Publications**

<ul class='no_marker'>
	<li><b>LLMCompass: Enabling Efficient Hardware Design for Large Language Model Inference</b></li>
	<li>Hengrui Zhang, August Ning, Rohan Prabhakar, and David Wentzlaff</li>
	<li><i>The 51th International Symposium on Computer Architecture (ISCA)</i>, Buenos Aires, AR, Jun 2024</li>
	<li><a href="assets/papers/llmcompass-isca-2024.pdf">[pdf]</a> <a href="https://github.com/PrincetonUniversity/llmCompass/">[Github repo]</a></li>
</ul>


<ul class='no_marker'>
	<li><b>CIFER: A Cache-Coherent 12nm 16mm<sup>2</sup> SoC With Four 64-Bit RISC-V Application Cores, 18 32-Bit RISC-V Compute Cores, and a 1541 LUT6/mm<sup>2</sup> Synthesizable eFPGA</b></li>
	<li>Ang Li, <i>Et al.</i></li>
	<li><i>IEEE Solid-State Circuits Letters</i>, Aug 2023</li>
	<li><a href="https://ieeexplore.ieee.org/document/10210635">[IEEE Xplore]</a> <a href="assets/papers/cifer-sscl-2023.pdf">[pdf]</a></li>
</ul>

<ul class='no_marker'>
	<li><b>Supply Chain Aware Computer Architecture</b></li>
	<li>August Ning, Georgios Tziantzioulis, and David Wentzlaff</li>
	<li><i>The 50th International Symposium on Computer Architecture (ISCA)</i>, Orlando, FL, USA, Jun 2023</li>
	<li><a href="https://dl.acm.org/doi/10.1145/3579371.3589052">[ACM DL Open Access]</a> <a href="assets/papers/supply-chain-isca-2023.pdf">[pdf]</a> <a href="https://github.com/PrincetonUniversity/ttm-cas/">[Github repo]</a></li>
</ul>

<ul class='no_marker'>
	<li><b>CIFER: A 12nm, 16mm<sup>2</sup>, 22-Core SoC with a 1541 LUT6/mm<sup>2</sup>, 1.92 MOPS/LUT, Fully Synthesizable, Cache-Coherent, Embedded FPGA</b></li>
	<li>Ting-Jung Chang*, Ang Li*, <i>Et al.</i></li>
	<li><i>2023 IEEE Custom Integrated Circuits Conference (CICC)</i>, San Antonio, TX, USA, Apr 2023</li>
	<li><a href="https://ieeexplore.ieee.org/abstract/document/10121294">[IEEE Xplore]</a> <a href="assets/papers/cifer-cicc-2023.pdf">[pdf]</a></li>
</ul>

<ul class='no_marker'>
	<li><b>DECADES: A 67mm<sup>2</sup>, 1.46TOPS, 55 Giga Cache-Coherent 64-bit RISC-V Instructions per second, Heterogeneous Manycore SoC with 109 Tiles including Accelerators, Intelligent Storage, and eFPGA in 12nm FinFET</b></li>
	<li>Fei Gao, <i>Et al.</i></li>
	<li><i>2023 IEEE Custom Integrated Circuits Conference (CICC)</i>, San Antonio, TX, USA, Apr 2023</li>
	<li><b>Best Student Paper Award Nominee!</b></li>
	<li><a href="https://ieeexplore.ieee.org/document/10121257">[IEEE Xplore]</a> <a href="assets/papers/decades-cicc-2023.pdf">[pdf]</a></li>
</ul>

<ul class='no_marker'>
	<li><b>Duet: Creating Harmony between Processors and Embedded FPGAs</b></li>
	<li>Ang Li, August Ning, and David Wentzlaff</li>
	<li><i>2023 IEEE International Symposium on High-Performance Computer Architecture (HPCA)</i>, Montreal, QC, Canada, Mar 2023</li>
	<li><a href="https://ieeexplore.ieee.org/document/10070989">[IEEE Xplore]</a> <a href="assets/papers/duet-hpca-2023.pdf">[pdf]</a> <a href="https://github.com/PrincetonUniversity/duet">[Github repo]</a></li>
</ul>

<ul class='no_marker'>
	<li><b>Variation-Aware Delay Fault Testing for Carbon-Nanotube FET Circuits</b></li>
	<li>Sanmitra Banerjee, Arjun Chaudhuri, August Ning and Krishnendu Chakrabarty</li>
	<li><i>IEEE Transactions on Very Large Scale Integration (VLSI) Systems</i>, Feb 2021</li>
	<li><a href="https://ieeexplore.ieee.org/document/9316977">[IEEE Xplore]</a> <a href="assets/papers/vadft-cntfet-tvlsi-2021.pdf">[pdf]</a></li>
</ul>

### **Workshops/Presentations**

<ul class='no_marker'>
	<li><b>Computer Architectures for Chip Surplus</b></li>
	<li>August Ning and David Wentzlaff</li>
	<li><i>ACM Student Research Competition at MICRO 2022</i>, Chicago, IL, USA, Oct 2022</li>
	<li><a href="assets/papers/chip-surplus-src-micro-2022.pdf">[poster]</a></li>
</ul>
<ul class='no_marker'>
	<li><b>Supply Chain Aware Chip Architecture</b></li>
	<li>August Ning, Georgios Tziantzioulis, and David Wentzlaff</li>
	<li><i>The Fourth Young Architect Workshop at ASPLOS 2022</i>, Lausanne, VD, Switzerland, Mar 2022</li>
	<li><a href="assets/papers/supply-chain-yarch-asplos-2022.pdf">[poster]</a></li>
</ul>

---

[Github](https://github.com/{{ site.github }}) / [Google Scholar](https://scholar.google.com/citations?user={{ site.google_scholar }}) / [CV]({{ site.cv_filepath }})

This website is built with [Jekyll](https://github.com/jekyll/jekyll) using a modified [no style, please!](https://github.com/riggraz/no-style-please) theme.