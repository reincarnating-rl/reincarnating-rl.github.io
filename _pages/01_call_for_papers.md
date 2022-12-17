---
layout: page
title: Call for Papers
permalink: /call-for-papers/
description: Learning “tabula rasa”, that is, from scratch without much previously learned knowledge, is the dominant paradigm in reinforcement learning (RL) research. While learning tabula rasa works well for small-scale research domains, it is the exception rather than the norm for solving larger-scale problems [1, 2, 3, 4, 5, 6, 7, 8]. Large-scale RL systems often undergo multiple design or algorithmic changes during their development cycle and use ad hoc approaches for incorporating these changes without retraining from scratch, which would have been prohibitively expensive. Additionally, the inefficiency of tabula rasa RL typically excludes the majority of the RL community outside certain resource-rich labs from tackling computationally demanding problems. To address these inefficiencies of tabula rasa RL, this workshop would focus on the alternative paradigm of leveraging prior computational work, referred to as reincarnating RL [11], to accelerate training across design iterations of an RL agent or when moving from one agent to another. Recently, the research community has started to focus on this emerging paradigm, by leveraging computational work in the form of learned network weights (for fine-tuning) [9-10], learned policies [11-14], offline data [15-18], pretrained representations [19-23], LLMs [24-27], learned skills [28-30] or dynamics models [31-33] etc. Thus, it is evident that there is an interest in this important topic of leveraging prior computation in RL, to which our workshop can bring further attention. 
nav: true
horizontal: false
---

We invite two types of papers -- **opinion papers** (up to 4 pages) and **technical papers** (up to 9 pages excluding references and appendix) about reusing prior computation in RL. In particular, we are interested in bringing together researchers and practitioners to discuss questions on theoretical, empirical and practical aspects of reusing prior computation in RL, including but not limited to:

- Developing methods for accelerating RL training depending on type or combination of prior computation available:
  -  Learned policies
  -  Offline datasets 
  -  Pretrained dynamics models
  -  Foundation models or LLMs
  -  Pretrained representations
  -  Learned Skills
- Challenges for dealing with suboptimality of prior computational work
- Democratizing large-scale RL problems by releasing prior computation and formalizing the corresponding reincarnating RL setting.
- Algorithmic decisions and challenges associated with suboptimality of prior computational work
- Evaluation protocols, frameworks and standardized benchmarks for leveraging prior computation in RL research
- Real-world / Large-scale applications of reincarnating RL
- Properties of prior computational work needed to guarantee optimality of reincarnating RL methods
- Connection to transfer learning, lifelong learning and data-driven simulation.

### Special Track for benchmarking reincarnating RL  

Since the majority of RL benchmarks are designed with tabula rasa RL in mind, there is a lack of benchmarks for reincarnating RL that allow for reusing prior computation. To mitigate this difficulty, we plan to organize a workshop track for repurposing existing environments or designing new environments for benchmarking reincarnating RL. 

Specifically, this track will require researchers to (1) open-source / release computational work (e.g, network checkpoints of pretrained agents, representations, models etc) on any RL environment and (2) demonstrate how we can reuse this prior computation for accelerating RL training. The submissions to this track can be accompanied either by a short report between 2 - 4 pages (lightweight) or a full workshop submission.

**Infrastructure support for the special track**: To make it easy for releasing and using computational work, we will encourage submissions to use the <a href="https://huggingface.co/docs/hub/index"> Hugging Face Hub </a>, which is commonly used for NLP and vision models and has several features including: (1) free model hosting, (2)  built-in file versioning - even for huge files, (3) all public models are powered by the Inference API, and (4) in-browser widgets allow users to interact with hosted models directly. This track would be run with the official support of Hugging Face (Nathan Lambert) as well as maintainers of widely-used RL libraries, including <a href="https://github.com/DLR-RM/stable-baselines3"> SB3 </a> (Antonin Raffin) and <a href="https://github.com/vwxyzjn/cleanrl"> CleanRL </a> (Costa Huang). Please reach out to them for any questions related to the track.


## Submission Website 
<a href="https://openreview.net/group?id=ICLR.cc/2023/Workshop/RRL"> https://openreview.net/group?id=ICLR.cc/2023/Workshop/RRL </a>

## Important Dates

- Submission deadline: **Feb 15 AoE**, 2023
- Accept/Reject Notification Date: March 3, 2023
- Camera Ready: TBD
- Workshop: 5th May, 2023

## Submission instructions

We will accept technical papers of length up to 8 pages and opinion papers of length up to 4 pages,
excluding references and appendices and position papers. We also accept short papers on benchmarking 
reincarnating RL, as indicated in the details for special track above. In order to gather a wide variety
of views, we will minimally constrain the format and topic areas for both types of papers. We will not 
accept work published in prior ML conferences including ICLR 2023, and encourage the submission of working
papers. The submission process will be handled via CMT in a double-blind review process. Papers can
utilize any style file they want (for e.g., ICML, NeurIPS, ICLR) and should be anonymized for double
blind review.

