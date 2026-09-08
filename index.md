---
layout: default
title: 人工智能芯片：设计与实践
---

## COURSE INFORMATION

- Lecture Location: 昌平新校区-206
- Lecture time:	9:00am-11:50am，周三（1～16周）
- Instructor: Dr. Bonan Yan 燕博南 (site: [bonany.cc](https://bonany.cc))
- Teaching Assistant: 周钜宸 (zjc AT stu.pku.edu.cn)
- Email: bonanyan AT pku.edu.cn

## AGENDA

| Week | Date                                                      | Lecture                                                                                                                                                                                                                    | Reference                                                                                                | Assignment |
| ---- | --------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------- | ---------- |
| 1    | 9/10                                                      | Class Introduction [\[slides\]](/assets/lec/Lec1_intro.pdf)                                                                                                                                                                | Verilog HDL 2005 Standard [\[doc\]](/assets/lec/IEEE.1364-2005_Verilog2005.pdf)                          |            |
| 2    | 9/17                                                      | Advanced HDL basics & Timing                                                                                                                                                                                               | FSM Templates:[1](/assets/other/mealy_state_machine_v.zip), [2](/assets/other/moore_state_machine_v.zip) |            |
| 3    | 9/24                                                      | Latest AI Chip Architectures                                                                                                                                                                                               |                                                                                                          |            |
| 4    | 10/1                                                      | Happy holiday😃                                                                                                                                                                                                           |                                                                                                          |            |
| 5    | 10/8                                                      | Happy holiday😃                                                                                                                                                                                                           |                                                                                                          |            |
| 6    | 10/15                                                     | TPU vs GPU ([Paper1](https://www.eecs.harvard.edu/~htk/publication/1988-supercomputing-borkar-etc.pdf), [Paper2](https://dl.acm.org/doi/abs/10.1145/3079856.3080246), [Code1](https://github.com/tiny-tpu-v2/tiny-tpu/))   |                                                                                                          |            |
| 7    | 10/22                                                     | Neuromorphic Computer ([Paper1](https://www.science.org/doi/10.1126/science.1254642), [Paper2](https://ieeexplore.ieee.org/document/8259423), [Paper3](https://www.nature.com/articles/s41586-024-08253-8))                |                                                                                                          |            |
| 8    | 10/29                                                     | CNN ASICs ([Paper1](https://ieeexplore.ieee.org/abstract/document/7738524), [Paper2](/lec/HC2023.Session7.ML_Inference.IBM.DharmendraModha.Final.pdf), [Code1](https://github.com/lulinchen/cnn_open))                         |                                                                                                          |            |
| 9    | 11/5                                                      | RISC-V for AI ([Paper1](/assets/lec/88_HC2024.Tenstorrent.Jasmina.Davor.v7.pdf), [Paper2](https://people.eecs.berkeley.edu/~krste/papers/EECS-2015-263.pdf), [Code1](https://docs.tenstorrent.com/tt-metal/latest/ttnn/index.html)) | assignment (设计架构框图，分工接口表) due 23:59:00, 11/26/2025，每组提交至微信群                                                                       |            |
| 10   | 11/12                                                     | Dataflow ([Paper1](https://dl.acm.org/doi/abs/10.1145/27633.28055), [Paper2](https://dl.acm.org/doi/abs/10.1145/3140659.3080256), [Historical View](https://ieeexplore.ieee.org/abstract/document/329757))                                                                                                                                                                                           |                                                                                                          |            |
| 11   | 11/19                                                     | Wafer-scale Architectures ([Paper1](https://ieeexplore.ieee.org/document/10460211), Paper2 Cerebras Chip [1](https://ieeexplore.ieee.org/document/9623424)[2](https://ieeexplore.ieee.org/document/10495794)[3](https://ieeexplore.ieee.org/document/10123162))                                                                                                                                                                          |                                                                                                          |            |
| 12   | 11/26                                                     | Processing-In-Memory ([RRAM PIM](https://ieeexplore.ieee.org/document/7551380), [DRAM PIM SW](https://ieeexplore.ieee.org/document/9499894),[DRAM PIM Primer](https://arxiv.org/abs/2012.03112), [Code APIM & DPIM](https://bonany.gitlab.io/pis/apim/))                                                                                                                                                                               |                                                                                                          |            |
| 13   | 12/3                                                      | LLM Accelerator ([Comprehensive Review](https://arxiv.org/abs/2410.04466), [Paper2](https://ieeexplore.ieee.org/document/9895630))                                                                                                                                                                                    |                                                                                                          |            |
| 14   | 12/10                                                     | Optical Communications & Computing ([Paper1](https://www.nature.com/articles/s41586-025-09430-z), [Paper2](https://www.nature.com/articles/s41566-021-00796-w))                                                                                                                                                                 |                                                                                                          |            |
| 15   | 12/17                                                     | Quantum AI Computing ([Basics](/assets/lec/T3Visuals.pdf), [Paper1](https://www.nature.com/articles/s41467-020-14454-2), [Paper2](https://iopscience.iop.org/article/10.1088/1361-6633/aab406))                                                                                                                                                                               |                                                                                                          |            |
| 16   | 12/24                                                     | Final Presentation                                                                                                                                                                                                         |                                                                                                          |            |
| 19   | Jan 13 11:59:00,2025 (tentative) Final Project Submission | [Final Exam Week] No Lecture                                                                                                                                                                                               |                                                                                                          |            |


## USEFUL TOOLS

- [Wavedrom](https://wavedrom.com): waveform drawing tool
- [iVerilog](https://github.com/steveicarus/iverilog): Verilog compilers/simulator
- [GTKWave](https://gtkwave.sourceforge.net): waveform viewer
- [PISLib](https://bonany.gitlab.io/pis/): behavioral models of processing-in-memory and memory
- [Memory RTL behavioral model](/other/memory-behavior-RTL-model.zip): behavioral model for memories


## GRADE BREAKDOWN

- Assignments: 20%
- Presentation: 40%
- Final Paper : 40%

---
