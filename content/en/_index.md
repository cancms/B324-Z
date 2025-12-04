---
# Leave the homepage title empty to use the site title
title:
type: home_index




# 实验室介绍
heroBlock:
  block: hero
  content:
    title: WELCOME TO THE ZHONG GROUP
#   image:
#      filename: research_topic.jpg
    text: |
      Miao Zhong is a Professor at the College of Engineering and Applied Sciences, Nanjing University, a Researcher Fellow at the National Laboratory of Solid State Microstructures, and a Ph.D. Supervisor. He received Ph.D. from the University of Tokyo and B.S. from Shanghai Jiao Tong University. He conducted postdoctoral research at the University of Tokyo, JSPS, NEDO, and the University of Toronto, focusing on small molecule activation, energy materials & devices, and catalytic material development.

      Prof. Zhong has been selected into the **National Youth Talent Program (Overseas, 2018)**, Jiangsu Shuangchuang Talent (2020), NJU Education–Research Integration Award (2022), the Young Scientist Award of the Japan Materials Research Society (2012), and the JSPS Fellowship (2011-2013). He has led two general-program grants from the NSFC, participated in one National Key R&D Project of MOST, and headed projects under the Jiangsu Carbon-Peak & Carbon-Neutrality S&T Special Program, the Jiangsu Shuangchuang Team, the Jiangsu Six Talent Peaks Program, and the NJU Dengfeng Talent Program.

      As first or corresponding author (responsible affiliation) he has published >60 papers in **Nature, Nat. Catal., Nat. Commun. (3), J. Am. Chem. Soc. (2), Angew. Chem. Int. Ed. (2), Energy Environ. Sci.**, etc., accumulating ~6,000 independent citations, with 11 papers cited >100 times. He has authored two English book chapters, edited one English monograph, and co-edited one Chinese textbook. He has transferred one U.S. patent to TotalEnergies, licensed one Japanese patent, and applied/granted several Chinese patents.

      Research Interests: electro-/thermo-catalytic conversion of CO2 and other small molecules, catalytic reaction kinetics, surface & interfacial physical chemistry. If you are interested in our research, please forward all inquiries to Prof. Zhong at miaozhong@nju.edu.cn.

  



# 图片轮播  
heroSlideBlock:
  block: slider

  content:

    slides:

    - title: "" # desc-title1
      content:  "" # desc1
      align: center
      background:
        image:
          filename: group_slides/g1.png
          filters:
            brightness: 1
        position: right
        color: '#666'  

    - title:  "" # desc-title2
      content:  "" # desc2
      align: left
      background:
        image:
          filename: group_slides/g2.png
          filters:
            brightness: 1
        position: right
        color: '#666'  

  design:
    # Slide height is automatic unless you force a specific height (e.g. '400px')
    slide_height: '700px'
    is_fullscreen: false
    # Automatically transition through slides?
    loop: true
    # Duration of transition between slides (in ms)
    interval: 1000



# Recent works
recentWorksBlock:
  - img: recent_works/rw1.jpg
    desc: "STI-Bench: a benchmark designed to evaluate MLLMs’ spatial-temporal understanding through challenging tasks such as estimating and predicting the appearance, pose, displacement, and motion of objects."
    title: 
    link: https://mint-sjtu.github.io/STI-Bench.io/
    
  - img: recent_works/rw2.jpg
    desc: "[CVPR'25 Oral] We propose Video-XL, a novel approach that leverages MLLMs’ inherent KV sparsification capacity to condense the visual input realizes outstanding cost-effectiveness, enabling high-quality processing of thousands of frames on a single A100 GPU."
    title: 
    link: https://github.com/VectorSpaceLab/Video-XL/tree/main

  - img: recent_works/rw3.jpg
    desc: "[ICRA'25] We propose SpatialBot, a family of state-of-the-art VLMs, for effective depth understanding and thus precise robot manipulating in embodied AI by training on our constructed SpatialQA and SpatialQA-E datasets."
    title: 
    link: https://github.com/BAAI-DCAI/SpatialBot/

  - img: recent_works/rw4.jpg
    desc: "[ECCV'24] We introduces Omni6DPose, a substantial benchmark featured by its diversity in object categories, large scale, and variety in object materials, across 581 instances in 149 categories."
    title: 
    link: https://jiyao06.github.io/Omni6DPose/

  - img: recent_works/rw5.jpg
    desc: "[NeurIPS'24 Spotlight] We propose a 3D foundation segmentation model, named SegVol, supporting universal and interactive volumetric medical image segmentation, supporting the segmentation of over 200 anatomical categories."
    title: 
    link: https://github.com/BAAI-DCAI/SegVol

  - img: recent_works/rw6.jpg
    desc: "We introduce Emu3, a new suite of state-of-the-art multimodal models trained solely with next-token prediction. By tokenizing images, text, and videos into a discrete space, we train a single transformer from scratch on a mixture of multimodal sequences."
    title: 
    link: https://emu.baai.ac.cn/about







newsBlock:
  block: collection
  content:
    title: Latest News
    count: 5
    filters:
      author: ''
      category: ''
      exclude_featured: false
      publication_type: ''
      tag: ''
    offset: 0
    order: desc
    page_type: post
  design:
    view: card
    columns: '1'      




---  