The proceedings of the workshop will be non-archival. We will require authors of accepted papers to
provide a recorded video and a slide deck describing their work. We plan to divide the accepted
papers into two groups with different presentation types – contributed talks (10 min), and posters
(two poster sessions) – based on novelty, technical merit, and alignment to the workshop’s goals.


### References

[1] Michael Ahn, Anthony Brohan, Noah Brown, Yevgen Chebotar, Omar Cortes, Byron David, Chelsea Finn, Keerthana Gopalakrishnan, Karol Hausman, Alex Herzog, et al.  Do as I can, not as I say:  Grounding language in robotic affordances. arXiv preprint arXiv:2204.01691, 2022. 

[2] Ilge Akkaya, Marcin Andrychowicz, Maciek Chociej, Mateusz Litwin, Bob McGrew, Arthur Petron, Alex Paino, Matthias Plappert, Glenn Powell, Raphael Ribas, et al.  Solving rubik’s cube with a robot hand. arXiv preprint arXiv:1910.07113, 2019.

[3] Christopher Berner, Greg Brockman, Brooke Chan, Vicki Cheung, Przemysław D ̨ebiak, Christy Dennison, David Farhi, Quirin Fischer, Shariq Hashme, Chris Hesse, et al. Dota 2 with large scale deep reinforcement learning. arXiv preprint arXiv:1912.06680, 2019.

[4] Yao Lu, Karol Hausman, Yevgen Chebotar, Mengyuan Yan, Eric Jang, Alexander Herzog, Ted Xiao, Alex Irpan, Mohi Khansari, Dmitry Kalashnikov, et al.  Aw-opt: Learning robotic skills with imitation and reinforcement at scale. In Conference on Robot Learning, pages 1078–1088. PMLR, 2022.

[5] Azalia Mirhoseini, Anna Goldie, Mustafa Yazgan, Joe Wenjie Jiang, Ebrahim Songhori, Shen Wang, Young-Joon Lee, Eric Johnson, Omkar Pathak, Azade Nazi, et al. A graph placement methodology for fast chip design. Nature, 594(7862):207–212, 2021.

[6] David Silver, Aja Huang, Chris J Maddison, Arthur Guez, Laurent Sifre, George Van Den Driessche, Julian Schrittwieser, Ioannis Antonoglou, Veda Panneershelvam, Marc Lanctot, et al. Mastering the game of go with deep neural networks and tree search. Nature, 529(7587):484–489, 2016.

[7] Oriol Vinyals, Igor Babuschkin, Wojciech M Czarnecki, Michaël Mathieu, Andrew Dudzik, Junyoung Chung, David H Choi, Richard Powell, Timo Ewalds, Petko Georgiev, et al. Grandmaster level in starcraft ii using multi-agent reinforcement learning. Nature, 575(7782):350–354, 2019.

[8] Trofin, Mircea, Yundi Qian, Eugene Brevdo, Zinan Lin, Krzysztof Choromanski, and David Li. "Mlgo: a machine learning guided compiler optimizations framework." arXiv preprint arXiv:2101.04808 (2021).

*Reusing Network Weights for Fine-Tuning*

[9] Bowen Baker, Ilge Akkaya, Peter Zhokhov, Joost Huizinga, Jie Tang, Adrien Ecoffet, Brandon Houghton, Raul Sampedro, and Jeff Clune.  Video pretraining (vpt): Learning to act by watching unlabeled online videos. arXiv preprint arXiv:2206.11795, 2022.

[10] Julian, Ryan, Benjamin Swanson, Gaurav S. Sukhatme, Sergey Levine, Chelsea Finn, and Karol Hausman. "Never stop learning: The effectiveness of fine-tuning in robotic reinforcement learning." arXiv preprint arXiv:2004.10190 (2020)

*Reusing Learned Policies*

[11] Agarwal, R., Schwarzer, M., Castro, P. S., Courville, A., & Bellemare, M. G. (2022).  Reincarnating Reinforcement Learning: Reusing Prior Computation to Accelerate Progress. NeurIPS

[12]  Lee, Alex X., Coline Devin, Jost Tobias Springenberg, Yuxiang Zhou, Thomas Lampe, Abbas Abdolmaleki, and Konstantinos Bousmalis. "How to spend your robot time: Bridging kickstarting and offline reinforcement learning for vision-based robotic manipulation." arXiv preprint arXiv:2205.03353 (2022).

[13] Uchendu, Ikechukwu, Ted Xiao, Yao Lu, Banghua Zhu, Mengyuan Yan, Joséphine Simon, Matthew Bennice et al. "Jump-Start Reinforcement Learning." arXiv preprint arXiv:2204.02372 (2022).

[14] Campos, Víctor, Pablo Sprechmann, Steven Hansen, Andre Barreto, Steven Kapturowski, Alex Vitvitskyi, Adria Puigdomenech Badia, and Charles Blundell. "Beyond fine-tuning: Transferring behavior in reinforcement learning." arXiv preprint arXiv:2102.13515 (2021).

