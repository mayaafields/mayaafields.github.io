---
title: "PROJECTS"
experience:
  enable : true
  # title : "Projects"
  experience_list:
    - name : "############Under Double Blind Review#######"  # Toleo: Scaling Freshness to Tera-scale Memory Using CXL and PIM
      company : "<u>Juechu Dong</u>, Jonahson Rosenblum, Satish Narayanasamy"
      duration : "ASPLOS\'24 -- under sumbission"
      content: " Scale trusted memory size from hundreds of MB to tens of TB by expanding the span of trusted from a single trusted processor to an entire platform including intelligent memories. <br>
                 Design a new scheme of freshness protection that reduces the space requirement by 50x. <br>
                 Reduce deployment cost by spacing sharing one intelligent memory device among multiple CPUs. "
    - name : "SECRET-GWAS: Confidential Computing for Population-Scale GWAS"
      company : "Jonahson Rosenblum, <u>Juechu Dong</u>, Satish Narayanasamy"
      duration : "RECOMB'24 -- under submission"
      content : "Develop a thousand-core platform on Azure Confidential Computing to conduct multi-institutional GWAS on millions of patients in less than a minute. <br>
                Adapt Spark-based Hail genomic analysis framework to run on TEE under obliviousness requirement. <br>
                Parallelize GWAS computation on 1k cores to achieve near linear speedup. "
    - name : "mm2-gb: GPU Accelerated Minimap2 for Long Read DNA Mapping"
      company : "<u>Juechu Dong</u>, Xueshen Liu, Harisankar Sadasivan, Sriranjani Sitaraman, Satish Narayanasamy"
      duration: "<a href=\"https://biosys-workshop.github.io/\">BioSys</a>-2024"
      content : "Accelerate computational intensive chaining step in the state-of-art long sequence mapping tool minimap2 by 2.57x-5.33x on ultra-long reads.<br>
                Optimize towards ultra long reads of 100k+ to accommodate genome sequencing technology trend. <br>
                Develop adaptive GPU scheduling algorithm to balance highly heterogeneous workload."
      img: "images/portfolio/mm2-workflow.png"
      cmt: "[[github](https://github.com/Minimap2onGPU/mm2-gb)] [[preprint](https://www.biorxiv.org/content/10.1101/2024.03.23.586366v1)]" 
      link: https://www.biorxiv.org/content/10.1101/2024.03.23.586366v1
    # - name : "Crossbar For Programmable Fully Homomorphic Encryption Accelerator"
    #   company : "advised by <a href=\"https://web.eecs.umich.edu/~rdreslin/\">Dr. Ronald Dreslinski</a> @UMich"
    #   duration : "2021 Sept - 2022 May"
    #   content : "Design extremely high bandwidth, statically scheduled crossbar for FHE accelerator F1 (MICRO 2021) with strict power and area restrictions. "
      
    - name : "Out-of-Order Processor Design"
      company : "EECS470 Computer Architecture Project"
      duration : "2021 Feb - 2021 Apr"
      content : "Design an out-of-order, 3-way scalar processor based on R10K design using system verilog. Add additional feature load store queue, advance branch predictor and cache heriachy. "
      img: "images/portfolio/EECS470rpt.jpg"
      link: "/blog/blog-3"

    # - name : "Fully-Autonomous SoC"
    #   company : "advised by <a href=\"https://web.eecs.umich.edu/~rdreslin/\">Prof. Ronald Dreslinski</a>"
    #   duration : "2021 Jan - 2021 May"
    #   content : "Build an intent solver that translates high-level user intent into hardware specifications and to satisfy user constraints, in particular, determines appropriate acceleration blocks for user python code</br> Attend weekly meetings with Dr. Dreslinski to develop basic research skills in experiment setup and to learn how to narrow down research interests and identify a new research topic"
    #   img: "images/portfolio/FASoC.jpg"
    #   link: "/blog/blog-1"

    # - name: "General Method to Roller Coaster Design and Analysis Based on NURBS Curves"
    #   company: "with Yanjun Chen and Haoyang Zhang"
    #   duration: "2019 Nov"
    #   content: "We won silver medal of University Physcis Competition 2019 with this design. It was a fantastic experience to do intensive brain storming and modeling in 48 hours. We didn't get much sleep, but a lot of fun. "
    #   img: "images/portfolio/UPC.jpg"


---