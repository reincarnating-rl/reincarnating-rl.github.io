---
layout: page
title: Call for Papers
permalink: /call-for-papers/
description: The field of machine learning (ML) is undergoing massive growth, and it is becoming apparent that it may be in need of self-reflection to ensure that efforts are directed towards real progress of the field [1-2]. More recently, there is an increasing number of papers at top conferences on the topic of ML evaluation, which show evidence of non-reliable findings and unsupported empirical claims in several subfields including computer vision [3-4], recommender systems [5], reinforcement learning [6-8], natural language processing [9-14], hyperparameter optimization [15-17] and more [18-24]. Such papers highlight the need for more scientific rigor and careful evaluation, both by researchers themselves and by reviewers. Therefore, it is clear that these are discussions that researchers are interested in having, while it is yet unclear what is the best path forward. We can accelerate this self-reflection by having thoughtful and careful discussions, and by gathering a diversity of opinions. 
nav: true
horizontal: false
---


We invite two types of papers -- opinion papers (up to 4 pages) and technical papers (up to 9 pages excluding references and appendix) about reusing prior computation in RL. In particular, we are interested in bringing together researchers and practitioners to discuss questions on theoretical, empirical and practical aspects of reusing prior computation in RL, including but not limited to:

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

Submission Site: <a href="??"> ?? </a>


We invite two types of papers -- opinion papers (up to 4 pages) stating positions on the topics
related to those listed above, and methodology papers (up to 8 pages excluding references) about
evaluation in ML. These topics may include: 

# Submission Website 
<a href="??"> ?? </a>

# Important Dates

- Submission deadline: **Feb 15 AoE**
- Accept/Reject Notification Date: 25th March
- Camera Ready: 18th April
- Workshop: 29th April 

# Submission instructions

We will accept technical papers of length up to 8 pages and opinion papers of length up to 4 pages,
excluding references and appendices and position papers. In order to gather a wide variety of views,
we will minimally constrain the format and topic areas for both types of papers. We will not accept
work published in prior ML conferences including ICLR 2023, and encourage the submission of working
papers. The submission process will be handled via CMT in a double-blind review process. Papers can
utilize any style file they want (for e.g., ICML, NeurIPS, ICLR) and should be anonymized for double
blind review.

The proceedings of the workshop will be non-archival. We will require authors of accepted papers to
provide a recorded video and a slide deck describing their work. We plan to divide the accepted
papers into two groups with different presentation types – contributed talks (10 min), and posters
(two poster sessions) – based on novelty, technical merit, and alignment to the workshop’s goals.

# References

[1] Michael Ahn, Anthony Brohan, Noah Brown, Yevgen Chebotar, Omar Cortes, Byron David, Chelsea Finn, Keerthana Gopalakrishnan, Karol Hausman, Alex Herzog, et al.  Do as I can, not as I say:  Grounding language in robotic affordances. arXiv preprint arXiv:2204.01691, 2022.

[2] Ilge Akkaya, Marcin Andrychowicz, Maciek Chociej, Mateusz Litwin, Bob McGrew, Arthur Petron, Alex Paino, Matthias Plappert, Glenn Powell, Raphael Ribas, et al.  Solving rubik’s cube with a robot hand. arXiv preprint arXiv:1910.07113, 2019.

[3] Christopher Berner, Greg Brockman, Brooke Chan, Vicki Cheung, Przemysław D ̨ebiak, Christy Dennison, David Farhi, Quirin Fischer, Shariq Hashme, Chris Hesse, et al. Dota 2 with large scale deep reinforcement learning. arXiv preprint arXiv:1912.06680, 2019.

[4] Yao Lu, Karol Hausman, Yevgen Chebotar, Mengyuan Yan, Eric Jang, Alexander Herzog, Ted Xiao, Alex Irpan, Mohi Khansari, Dmitry Kalashnikov, et al.  Aw-opt: Learning robotic skills with imitation and reinforcement at scale. In Conference on Robot Learning, pages 1078–1088. PMLR, 2022.