*Reusing Offline Data*

[15] Singh, Avi, Huihan Liu, Gaoyue Zhou, Albert Yu, Nicholas Rhinehart, and Sergey Levine. "Parrot: Data-Driven Behavioral Priors for Reinforcement Learning." ICLR (2021).

[16] Kostrikov, Ilya, Ashvin Nair, and Sergey Levine. "Offline Reinforcement Learning with Implicit Q-Learning." In International Conference on Learning Representations. 2022.

[17] Lee, Seunghyun, Younggyo Seo, Kimin Lee, Pieter Abbeel, and Jinwoo Shin. "Offline-to-online reinforcement learning via balanced replay and pessimistic q-ensemble." In Conference on Robot Learning, pp. 1702-1712. PMLR, 2022.

[18] Lee, Kuang-Huei, Ofir Nachum, Mengjiao Yang, Lisa Lee, Daniel Freeman, Winnie Xu, Sergio Guadarrama et al. "Multi-Game Decision Transformers." arXiv preprint arXiv:2205.15241 (2022).

*Reusing Pretrained Representations*

[19] Schwarzer, Max, Nitarshan Rajkumar, Michael Noukhovitch, Ankesh Anand, Laurent Charlin, R. Devon Hjelm, Philip Bachman, and Aaron C. Courville. "Pretraining representations for data-efficient reinforcement learning." Advances in Neural Information Processing Systems 34 (2021): 12686-12699.

[20] Stooke, Adam, Kimin Lee, Pieter Abbeel, and Michael Laskin. "Decoupling representation learning from reinforcement learning." In International Conference on Machine Learning, pp. 9870-9879. PMLR, 2021.

[21] Parisi, Simone, Aravind Rajeswaran, Senthil Purushwalkam, and Abhinav Gupta. "The unsurprising effectiveness of pre-trained vision models for control." arXiv preprint arXiv:2203.03580 (2022).

[22] Touati, Ahmed, and Yann Ollivier. "Learning one representation to optimize all rewards." Advances in Neural Information Processing Systems 34 (2021): 13-23.

[23] Liu, Hao, and Pieter Abbeel. "Behavior from the void: Unsupervised active pre-training." Advances in Neural Information Processing Systems 34 (2021): 18459-18473.

*Reusing LLMs*

[24] Huang Wenlong, Xia Fei, Xiao Ted, Chan Harris, Liang Jackie, Florence Pete, Zeng Andy, et al. “Inner Monologue: Embodied Reasoning through Planning with Language Models”. arXiv preprintarXiv:2207.05608.

[25] Zeng, Andy, et al. "Socratic models: Composing zero-shot multimodal reasoning with language." arXiv preprint arXiv:2204.00598 (2022).
 
[26] Shridhar, Mohit, Lucas Manuelli, and Dieter Fox. "Cliport: What and where pathways for robotic manipulation." Conference on Robot Learning. PMLR, 2022.
 
[27] Fan, Linxi, Guanzhi Wang, Yunfan Jiang, Ajay Mandlekar, Yuncong Yang, Haoyi Zhu, Andrew Tang, De-An Huang, Yuke Zhu, and Anima Anandkumar. "Minedojo: Building open-ended embodied agents with internet-scale knowledge." arXiv preprint arXiv:2206.08853 (2022).

*Reusing Skills*

[28] Matthews, Michael, Mikayel Samvelyan, Jack Parker-Holder, Edward Grefenstette, and Tim Rocktäschel. "Hierarchical Kickstarting for Skill Transfer in Reinforcement Learning." arXiv preprint arXiv:2207.11584 (2022).

[29] Pertsch, Karl, Youngwoon Lee, Yue Wu, and Joseph J. Lim. "Guided reinforcement learning with learned skills." arXiv preprint arXiv:2107.10253 (2021).

[30] Shi, Lucy Xiaoyang, Joseph J. Lim, and Youngwoon Lee. "Skill-based model-based reinforcement learning." arXiv preprint arXiv:2207.07560 (2022).

*Reusing Models*

[31] Sun, Yanchao, Ruijie Zheng, Xiyao Wang, Andrew Cohen, and Furong Huang. “Transfer RL across observation feature spaces via model-based regularization.” International Conference on Learning Representations (2022).

[32] Sasso, Remo, Matthia Sabatelli, and Marco A. Wiering. "Fractional transfer learning for deep model-based reinforcement learning." arXiv preprint arXiv:2108.06526 (2021).

[33] Sun, Yuewen, Kun Zhang, and Changyin Sun. "Model-Based Transfer Reinforcement Learning Based on Graphical Model Representations." IEEE Transactions on Neural Networks and Learning Systems (2021).


 *PS: The above references are only representative of relevant work and are not meant to be exhaustive. Please feel free to create a pull request for adding a relevant paper to the references above to the website <a href="https://github.com/reincarnating-rl/reincarnating-rl.github.io/blob/master/_pages/01_call_for_papers.md"> github repository</a>.*
