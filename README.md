<div align="center">
  <h1>👨‍💻 Awesome MLLM for Code</h1>
  <a href="https://awesome.re">
    <img src="https://awesome.re/badge.svg" alt="Awesome">
  </a>
  <a href="https://img.shields.io/badge/PRs-Welcome-red">
    <img src="https://img.shields.io/badge/PRs-Welcome-red" alt="PRs Welcome">
  </a>
  <a href="https://img.shields.io/github/last-commit/xjywhu/Awesome-Multimodal-LLM-for-Code?color=green">
    <img src="https://img.shields.io/github/last-commit/xjywhu/Awesome-Multimodal-LLM-for-Code?color=green" alt="Last Commit">
  </a>
</div>

![](mllm-code-logo.svg)


This repo includes papers about methods, benchmarks and evaluation for code generation under multimodal scenarios:
- UI Code Generation: Web front-end code generation, Mobile app UI code generation, etc。
- Scientific Code Generation: plot, chart, formula, etc.
- Slide code generation.
- Visually Rich Programming: programming problems with image examples.
- Logo: image generation through svg code generation.
- Program repair under above scenarios.
- UML code generation.
- CAD code generation.
- Poster code generation.
- General Benchmark.

[comment]: <> (multimodal code generation such as UI code generation, scientific plots code generation and so on.)

# Content