[5] Azalia Mirhoseini, Anna Goldie, Mustafa Yazgan, Joe Wenjie Jiang, Ebrahim Songhori, Shen Wang, Young-Joon Lee, Eric Johnson, Omkar Pathak, Azade Nazi, et al. A graph placement methodology for fast chip design. Nature, 594(7862):207–212, 2021.

[6] David Silver, Aja Huang, Chris J Maddison, Arthur Guez, Laurent Sifre, George Van Den Driessche, Julian Schrittwieser, Ioannis Antonoglou, Veda Panneershelvam, Marc Lanctot, et al. Mastering the game of go with deep neural networks and tree search. Nature, 529(7587):484–489, 2016.

[7] Oriol Vinyals, Igor Babuschkin, Wojciech M Czarnecki, Michaël Mathieu, Andrew Dudzik, Junyoung Chung, David H Choi, Richard Powell, Timo Ewalds, Petko Georgiev, et al. Grandmaster level in starcraft ii using multi-agent reinforcement learning. Nature, 575(7782):350–354, 2019.

[8] Trofin, Mircea, Yundi Qian, Eugene Brevdo, Zinan Lin, Krzysztof Choromanski, and David Li. "Mlgo: a machine learning guided compiler optimizations framework." arXiv preprint arXiv:2101.04808 (2021).

Reusing Network Weights for Fine-Tuning

[9] Bowen Baker, Ilge Akkaya, Peter Zhokhov, Joost Huizinga, Jie Tang, Adrien Ecoffet, Brandon Houghton, Raul Sampedro, and Jeff Clune.  Video pretraining (vpt): Learning to act by watching unlabeled online videos. arXiv preprint arXiv:2206.11795, 2022.

[10] Julian, Ryan, Benjamin Swanson, Gaurav S. Sukhatme, Sergey Levine, Chelsea Finn, and Karol Hausman. "Never stop learning: The effectiveness of fine-tuning in robotic reinforcement learning." arXiv preprint arXiv:2004.10190 (2020)

Reusing Learned Policies

[11] Agarwal, R., Schwarzer, M., Castro, P. S., Courville, A., & Bellemare, M. G. (2022).  Reincarnating Reinforcement Learning: Reusing Prior Computation to Accelerate Progress. NeurIPS

[12]  Lee, Alex X., Coline Devin, Jost Tobias Springenberg, Yuxiang Zhou, Thomas Lampe, Abbas Abdolmaleki, and Konstantinos Bousmalis. "How to spend your robot time: Bridging kickstarting and offline reinforcement learning for vision-based robotic manipulation." arXiv preprint arXiv:2205.03353 (2022).

[13] Uchendu, Ikechukwu, Ted Xiao, Yao Lu, Banghua Zhu, Mengyuan Yan, Joséphine Simon, Matthew Bennice et al. "Jump-Start Reinforcement Learning." arXiv preprint arXiv:2204.02372 (2022).

[14] Campos, Víctor, Pablo Sprechmann, Steven Hansen, Andre Barreto, Steven Kapturowski, Alex Vitvitskyi, Adria Puigdomenech Badia, and Charles Blundell. "Beyond fine-tuning: Transferring behavior in reinforcement learning." arXiv preprint arXiv:2102.13515 (2021).

Reusing Offline Data 

[15] Singh, Avi, Huihan Liu, Gaoyue Zhou, Albert Yu, Nicholas Rhinehart, and Sergey Levine. "Parrot: Data-Driven Behavioral Priors for Reinforcement Learning." ICLR (2021).

[16] Kostrikov, Ilya, Ashvin Nair, and Sergey Levine. "Offline Reinforcement Learning with Implicit Q-Learning." In International Conference on Learning Representations. 2022.

[17] Lee, Seunghyun, Younggyo Seo, Kimin Lee, Pieter Abbeel, and Jinwoo Shin. "Offline-to-online reinforcement learning via balanced replay and pessimistic q-ensemble." In Conference on Robot Learning, pp. 1702-1712. PMLR, 2022.

