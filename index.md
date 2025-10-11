---
layout: page
title: About me 
cover: false
---


Hi, I'm Yilun Xu, a research scientist at Meta. I was a research scientist Google DeepMind, building the world's first world model &#127758; , particularly in the post-training and model acceleration. Previously, I co-led the diffusion distillation efforts at NVIDIA.

I received my PhD in MIT EECS, advised by [Tommi Jaakkola](https://people.csail.mit.edu/tommi/tommi.html). I obtained my Bachelor’s degree from Turing Class in EECS dept, 
Peking University, working with [Yizhou Wang](http://cfcs.pku.edu.cn/faculty/adjunct/wangyizhou/index.htm) (PKU), and [Stefano Ermon](https://cs.stanford.edu/~ermon/) (Stanford). 
During my GDM time, I worked with [Tim Brooks](https://www.timothybrooks.com/about/). During my NVIDIA time, I worked with [Arash Vahdat](http://latentspace.cc) and [Ming-Yu Liu](https://mingyuliu.net). 
 
My PhD research focus is deep generative modeling: 

- *(i) New models:* PFGM [10], PFGM++ [13], HGF [18], t-EDM [21]
- *(ii) Training:* STF [11], Disco-Diff [16], Style Control [9]
- *(iii) Sampling:* Restart sampling [14], Particle Guidance [15], Anytime AR [5]
- *(iv) Discrete diffusion:* DDPD [19], EDLM [20]
- *(v) Diffusion Distillation:* TCM [22], f-distill [23]

I also have some works on bridging machine learning and information theory [4, 3, 2, 1], such as V-information, during my undergrad.



**Contact**: ylxu@meta.com

# Publications 
(*) denotes equal contribution

<ol reversed>
{% for paper in site.data.papers.papers %}
  {% if paper.selected %}
  <li>
  {% include paper.html paper=paper %}
  </li>
  {% endif %}
{% endfor %}
</ol>



# Education

<div style="clear: both;">
  <div style="float: left; margin-right 1em;">
    <img src="/assets/img/mit.png" alt="" width="150" height="150">
  </div>
  <div>
    <h3>&nbsp;&nbsp;&nbsp; Sep. 2021* - May. 2024: Massachusetts Institute of Technology</h3>
    <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Ph.D. in Computer Science </p>
    <p> &nbsp;&nbsp;&nbsp;&nbsp; Advisor: <a href="https://people.csail.mit.edu/tommi/tommi.html">Tommi Jaakkola</a> </p>
    <p>      &nbsp;&nbsp;&nbsp;&nbsp; *: remote during Sept 2020 - Aug 2021</p>
  </div>
</div>

<div style="clear: both;">
  <div style="float: left; margin-right 1em;">
    <img src="/assets/img/pku.png" alt="" width="150" height="150">
  </div>
  <div>
    <h3>&nbsp;&nbsp;&nbsp;Sep. 2016 - July. 2020: Peking University</h3>
    <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;B.S. in Turing Class, Computer Science (summa cum laude)</p>
    <p> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Advisor: <a href="http://cfcs.pku.edu.cn/faculty/adjunct/wangyizhou/index.htm">Yizhou Wang</a> </p>
  </div>
</div>

<div style="clear: both;">
  <div style="float: left; margin-right 1em;">
    <img src="/assets/img/stanford.png" alt="" width="150" height="150">
  </div>
  <div>
    <h3>&nbsp;&nbsp;&nbsp;Jun. 2019 - Sep. 2019: Stanford University</h3>
    <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Visiting reseacher </p>
    <p> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Advisor: <a href="https://cs.stanford.edu/~ermon/">Stefano Ermon</a> </p>
  </div>
</div>
<br/>

[//]: # (# Work Experience )

[//]: # ()
[//]: # (<div style="clear: both;">)

[//]: # (  <div style="float: left; margin-right 1em;">)

[//]: # (    <img src="/assets/img/nvidia.png" alt="" width="182" height="150">)

[//]: # (  </div>)

[//]: # (  <div>)

[//]: # (    <h3>&nbsp;&nbsp;&nbsp;July 2024 - April 2025: NVIDIA </h3>)

[//]: # (    <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Research Scientist </p>)

[//]: # (    <p> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Projects: <a href="https://karstenkreis.github.io">Karsten Kreis</a> and <a href="http://latentspace.cc">Arash Vahdat</a> </p>)

[//]: # (  </div>)

[//]: # (</div>)

[//]: # (<br/>)

[//]: # (# Talks)

[//]: # ()
[//]: # (- *On Physics-Inspired Generative Models*)

[//]: # (  - **Peking University, hosted by Prof. [Yizhou Wang]&#40;http://cfcs.pku.edu.cn/faculty/adjunct/wangyizhou/index.htm&#41;**, June 2024 [[Video &#40;CN&#41;]&#40;https://www.bilibili.com/video/BV1e6421f7kY/?spm_id_from=333.337.search-card.all.click&#41;], [[Slide]&#40;https://www.dropbox.com/scl/fi/qed49r04bejmhlws22j1j/phd_defense.pptx?rlkey=8kw9owov91qi49zjrr2ulimok&st=lfeaq85o&dl=0&#41;])

[//]: # (  )
[//]: # (  - **CUHK, hosted by Prof. [Pheng Ann Heng]&#40;https://www.cse.cuhk.edu.hk/~pheng/&#41;**, June 2024)

[//]: # ()
[//]: # (- *Generative Models & Physical Processes*)

[//]: # (  - **UCLA, hosted by Prof. [Yingnian Wu]&#40;http://www.stat.ucla.edu/~ywu/me.html&#41;**, Oct 2023 [[Slide]]&#40;https://www.dropbox.com/scl/fi/f91h30eevegprnjmu9dsa/talk.key?rlkey=g3owuav0sgfh910q38go2buk3&dl=0&#41;)

[//]: # ()
[//]: # (- *Unlocking the Potential of Physics-Inspired Generative Models*)

[//]: # (  - **[Learning on Graphs and Geometry]&#40;https://m2d2.io/talks/logg/about/&#41; seminar**. Oct, 2023 [[Video]]&#40;https://www.youtube.com/watch?v=VFXKMlcl7QA&#41;)

[//]: # (  - **Zhejiang University, hosted by Prof. Chao Xu**, Oct 2023 )

[//]: # ()
[//]: # (  - **[Peking University, CFCS]&#40;https://cfcs.pku.edu.cn/english/&#41;**, Aug 2023)

[//]: # ()
[//]: # (  - **[NVIDIA Research]&#40;https://www.nvidia.com/en-us/research/&#41;**, July 2023)

[//]: # ()
[//]: # (  - **ByteDance, AI for Science Team**, July 2023)

[//]: # ()
[//]: # (  - **[Swarma Club]&#40;https://swarma.org&#41;**, May 2023, [[Slide]&#40;https://www.dropbox.com/s/0cgacob54vw7boe/jizhi_5_13_22.pptx?dl=0&#41;]  [[Video &#40;CN&#41;]&#40;https://www.bilibili.com/video/BV17g4y1V7wY/?spm_id_from=333.337.search-card.all.click&#41;])

[//]: # ()
[//]: # (  - **[TechBeat/Jiangmen Ventures]&#40;https://www.techbeat.net&#41;**, April 2023, [[Slide]&#40;https://www.dropbox.com/s/0cgacob54vw7boe/jizhi_5_13_22.pptx?dl=0&#41;] [[Video &#40;CN&#41;]&#40;https://www.bilibili.com/video/BV1HV4y167q1/?spm_id_from=333.337.search-card.all.click&#41;])

[//]: # ()
[//]: # (  - **[MLTea Talk]&#40;https://mlxmit.mit.edu/ml-tea-talks&#41;**, MIT, April 2023, [[Slide]&#40;https://www.dropbox.com/s/0cgacob54vw7boe/jizhi_5_13_22.pptx?dl=0&#41;])

[//]: # (  - **Stanford University, hosted by Prof. [Mert Pilanci]&#40;https://web.stanford.edu/~pilanci/&#41;**, Feb 2023, [[Slide]&#40;https://www.dropbox.com/scl/fi/6p0av7cak0yp59g0zt32z/Mert_group.pptx?dl=0&rlkey=ix5smfxcio8snzbck2odpod5q&#41;])

[//]: # ()
[//]: # (- *Conditional and Controllable Generation*  )

[//]: # (  - **Guest lecturer at [6.S052/6.S952]&#40;https://www.eecs.mit.edu/academics/subject-updates/subject-updates-spring-2023/&#41;: Modeling with Machine learning for CS, MIT**, April 2023, [[Slide]&#40;https://www.dropbox.com/s/5vgzmmkc59846uu/lecture9.key?dl=0&#41;])

[//]: # ()
[//]: # (- *Poisson Flow Generative Models*)

[//]: # (  - **[AssemblyAI]&#40;https://www.assemblyai.com&#41; AI Hackathon**, Dec 2022, [[Slide]&#40;https://www.dropbox.com/scl/fi/kf4xei8mahx8uwuxdzxaj/assembly-ai.pptx?dl=0&rlkey=cjuuayvv672nk9t7vy1jgf8gc&#41;])

[//]: # ()
[//]: # (  - **Princeton University, hosted by Prof. [Mengdi Wang]&#40;https://mwang.princeton.edu&#41;**, Nov 2022, [[Slide]&#40;https://www.dropbox.com/scl/fi/wn13m59v28ts5heolr0qv/mengdi_group.pptx?dl=0&rlkey=7sxw47b6i0jdvroisg586o92s&#41;])

[//]: # ()
[//]: # (  - **[MIT NetMIT Group]&#40;http://groups.csail.mit.edu/netmit/wordpress/&#41;, hosted by Prof. [Dina Katabi]&#40;https://people.csail.mit.edu/dina/&#41;**,)

[//]: # (  Nov 2022 )

[//]: # ()
[//]: # (- *Controlling Directions Orthogonal to a Classifier*,)

[//]: # (  - **[AI TIME]&#40;http://aitime.cn/&#41;**, June 2022, [[Slide]]&#40;https://www.dropbox.com/scl/fi/txtz6pwr6xfarg3fetpzb/orthogonal_classifier_ai_times.pptx?dl=0&rlkey=n3p1nxeq8sso0jui9r3xraggh&#41;)

[//]: # (- *Anytime Sampling for Autoregressive Models via Ordered Autoencoding*)

[//]: # (  - **[AI TIME]&#40;http://aitime.cn/&#41;**, June 2021, [[Slide]&#40;https://www.dropbox.com/scl/fi/m4ulvedtz2e7stnxgydcw/anytime_paper_aitimes.pptx?dl=0&rlkey=7ls7dfcgpq3s64rgkgxarvzld&#41;])


# Service 

Conference Reviewer: NeurIPS 2020-2024; ICLR 2021-2025; ICML 2021-2024; CVPR 2025; ICCV 2025 

PC member: ICLR 2022 PAIR2Struct, CVPR 2025 Visual Generative Modeling: What’s After Diffusion?

Panelist: ICML 2023 Structured Probabilistic Inference & Generative Modeling

Teaching Assistant for 6.S052/6.S952: Modeling with Machine learning for CS, MIT, Spring 2023 (*co-design the problem set and lectures for this new course, and receive an outstanding TA rating of **6.9 out of 7.0** from students*)

# Miscellaneous

I am a national second-class table tennis player in China. Men's single champion in PKU Freshman's Cup (2016). I also played for MIT table tennis team, winning the 3rd place (group) in the 2022 NCTTA Upper New England Championship. 