- [Awesome-Multimodal-LLM-for-Code](#Awesome-Multimodal-LLM-for-Code)
  * [Content](#content)
  * [📜 Papers](#papers)
      - [1. Web/UI Code Generation](#1-Web/UI-Code-Generation)
      - [2. Scientific Plots Code Generation](#2-Scientific-Plots-Code-Generation)
      - [3. Visually Rich Programming](#3-Visually-Rich-Programming)
      - [4. SVG Code Generation and Understanding](#4-SVG-Code-Generation-and-Understanding)
      - [5. Slide Code Generation](#5-Slide-Code-Generation)
      - [6. Program Repair](#6-Program-Repair)
      - [7. UML code generation](#7-UML-code-generation)
      - [8. CAD code generation](#8-CAD-code-generation)
      - [9. Poster code generation](#9-Poster-code-generation)
      - [10. Multimodal document generation](#10-Multimodal-document-generation)
      - [11. General](#11-General)
  * [🔥Contributing](#contributing)

---

# 📜 Papers

> You can directly click on the title to jump to the corresponding PDF link location

## 1. Web/UI Code Generation

1. [**Design2Code: How Far Are We From Automating Front-End Engineering?.**](https://arxiv.org/abs/2403.03163) *Chenglei Si, Yanzhe Zhang, Zhengyuan Yang, Ruibo Liu, Diyi Yang
.* NAACL 2025. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/NoviScl/Design2Code)](https://github.com/NoviScl/Design2Code)

2. [**Unlocking the conversion of Web Screenshots into HTML Code with the WebSight Dataset.**](https://arxiv.org/abs/2403.09029) *Hugo Laurençon, Léo Tronchon, Victor Sanh
.* Arxiv 2024.

3. [**VISION2UI: A Real-World Dataset with Layout for Code Generation from UI Designs.**](https://arxiv.org/abs/2404.06369) *Yi Gui, Zhen Li, Yao Wan, Yemin Shi, Hongyu Zhang, Yi Su, Shaoling Dong, Xing Zhou, Wenbin Jiang
.* Arxiv 2024. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

4. [**NLDesign: A UI Design Tool for Natural Language Interfaces**](https://dl.acm.org/doi/10.1145/3674399.3674455) *Tianhao Zhang, Fu Peiguo, Jie Liu, Yihe Zhang, Xingmei Chen
.* ACM-TURC‘24 (2024.6.30)

5. [**Automatically Generating UI Code from Screenshot: A Divide-and-Conquer-Based Approach.**](https://arxiv.org/abs/2406.16386) *Yuxuan Wan, Chaozheng Wang, Yi Dong, Wenxuan Wang, Shuqing Li, Yintong Huo, Michael R. Lyu
.* Arxiv 2024 (FSE 2025). &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/WebPAI/DCGen)](https://github.com/WebPAI/DCGen)

6. [**Web2Code: A Large-scale Webpage-to-Code Dataset and Evaluation Framework for Multimodal LLMs.**](https://arxiv.org/abs/2406.20098) *Sukmin Yun, Haokun Lin, Rusiru Thushara, Mohammad Qazim Bhat, Yongxin Wang, Zutao Jiang, Mingkai Deng, Jinhong Wang, Tianhua Tao, Junbo Li, Haonan Li, Preslav Nakov, Timothy Baldwin, Zhengzhong Liu, Eric P. Xing, Xiaodan Liang, Zhiqiang Shen
.* NeurIPS 2024 Datasets and Benchmarks. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/MBZUAI-LLM/web2code)](https://github.com/MBZUAI-LLM/web2code)

7. [**Prototype2Code: End-to-end Front-end Code Generation from UI Design Prototypes**](https://arxiv.org/abs/2405.04975) *Shuhong Xiao, Yunnong Chen, Jiazhi Li, Liuqing Chen, Lingyun Sun, Tingting Zhou
.* Arxiv 2024.

8. [**Bridging Design and Development with Automated Declarative UI Code Generation**](https://arxiv.org/abs/2409.11667) *Ting Zhou, Yanjie Zhao, Xinyi Hou, Xiaoyu Sun, Kai Chen, Haoyu Wang
.* Arxiv 2024.(FSE 2025)

9. [**Sketch2Code: Evaluating Vision-Language Models for Interactive Web Design Prototyping**](https://arxiv.org/abs/2410.16232) *Ryan Li, Yanzhe Zhang, Diyi Yang .* Arxiv 2024. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/SALT-NLP/Sketch2Code)](https://github.com/SALT-NLP/Sketch2Code)

10. [**Interaction2Code: How Far Are We From Automatic Interactive Webpage Generation?**](https://arxiv.org/abs/2411.03292) *Jingyu Xiao, Yuxuan Wan, Yintong Huo, Zhiyao Xu, Michael R.Lyu
.* Arxiv 2024 (ASE 2025). &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/WebPAI/Interaction2Code)](https://github.com/WebPAI/Interaction2Code)

11. [**UIClip: A Data-driven Model for Assessing User Interface Design**](https://dl.acm.org/doi/10.1145/3654777.3676408) *Jason Wu, Yi-Hao Peng, Xin Yue Li, Amanda Swearngin, Jeffrey P. Biham, Jeffrey Nichols
.* UIST 2024.

12. [**WAFFLE: Multi-Modal Model for Automated Front-End Development**](https://www.arxiv.org/abs/2410.18362) *Shanchao Liang, Nan Jiang, Shangshu Qian, Lin Tan
.* Arxiv 2024 (ACL 2025 Main). &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/lt-asset/Waffle)](https://github.com/lt-asset/Waffle)

13. [**MRWeb: An Exploration of Generating Multi-Page Resource-Aware Web Code from UI Designs**](https://arxiv.org/abs/2412.15310) *Yuxuan Wan, Yi Dong, Jingyu Xiao, Yintong Huo, Wenxuan Wang, Michael R. Lyu
.* Arxiv 2024. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/WebPAI/MRWeb)](https://github.com/WebPAI/MRWeb)

14. [**UICopilot: Automating UI Synthesis via Hierarchical Code Generation from Webpage Designs**](https://openreview.net/pdf?id=faMbH0wkye) * Yi Gui, Yao Wan, Zhen Li, Zhongyi Zhang, Dongping Chen, Hongyu Zhang, Yi Su, Bohua Chen, Xing Zhou, Wenbin Jiang, Xiangliang Zhang. WWW 2025 (Oral). &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

15. [**WebCode2M: A Real-World Dataset for Code Generation from Webpage Designs**](https://openreview.net/pdf?id=aeP5nmlw5B) * Yi Gui, Zhen Li, Yao Wan*, Yemin Shi, Hongyu Zhang, Yi Su, Bohua Chen, Dongping Chen, Siyuan Wu, Xing Zhou, Wenbin Jiang, Hai Jin, Xiangliang Zhang. WWW 2025 (Oral). &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

16. [**Zero-Shot Prompting Approaches for LLM-based Graphical User Interface Generation**](https://arxiv.org/abs/2412.11328) * Kristian Kolthoff, Felix Kretzer, Lennart Fiebig, Christian Bartelt, Alexander Maedche, Simone Paolo Ponzetto.Arxiv 2024.12. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

17. [**Towards Human-AI Synergy in UI Design: Enhancing Multi-Agent Based UI Generation with Intent Clarification and Alignment**](https://arxiv.org/abs/2412.20071) *Mingyue Yuan, Jieshan Chen, Yongquan Hu, Sidong Feng, Mulong Xie, Gelareh Mohammadi, Zhenchang Xing, Aaron Quigley.Arxiv 2024.12.28
    
18. [**Frontend Diffusion: Empowering Self-Representation of Junior Researchers and Designers Through Agentic Workflows**](https://arxiv.org/abs/2502.03788) *Zijian Ding, Qinshi Zhang, Mohan Chi, Ziyi Wang. Arxiv 2025. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;


19. [**UICrit: Enhancing Automated Design Evaluation with a UICritique Dataset**](https://arxiv.org/abs/2407.08850) *Peitong Duan, Chin-yi Chen, Gang Li, Bjoern Hartmann, Yang Li.* Arxiv 2024.7.11 (UIST 2024). &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/google-research-datasets/uicrit)](https://github.com/google-research-datasets/uicrit)

20. [**Advancing vision-language models in front-end development via data synthesis**](https://arxiv.org/html/2503.01619v1) *Tong Ge, Yashu Liu, Jieping Ye, Tianyi Li, Chao Wang
.* Arxiv 2025.3.3. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/Flame-Code-VLM/Flame-Code-VLM)](https://github.com/Flame-Code-VLM/Flame-Code-VLM)

21. [**Multimodal graph representation learning for website generation based on visual sketch**](https://arxiv.org/abs/2504.18729) *Tung D. Vu, Chung Hoang, Truong-Son Hy.* Arxiv 2025.4.26. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/HySonLab/Design2Code)](https://github.com/HySonLab/Design2Code)

22. [**WebGen-Bench: Evaluating LLMs on Generating Interactive and Functional Websites from Scratch**](https://arxiv.org/abs/2505.03733) *Zimu Lu, Yunqiao Yang, Houxing Ren, Haotian Hou, Han Xiao, Ke Wang, Weikang Shi, Aojun Zhou, Mingjie Zhan, Hongsheng Li.* Arxiv 2025.5.6. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/mnluzimu/WebGen-Bench)](https://github.com/mnluzimu/WebGen-Bench)

23. [**Web-Bench: A LLM Code Benchmark Based on Web Standards and Frameworks**](https://arxiv.org/abs/2505.17399) *Kai Xu, YiWei Mao, XinYi Guan, ZiLong Feng.* Arxiv 2025.5.12. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/bytedance/web-bench)](https://github.com/bytedance/web-bench)

24. [**FullFront: Benchmarking MLLMs Across the Full Front-End Engineering Workflow**](https://arxiv.org/abs/2505.17399) *Haoyu Sun, Huichen Will Wang, Jiawei Gu, Linjie Li, Yu Cheng.* Arxiv 2025.5.23. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/Mikivishy/FullFront)](https://github.com/Mikivishy/FullFront)

25. [**DesignBench: A Comprehensive Benchmark for MLLM-based Front-end Code Generation**](https://arxiv.org/abs/2506.06251) *Jingyu Xiao, Ming Wang, Man Ho Lam, Yuxuan Wan, Junliang Liu, Yintong Huo, Michael R. Lyu.* Arxiv 2025.6.6. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/WebPAI/DesignBench)](https://github.com/WebPAI/DesignBench)
    
26. [**WebUIBench: A Comprehensive Benchmark for Evaluating Multimodal Large Language Models in WebUI-to-Code**](https://arxiv.org/abs/2506.07818) *Zhiyu Lin, Zhengda Zhou, Zhiyuan Zhao, Tianrui Wan, Yilun Ma, Junyu Gao, Xuelong Li.* Arxiv 2025.6.9. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/MAIL-Tele-AI/WebUIBench)](https://github.com/MAIL-Tele-AI/WebUIBench)
    
27. [**MLLM-Based UI2Code Automation Guided by UI Layout Information**](https://arxiv.org/abs/2506.10376) *Fan Wu, Cuiyun Gao, Shuqing Li, Xin-Cheng Wen, Qing Liao.* Arxiv 2025.6.12.（ISSTA 2025） &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/ay7u1009/LayoutCoder)](https://github.com/ay7u1009/LayoutCoder/)
  
28. [**DesignCoder: Hierarchy-Aware and Self-Correcting UI Code Generation with Large Language Models**](https://arxiv.org/abs/2506.10376) *Fan Wu, Cuiyun Gao, Shuqing Li, Xin-Cheng Wen, Qing Liao.* Arxiv 2025.6.16.
  
29. [**FrontendBench: A Benchmark for Evaluating LLMs on Front-End Development via Automatic Evaluation**](https://www.arxiv.org/abs/2506.13832) *Hongda Zhu, Yiwen Zhang, Bing Zhao, Jingzhe Ding, Siyao Liu, Tong Liu, Dandan Wang, Yanan Liu, Zhaojian Lio.* Arxiv 2025.6.16.

30. [**ScreenCoder: Advancing Visual-to-Code Generation for Front-End Automation via Modular Multimodal Agents**](https://arxiv.org/pdf/2507.22827) *Yilei Jiang, Yaozhi Zheng, Yuxuan Wan, Jiaming Han, Qunzhong Wang, Michael R. Lyu, Xiangyu Yue.* Arxiv 2025.7.31. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/leigest519/ScreenCoder
)](https://github.com/leigest519/ScreenCoder)




## 2. Scientific Plots Code Generation

1. [**Plot2Code: A Comprehensive Benchmark for Evaluating Multi-modal Large Language Models in Code Generation from Scientific Plots.**](https://arxiv.org/abs/2405.07990) *Chengyue Wu, Yixiao Ge, Qiushan Guo, Jiahao Wang, Zhixuan Liang, Zeyu Lu, Ying Shan, Ping Luo
.* Arxiv 2024. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/TencentARC/Plot2Code)](https://github.com/TencentARC/Plot2Code)

2. [**MatPlotAgent: Method and Evaluation for LLM-Based Agentic Scientific Data Visualization.**](https://arxiv.org/abs/2402.11453) *Zhiyu Yang, Zihan Zhou, Shuo Wang, Xin Cong, Xu Han, Yukun Yan, Zhenghao Liu, Zhixing Tan, Pengyuan Liu, Dong Yu, Zhiyuan Liu, Xiaodong Shi, Maosong Sun
.* Arxiv 2024. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/thunlp/MatPlotAgent)](https://github.com/thunlp/MatPlotAgent)

3. [**ChartMimic: Evaluating LMM's Cross-Modal Reasoning Capability via Chart-to-Code Generation.**](https://arxiv.org/abs/2406.09961) Chufan Shi, Cheng Yang, Yaxin Liu, Bo Shui, Junjie Wang, Mohan Jing, Linran Xu, Xinyu Zhu, Siheng Li, Yuxiang Zhang, Gongye Liu, Xiaomei Nie, Deng Cai, Yujiu Yang
.* Arxiv 2024. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/ChartMimic/ChartMimic)](https://github.com/ChartMimic/ChartMimic)

4. [**From Words to Structured Visuals: A Benchmark and Framework for Text-to-Diagram Generation and Editing.**](https://arxiv.org/abs/2411.11916) Jingxuan Wei, Cheng Tan, Qi Chen, Gaowei Wu, Siyuan Li, Zhangyang Gao, Linzhuang Sun, Bihui Yu, Ruifeng Guo
.* Arxiv 2024. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

5. [**Is GPT-4V (ision) All You Need for Automating Academic Data Visualization? Exploring Vision-Language Models’ Capability in Reproducing Academic Charts.**](https://aclanthology.org/2024.findings-emnlp.485/) Zhehao Zhang, Weicheng Ma, Soroush Vosoughi
.* EMNLP 2024 (Findings). &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/zzh-SJTU/AcademiaChart)](https://github.com/zzh-SJTU/AcademiaChart)


6. [**ChartMoE: Mixture of Diversely Aligned Expert Connector for Chart Understanding.**](https://arxiv.org/abs/2409.03277) Zhengzhuo Xu, Bowen Qu, Yiyan Qi, Sinan Du, Chengjin Xu, Chun Yuan, Jian Guo.* Arxiv 2024.9 (ICLR 2025 Oral). &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/IDEA-FinAI/ChartMoE)](https://github.com/IDEA-FinAI/ChartMoE)


7. [**ChartCoder: Advancing Multimodal Large Language Model for Chart-to-Code Generation.**](https://arxiv.org/abs/2501.06598) Xuanle Zhao, Xianzhen Luo, Qi Shi, Chi Chen, Shuo Wang, Wanxiang Che, Zhiyuan Liu, Maosong Sun.* Arxiv 2025.1 (ACL 2025 Main). &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/thunlp/ChartCoder)](https://github.com/thunlp/ChartCoder)


8. [**nvAgent: Automated Data Visualization from Natural Language via Collaborative Agent Workflow.**](https://arxiv.org/abs/2502.05036) Geliang Ouyang, Jingyao Chen, Zhihe Nie, Yi Gui, Yao Wan, Hongyu Zhang, Dongping Chen.* Arxiv 2025.2.7 (ACL 2025 Main). &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/geliang0114/nvAgent)](https://github.com/geliang0114/nvAgent)

9. [**METAL: A Multi-Agent Framework for Chart Generation with Test-Time Scaling**](https://arxiv.org/abs/2502.17651) *Bingxuan Li, Yiwei Wang, Jiuxiang Gu, Kai-Wei Chang, Nanyun Peng.* Arxiv 2025.2.24 (ACL 2025 Main). &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/metal-chart-generation/metal)](https://github.com/metal-chart-generation/metal)

10. [**Chain of Functions: A Programmatic Pipeline for Fine-Grained Chart Reasoning Data**](https://arxiv.org/abs/2503.16260) *Zijian Li, Jingjing Fu, Lei Song, Jiang Bian, Jun Zhang, Rui Wang
.* Arxiv 2025.3.20.

11. [**Enhancing Chart-to-Code Generation in Multimodal Large Language Models via Iterative Dual Preference Learning.**](https://arxiv.org/pdf/2504.02906) Zhihan Zhang, Yixin Cao, and Lizi Liao.* Arxiv 2025.4.3. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/Zhihan72/Chart2Code)](https://github.com/Zhihan72/Chart2Code)

12. [**Draw with Thought: Unleashing Multimodal Reasoning for Scientific Diagram Generation.**](https://arxiv.org/abs/2504.09479) Zhiqing Cui, Jiahao Yuan, Hanqing Wang, Yanshu Li, Chenxu Du, Zhenglong Ding.* Arxiv 2025.4.13.
  
13. [**ChartEdit: How Far Are MLLMs From Automating Chart Analysis? Evaluating MLLMs' Capability via Chart Editing.**](https://arxiv.org/abs/2505.11935) Xuanle Zhao, Xuexin Liu, Haoyue Yang, Xianzhen Luo, Fanhu Zeng, Jianling Li, Qi Shi, Chi Chen.* Arxiv 2025.5.17. (ACL 2025 Findings).

14. [**ChartMuseum: Testing Visual Reasoning Capabilities of Large Vision-Language Models.**](https://arxiv.org/abs/2505.13444) Liyan Tang, Grace Kim, Xinyu Zhao, Thom Lake, Wenxuan Ding, Fangcong Yin, Prasann Singhal, Manya Wadhwa, Zeyu Leo Liu, Zayne Sprague, Ramya Namuduri, Bodun Hu, Juan Diego Rodriguez, Puyuan Peng, Greg Durrett.* Arxiv 2025.5.19.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/Liyan06/ChartMuseum)](https://github.com/Liyan06/ChartMuseum)

15. [**ChartCards: A Chart-Metadata Generation Framework for Multi-Task Chart Understanding.**](https://arxiv.org/abs/2505.11935) Yifan Wu, Lutao Yan, Leixian Shen, Yinan Mei, Jiannan Wang, Yuyu Luo.* Arxiv 2025.5.21.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/Evanwu1125/ChartCards)](https://github.com/Evanwu1125/ChartCards)

16. [**Multimodal DeepResearcher: Generating Text-Chart Interleaved Reports From Scratch with Agentic Framework.**](https://arxiv.org/abs/2506.02454) Zhaorui Yang, Bo Pan, Han Wang, Yiyao Wang, Xingyu Liu, Minfeng Zhu, Bo Zhang, Wei Chen.* Arxiv 2025.6.3.
  
17. [**Generating Pedagogically Meaningful Visuals for Math Word Problems: A New Benchmark and Analysis of Text-to-Image Models.**](https://arxiv.org/abs/2506.03735) Junling Wang, Anna Rutkiewicz, April Yi Wang, Mrinmaya Sachan.* Arxiv 2025.6.4. (ACL 2025 Findings) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/eth-lre/math2visual)](https://github.com/eth-lre/math2visual)

18. [**Effective Training Data Synthesis for Improving MLLM Chart Understanding.**](https://arxiv.org/abs/2508.06492) Yuwei Yang, Zeyu Zhang, Yunzhong Hou, Zhuowan Li, Gaowen Liu, Ali Payani, Yuan-Sen Ting, Liang Zheng. Arxiv 2025.8.8. (ICCV 2025) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/yuweiyang-anu/ECD)](https://github.com/yuweiyang-anu/ECD)




## 3. Visually Rich Programming and Math

1. [**MMCode: Evaluating Multi-Modal Code Large Language Models with Visually Rich Programming Problems.**](https://arxiv.org/abs/2404.09486) *Kaixin Li, Yuchen Tian, Qisheng Hu, Ziyang Luo, Jing Ma
.* Arxiv 2024. EMNLP 2024 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/happylkx/MMCode)](https://github.com/happylkx/MMCode)

2. [**HumanEval-V: Evaluating Visual Understanding and Reasoning Abilities of Large Multimodal Models Through Coding Tasks.**](https://arxiv.org/abs/2410.12381) *Fengji Zhang, Linquan Wu, Huiyu Bai, Guancheng Lin, Xiao Li, Xiao Yu, Yue Wang, Bei Chen, Jacky Keung
.* Arxiv 2024. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/HumanEval-V/HumanEval-V-Benchmark)](https://github.com/HumanEval-V/HumanEval-V-Benchmark)

3. [**DynEx: Dynamic Code Synthesis with Structured Design Exploration for Accelerated Exploratory Programming.**](https://arxiv.org/pdf/2410.00400) *Jenny Ma, Karthik Sreedhar, Vivian Liu, Sitong Wang, Pedro Alejandro Perez, Riya Sahni, Lydia B. Chilton
.* Arxiv 2024.
   
4. [**ScratchEval: Are GPT-4o Smarter than My Child? Evaluating Large Multimodal Models with Visual Programming Challenges.**](https://arxiv.org/abs/2411.18932) *Rao Fu, Ziyang Luo, Hongzhan Lin, Zhen Ye, Jing Ma
.* Arxiv 2024. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/HKBUNLP/ScratchEval)](https://github.com/HKBUNLP/ScratchEval)

5. [**Code-Vision: Evaluating Multimodal LLMs Logic Understanding and Code Generation Capabilities.**](https://arxiv.org/abs/2502.11829) * Hanbin Wang, Xiaoxuan Zhou, Zhipeng Xu, Keyuan Cheng, Yuxin Zuo, Kai Tian, Jingwei Song, Junting Lu, Wenhui Hu, Xueyang Liu
.* Arxiv 2025.02.17. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/wanghanbinpanda/CodeVision)](https://github.com/wanghanbinpanda/CodeVision)

6. [**MathCoder-VL: Bridging Vision and Code for Enhanced Multimodal Mathematical Reasoning.**](https://arxiv.org/abs/2505.10557) * Ke Wang, Junting Pan, Linda Wei, Aojun Zhou, Weikang Shi, Zimu Lu, Han Xiao, Yunqiao Yang, Houxing Ren, Mingjie Zhan, Hongsheng Li
.* Arxiv 2025.05.15. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/mathllm/MathCoder)](https://github.com/mathllm/MathCoder)








## 4. SVG Code Generation and Understanding

1. [**StarVector: Generating Scalable Vector Graphics Code from Images and Text**](https://arxiv.org/abs/2312.11556) *Juan A. Rodriguez, Abhay Puri, Shubham Agarwal, Issam H. Laradji, Pau Rodriguez, Sai Rajeswar, David Vazquez, Christopher Pal, Marco Pedersoli.* Arxiv 2023. (CVPR 2025)

2. [**LogoMotion: Visually Grounded Code Generation for Content-Aware Animation.**](https://arxiv.org/abs/2405.07065) *Vivian Liu, Rubaiat Habib Kazi, Li-Yi Wei, Matthew Fisher, Timothy Langlois, Seth Walker, Lydia Chilton
.* Arxiv 2024 (CHI 2025).

3. [**SVGEditBench: A Benchmark Dataset for Quantitative Assessment of LLM's SVG Editing Capabilities.**](https://arxiv.org/abs/2404.13710) *Kunato Nishina, Yusuke Matsui.* Arxiv 2024.4.21 (CVPR 2024 Workshop). &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/mti-lab/SVGEditBench)](https://github.com/mti-lab/SVGEditBench)

4. [**Chat2SVG: Vector Graphics Generation with Large Language Models and Image Diffusion Models.**](https://arxiv.org/abs/2411.16602) *Ronghuan Wu, Wanchao Su, Jing Liao
.* Arxiv 2024 (CVPR 2025). &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/kingnobro/chat2svg)](https://github.com/kingnobro/chat2svg)


5. [**Can Large Language Models Understand Symbolic Graphics Programs?**](https://arxiv.org/abs/2408.08313) *Zeju Qiu, Weiyang Liu, Haiwen Feng, Zhen Liu, Tim Z. Xiao, Katherine M. Collins, Joshua B. Tenenbaum, Adrian Weller, Michael J. Black, Bernhard Schölkopf.* ICLR 2025 (Spotlight). &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/sgp-bench/sgp-bench)](https://github.com/sgp-bench/sgp-bench)

6. [**LLM4SVG: Empowering LLMs to Understand and Generate Complex Vector Graphics**](https://arxiv.org/abs/2412.11102) *Ximing Xing, Juncheng Hu, Guotao Liang, Jing Zhang, Dong Xu, Qian Yu.* CVPR 2025. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/ximinng/LLM4SVG)](https://github.com/ximinng/LLM4SVG)
  
7. [**OmniSVG: A Unified Scalable Vector Graphics Generation Model.**](https://arxiv.org/abs/2504.06263) *Yiying Yang, Wei Cheng, Sijin Chen, Xianfang Zeng, Jiaxu Zhang, Liao Wang, Gang Yu, Xingjun Ma, Yu-Gang Jiang.* Arxiv 2025.4.8. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/OmniSVG/OmniSVG)](https://github.com/OmniSVG/OmniSVG)

8. [**Reason-SVG: Hybrid Reward RL for Aha-Moments in Vector Graphics Generation.**](https://arxiv.org/abs/2505.24499) *Ximing Xing, Yandong Guan, Jing Zhang, Dong Xu, Qian Yu.* Arxiv 2025.5.30.

9. [**SVGenius: Benchmarking LLMs in SVG Understanding, Editing and Generation.**](https://arxiv.org/abs/2504.06263) *Siqi Chen, Xinyu Dong, Haolei Xu, Xingyu Wu, Fei Tang, Hang Zhang, Yuchen Yan, Linjuan Wu, Wenqi Zhang, Guiyang Hou, Yongliang Shen, Weiming Lu, Yueting Zhuang.* Arxiv 2025.6.3.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/ZJU-REAL/SVGenius)](https://github.com/ZJU-REAL/SVGenius)




## 5. Slide Code Generation

1. [**AutoPresent: Designing Structured Visuals from Scratch.**](https://www.arxiv.org/abs/2501.00912) *Jiaxin Ge, Zora Zhiruo Wang, Xuhui Zhou, Yi-Hao Peng, Sanjay Subramanian, Qinyue Tan, Maarten Sap, Alane Suhr, Daniel Fried, Graham Neubig, Trevor Darrell
.* Arxiv 2025.1.1 (CVPR 2025). [![GitHub Repo stars](https://img.shields.io/github/stars/para-lost/AutoPresent)](https://github.com/para-lost/AutoPresent)

2. [**PPTAgent: Generating and Evaluating Presentations Beyond Text-to-Slides.**](https://arxiv.org/abs/2501.03936) *Hao Zheng, Xinyan Guan, Hao Kong, Jia Zheng, Hongyu Lin, Yaojie Lu, Ben He, Xianpei Han, Le Sun
.* Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/icip-cas/PPTAgent)](https://github.com/icip-cas/PPTAgent)

3. [**Talk to Your Slides: Language-Driven Agents for Efficient Slide Editing.**](https://arxiv.org/abs/2505.11604) *Kyudan Jung, Hojun Cho, Jooyeol Yun, Soyoung Yang, Jaehyeok Jang, Jaegul Choo.* Arxiv 2025.5.16 (https://anonymous.4open.science/r/Talk-to-Your-Slides-0F4C)

4. [**PreGenie: An Agentic Framework for High-quality Visual Presentation.**](https://arxiv.org/abs/2505.21660) *Xiaojie Xu, Xinli Xu, Sirui Chen, Haoyu Chen, Fan Zhang, Ying-Cong Chen
.* Arxiv 2025.5.27.

5. [**SlideCoder: Layout-aware RAG-enhanced Hierarchical Slide Generation from Design.**](https://www.arxiv.org/abs/2506.07964) *Wenxin Tang, Jingyu Xiao, Wenxuan Jiang, Xi Xiao, Yuhang Wang, Xuxin Tang, Qing Li, Yuehe Ma, Junliang Liu, Shisong Tang, Michael R. Lyu
.* Arxiv 2025.6.9. [![GitHub Repo stars](https://img.shields.io/github/stars/vinsontang1/SlideCoder)](https://github.com/vinsontang1/SlideCoder)

6. [**PresentAgent: Multimodal Agent for Presentation Video Generation.**](https://www.arxiv.org/abs/2507.04036) *Jingwei Shi, Zeyu Zhang, Biao Wu, Yanjie Liang, Meng Fang, Ling Chen, Yang Zhao
.* Arxiv 2025.7.5. [![GitHub Repo stars](https://img.shields.io/github/stars/AIGeeksGroup/PresentAgent)](https://github.com/AIGeeksGroup/PresentAgent)




## 6. Program Repair

1. [**SWE-bench Multimodal: Do AI Systems Generalize to Visual Software Domains?**](https://arxiv.org/abs/2410.03859) *John Yang, Carlos E. Jimenez, Alex L. Zhang, Kilian Lieret, Joyce Yang, Xindi Wu, Ori Press, Niklas Muennighoff, Gabriel Synnaeve, Karthik R. Narasimhan, Diyi Yang, Sida I. Wang, Ofir Press.* ICLR 2025.

2. [**DesignRepair: Dual-Stream Design Guideline-Aware Frontend Repair with Large Language Models**](https://arxiv.org/abs/2411.01606) * Mingyue Yuan, Jieshan Chen, Zhenchang Xing, Aaron Quigley, Yuyu Luo, Gelareh Mohammadi, Qinghua Lu, Liming Zhu.* ICSE 2025.  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/DesignRepair2024/DesignRepair2024)](https://github.com/DesignRepair2024/DesignRepair2024)

3. [**CodeV: Issue Resolving with Visual Data**](https://arxiv.org/abs/2412.17315) *Linhao Zhang, Daoguang Zan, Quanshun Yang, Zhirong Huang, Dong Chen, Bo Shen, Tianyu Liu, Yongshun Gong, Pengjie Huang, Xudong Lu, Guangtai Liang, Lizhen Cui, Qianxiang Wang .* Arxiv 2024. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/luolin101/CodeV)](https://github.com/luolin101/CodeV)

4. [**Seeing is Fixing: Cross-Modal Reasoning with Multimodal LLMs for Visual Software Issue Fixing**](https://www.arxiv.org/abs/2506.16136) *Kai Huang, Jian Zhang, Xiaofei Xie, Chunyang Chen .* Arxiv 2025.6.19.



## 7. UML and workflow code generation

1. [**From Image to UML: First Results of Image-Based UML Diagram Generation using LLMs**](https://arxiv.org/pdf/2404.11376) *Arie van Deursen, Eduard C. Groen .* LLM4MDE 2024.
2. [**StarFlow: Generating Structured Workflow Outputs From Sketch Images**](https://arxiv.org/abs/2503.21889) *Patrice Bechard, Chao Wang, Amirhossein Abaskohi, Juan Rodriguez, Christopher Pal, David Vazquez, Spandana Gella, Sai Rajeswar, Perouz Taslakian. Arxiv 2025.03.27.





## 8. CAD code generation

1. [**mrCAD: Multimodal Refinement of Computer-aided Designs**](https://arxiv.org/abs/2504.20294) *William P. McCarthy, Saujas Vaduguru, Karl D. D. Willis, Justin Matejka, Judith E. Fan, Daniel Fried, Yewen Pu .* Arxiv 2025.04.28. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/AutodeskAILab/mrCAD)](https://github.com/AutodeskAILab/mrCAD)

2. [**CADReview: Automatically Reviewing CAD Programs with Error Detection and Correction**](https://arxiv.org/abs/2505.22304) *Jiali Chen, Xusen Hei, HongFei Liu, Yuancheng Wei, Zikun Deng, Jiayuan Xie, Yi Cai, Li Qing .* Arxiv 2025.05.28 (ACL 2025 Main Oral). &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/Gary-code/CADReview)](https://github.com/Gary-code/CADReview)




## 9. Poster code generation

1. [**Paper2Poster: Towards Multimodal Poster Automation from Scientific Papers**](https://arxiv.org/abs/2505.21497) *Wei Pang, Kevin Qinghong Lin, Xiangru Jian, Xi He, Philip Torr .* Arxiv 2025.05.27. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/Paper2Poster/Paper2Poster)](https://github.com/Paper2Poster/Paper2Poster)
2. [**P2P: Automated Paper-to-Poster Generation and Fine-Grained Benchmark**](https://arxiv.org/abs/2505.17104) *Tao Sun, Enhao Pan, Zhengkai Yang, Kaixin Sui, Jiajun Shi, Xianfu Cheng, Tongliang Li, Wenhao Huang, Ge Zhang, Jian Yang, Zhoujun Li.* Arxiv 2025.05.21. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/multimodal-art-projection/P2P)](https://github.com/multimodal-art-projection/P2P)

## 10. Multimodal document generation

1. [**BigDocs: An Open and Permissively-Licensed Dataset for Training Multimodal Models on Document and Code Tasks**](https://arxiv.org/abs/2412.04626) *Juan Rodriguez, Xiangru Jian, Siba Smarak Panigrahi, Tianyu Zhang, Aarash Feizi, Abhay Puri, Akshay Kalkunte, François Savard, Ahmed Masry, Shravan Nayak, Rabiul Awal, Mahsa Massoud, Amirhossein Abaskohi, Zichao Li, Suyuchen Wang, Pierre-André Noël, Mats Leon Richter, Saverio Vadacchino, Shubham Agarwal, Sanket Biswas, Sara Shanian, Ying Zhang, Noah Bolger, Kurt MacDonald, Simon Fauvel, Sathwik Tejaswi, Srinivas Sunkara, Joao Monteiro, Krishnamurthy DJ Dvijotham, Torsten Scholak, Nicolas Chapados, Sepideh Kharagani, Sean Hughes, M. Özsu, Siva Reddy, Marco Pedersoli, Yoshua Bengio, Christopher Pal, Issam Laradji, Spandana Gella, Perouz Taslakian, David Vazquez, Sai Rajeswar. ICLR 2025

2. [**Multimodal DeepResearcher: Generating Text-Chart Interleaved Reports From Scratch with Agentic Framework**](https://arxiv.org/abs/2506.02454) *Zhaorui Yang, Bo Pan, Han Wang, Yiyao Wang, Xingyu Liu, Minfeng Zhu, Bo Zhang, Wei Chen.* Arxiv 2025.06.03.

   
## 11. General

1. [**Image2Struct: Benchmarking Structure Extraction for Vision-Language Models**](https://arxiv.org/abs/2410.22456) *Josselin Somerville Roberts, Tony Lee, Chi Heem Wong, Michihiro Yasunaga, Yifan Mai, Percy Liang
.* NeurIPS 2024 Datasets and Benchmarks.

2. [**FullStack Bench: Evaluating LLMs as Full Stack Coders**](https://arxiv.org/abs/2412.00535) *Siyao Liu, He Zhu, Jerry Liu, Shulin Xin, Aoyan Li, Rui Long, Li Chen, Jack Yang, Jinxiang Xia, Z.Y. Peng, Shukai Liu, Zhaoxiang Zhang, Jing Mai, Ge Zhang, Wenhao Huang, Kai Shen, Liang Xiang
.* Arxiv 2024. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/bytedance/FullStackBench)](https://github.com/bytedance/FullStackBench)


3. [**Empowering Agile-Based Generative Software Development through Human-AI Teamwork**](https://arxiv.org/abs/2407.15568) *Sai Zhang, Zhenchang Xing, Ronghui Guo, Fangzhou Xu, Lei Chen, Zhaoyuan Zhang, Xiaowang Zhang, Zhiyong Feng, Zhiqiang Zhuang
.* TOSEM 2024. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/UGAIForge/AgileGen)](https://github.com/UGAIForge/AgileGen)

4. [**Automated LaTeX Code Generation from Handwritten Mathematical Expressions**](https://arxiv.org/html/2412.03853v2) *Jayaprakash Sundararaj, Akhil Vyas, Benjamin Gonzalez-Maldonado.* Arxiv 2024.
   
5. [**ArtifactsBench: Bridging the Visual-Interactive Gap in LLM Code Generation Evaluation**](https://arxiv.org/abs/2507.04952) *Chenchen Zhang, Yuhang Li, Can Xu, Jiaheng Liu, Ao Liu, Shihui Hu, Dengpeng Wu, Guanhua Huang, Kejiao Li, Qi Yi, Ruibin Xiong, Haotian Zhu, Yuanxing Zhang, Yuhao Jiang, Yue Zhang, Zenan Xu, Bohui Zhai, Guoxiang He, Hebin Li, Jie Zhao, Le Zhang, Lingyun Tan, Pengyu Guo, Xianshu Pang, Yang Ruan, Zhifeng Zhang, Zhonghu Wang, Ziyan Xu, Zuopu Yin, Wiggin Zhou, Chayse Zhou, Fengzong Lian.* Arxiv 2025.07.07. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/Tencent-Hunyuan/ArtifactsBenchmark)](https://github.com/Tencent-Hunyuan/ArtifactsBenchmark)



# 🔥Contributing
This is an active repository and your contributions are always welcome! Before you add papers/tools into the awesome list, please make sure that:
- First, think about which category the work should belong to.
- The paper or tools is related to Multimodal Large Language Models (MLLMs) for code generation.
- The paper should be inserted in the correct position in chronological order (publication/arxiv release time).
- The link to paper should be the arxiv page, not the pdf page if this is a paper posted on arxiv.
- If the paper is accpeted, please use the correct publication venue instead of arxiv.

# 🌟 Star History

[![Star History Chart](https://api.star-history.com/svg?repos=xjywhu/Awesome-Multimodal-LLM-for-Code&type=Date)](https://www.star-history.com/#xjywhu/Awesome-Multimodal-LLM-for-Code&Date)