[18] Lee, Kuang-Huei, Ofir Nachum, Mengjiao Yang, Lisa Lee, Daniel Freeman, Winnie Xu, Sergio Guadarrama et al. "Multi-Game Decision Transformers." arXiv preprint arXiv:2205.15241 (2022).

Reusing Pretrained Representations

[19] Schwarzer, Max, Nitarshan Rajkumar, Michael Noukhovitch, Ankesh Anand, Laurent Charlin, R. Devon Hjelm, Philip Bachman, and Aaron C. Courville. "Pretraining representations for data-efficient reinforcement learning." Advances in Neural Information Processing Systems 34 (2021): 12686-12699.

[20] Stooke, Adam, Kimin Lee, Pieter Abbeel, and Michael Laskin. "Decoupling representation learning from reinforcement learning." In International Conference on Machine Learning, pp. 9870-9879. PMLR, 2021.

[21] Parisi, Simone, Aravind Rajeswaran, Senthil Purushwalkam, and Abhinav Gupta. "The unsurprising effectiveness of pre-trained vision models for control." arXiv preprint arXiv:2203.03580 (2022).

[22] Touati, Ahmed, and Yann Ollivier. "Learning one representation to optimize all rewards." Advances in Neural Information Processing Systems 34 (2021): 13-23.

[23] Liu, Hao, and Pieter Abbeel. "Behavior from the void: Unsupervised active pre-training." Advances in Neural Information Processing Systems 34 (2021): 18459-18473.

Reusing LLMs

[24] Huang Wenlong, Xia Fei, Xiao Ted, Chan Harris, Liang Jackie, Florence Pete, Zeng Andy, et al. “Inner Monologue: Embodied Reasoning through Planning with Language Models”. arXiv preprintarXiv:2207.05608.

[25] Zeng, Andy, et al. "Socratic models: Composing zero-shot multimodal reasoning with language." arXiv preprint arXiv:2204.00598 (2022).
 
[26] Shridhar, Mohit, Lucas Manuelli, and Dieter Fox. "Cliport: What and where pathways for robotic manipulation." Conference on Robot Learning. PMLR, 2022.
 
[27] Fan, Linxi, Guanzhi Wang, Yunfan Jiang, Ajay Mandlekar, Yuncong Yang, Haoyi Zhu, Andrew Tang, De-An Huang, Yuke Zhu, and Anima Anandkumar. "Minedojo: Building open-ended embodied agents with internet-scale knowledge." arXiv preprint arXiv:2206.08853 (2022).

Reusing Skills

[28] Matthews, Michael, Mikayel Samvelyan, Jack Parker-Holder, Edward Grefenstette, and Tim Rocktäschel. "Hierarchical Kickstarting for Skill Transfer in Reinforcement Learning." arXiv preprint arXiv:2207.11584 (2022).

[29] Pertsch, Karl, Youngwoon Lee, Yue Wu, and Joseph J. Lim. "Guided reinforcement learning with learned skills." arXiv preprint arXiv:2107.10253 (2021).

[30] Shi, Lucy Xiaoyang, Joseph J. Lim, and Youngwoon Lee. "Skill-based model-based reinforcement learning." arXiv preprint arXiv:2207.07560 (2022).

Reusing Models

[31] Sun, Yanchao, Ruijie Zheng, Xiyao Wang, Andrew Cohen, and Furong Huang. “Transfer RL across observation feature spaces via model-based regularization.” International Conference on Learning Representations (2022).

[32] Sasso, Remo, Matthia Sabatelli, and Marco A. Wiering. "Fractional transfer learning for deep model-based reinforcement learning." arXiv preprint arXiv:2108.06526 (2021).

[33] Sun, Yuewen, Kun Zhang, and Changyin Sun. "Model-Based Transfer Reinforcement Learning Based on Graphical Model Representations." IEEE Transactions on Neural Networks and Learning Systems (2021).
