# Awesome-Agent-Skills-Papers

A curated list for agent skills papers, following the organization style of [Awesome-Efficient-LLM](https://github.com/horseee/Awesome-Efficient-LLM).

## Full List

- Skill Learning / Self-Improvement
- Skill-Oriented Reasoning / World Modeling
- Skill Routing / Orchestration / Ecosystems
- Skill Benchmarks / Evaluation
- Security / Robustness
- Survey / Taxonomy / Theory

### Notes

- This list is built from the papers you provided.
- The duplicated entries `2602.06130` and `2601.04748` are each included only once.
- For conceptual or survey papers without a single headline metric in the abstract, the “Introduction” field summarizes the main takeaway instead of forcing a number.

#### Contributing

If you'd like to add more skill papers, benchmarks, or repositories, feel free to extend the same markdown format:

`Title & Authors | Introduction | Links`

---

## Paper List (2025-10 - 2026-03)

### Quick Link

- [Skill Learning / Self-Improvement](#skill-learning--self-improvement)
- [Skill-Oriented Reasoning / World Modeling](#skill-oriented-reasoning--world-modeling)
- [Skill Routing / Orchestration / Ecosystems](#skill-routing--orchestration--ecosystems)
- [Skill Benchmarks / Evaluation](#skill-benchmarks--evaluation)
- [Security / Robustness](#security--robustness)
- [Survey / Taxonomy / Theory](#survey--taxonomy--theory)

---

## Skill Learning / Self-Improvement

| Title & Authors | Introduction | Links |
|:--|  :----: | :---:|
| **XSkill: Continual Learning from Experience and Skills in Multimodal Agents**<br>Guanyu Jiang, Zhaochen Su, Xiaoye Qu, Yi R. Fung | XSkill is a dual-stream continual-learning framework that distills visually grounded **experiences** and **skills** from multimodal rollouts and retrieves/adapts them at inference time, and it consistently outperforms both tool-only and learning-based baselines on five benchmarks with four backbone models. | [Paper](https://arxiv.org/abs/2603.12056) |
| **AutoSkill: Experience-Driven Lifelong Learning via Skill Self-Evolution**<br>Yutao Yang, Junsong Li, Qianjun Pan, Bihao Zhan, Yuxuan Cai, Lin Du, Jie Zhou, Kai Chen, Qin Chen, Xin Li, Bo Zhang, Liang He | AutoSkill is a model-agnostic lifelong-learning plugin that automatically derives, evolves, and reuses skills from interaction traces, with the paper emphasizing transferable standardized skill representations across agents, users, and tasks rather than a single headline benchmark number. | [Paper](https://arxiv.org/abs/2603.01145) |
| **SkillRL: Evolving Agents via Recursive Skill-Augmented Reinforcement Learning**<br>Peng Xia, Jianwen Chen, Hanyang Wang, Jiaqi Liu, Kaide Zeng, Yu Wang, Siwei Han, Yiyang Zhou, Xujiang Zhao, Haifeng Chen, Zeyu Zheng, Cihang Xie, Huaxiu Yao | SkillRL bridges raw experience and policy improvement by building a hierarchical SkillBank and recursively co-evolving it with the agent during RL, achieving state-of-the-art results on ALFWorld, WebShop, and seven search-augmented tasks while outperforming strong baselines by **15.3%+**. | [Paper](https://arxiv.org/abs/2602.08234) |
| **Evolving Programmatic Skill Networks**<br>Haochen Shi, Xingdi Yuan, Bang Liu | PSN represents skills as executable symbolic programs in a compositional network that grows through reflection, maturity-aware optimization, and structural refactoring, and on Minecraft it unlocks diamond tools in **51 iterations on average vs. 102 for Voyager** while also showing stronger Crafter learning curves. | [Paper](https://arxiv.org/abs/2601.03509) |
| **Reinforcement Learning for Self-Improving Agent with Skill Library**<br>Jiongxiao Wang, Qiaojing Yan, Yawei Wang, Yijun Tian, Soumya Smruti Mishra, Zhichao Xu, Megha Gandhi, Panpan Xu, Lin Lee Cheong | This paper introduces **SAGE**, an RL framework that accumulates reusable skills across sequential rollouts and rewards both task completion and skill use, delivering **+8.9%** Scenario Goal Completion on AppWorld with **26% fewer interaction steps** and **59% fewer tokens**. | [Paper](https://arxiv.org/abs/2512.17102) |
| **CUA-Skill: Develop Skills for Computer Using Agent**<br>Tianyi Chen, Yinheng Li, Michael Solodko, Sen Wang, Nan Jiang, Tingyuan Cui, Junheng Hao, Jongwoo Ko, Sara Abdali, Leon Xu, Suzhen Zheng, Hao Fan, Pashmina Cameron, Justin Wagle, Kazuhito Koishida | CUA-Skill builds a structured skill base for computer-using agents with parameterized execution and composition graphs plus memory-aware recovery, and its CUA-Skill Agent reaches a state-of-the-art **57.5%** best-of-three success rate on WindowsAgentArena. | [Paper](https://arxiv.org/abs/2601.21123) |

---

## Skill-Oriented Reasoning / World Modeling

| Title & Authors | Introduction | Links |
| --- | --- | --- |
| **TARSE: Test-Time Adaptation via Retrieval of Skills and Experience for Reasoning Agents**<br>Junda Wang, Zonghai Tao, Hansi Zeng, Zhichao Yang, Hamed Zamani, Hong Yu | TARSE frames clinical QA as an agent problem with two explicit retrievable resources—**skills** from guideline-like procedures and **experience** from verified reasoning traces—and performs lightweight test-time adaptation on the retrieved items, showing consistent gains over strong medical RAG and prompting-only reasoning baselines. | [Paper](https://arxiv.org/abs/2603.01241) |
| **Self-Improving World Modelling with Latent Actions**<br>Yifu Qiu, Zheng Zhao, Waylon Li, Yftah Ziser, Anna Korhonen, Shay B. Cohen, Edoardo M. Ponti | **SWIRL** learns world models from state-only sequences by alternating forward world modeling and inverse dynamics over latent actions, yielding gains of **16% on AURORABench**, **28% on ByteMorph**, **16% on WorldPredictionBench**, and **14% on StableToolBench**. | [Paper](https://arxiv.org/abs/2602.06130) |
| **When Single-Agent with Skills Replace Multi-Agent Systems and When They Fail**<br>Xiaoxiao Li | This paper studies when a multi-agent system can be “compiled” into a single agent with a skill library, showing competitive reasoning accuracy with lower token usage and latency but also identifying a **phase transition** where skill selection collapses beyond a critical library size. | [Paper](https://arxiv.org/abs/2601.04748) |
| **Agentic Proposing: Enhancing Large Language Model Reasoning via Compositional Skill Synthesis**<br>Zhengbo Jiao, Shaobo Wang, Zifan Zhang, Xuan Ren, Wei Wang, Bing Zhao, Hu Wei, Linfeng Zhang | Agentic Proposing treats data synthesis as a sequential decision process over composable reasoning skills and trains an Agentic-Proposer-4B with MGPO, and a 30B solver trained on only **11K** synthesized trajectories reaches **91.6%** on **AIME 2025**. | [Paper](https://arxiv.org/abs/2602.03279) |

---

## Skill Routing / Orchestration / Ecosystems

| Title & Authors | Introduction | Links |
| --- | --- | --- |
| **SkillOrchestra: Learning to Route Agents via Skill Transfer**<br>Jiayu Wang, Yifei Ming, Zixuan Ke, Shafiq Joty, Aws Albarghouthi, Frederic Sala | SkillOrchestra learns fine-grained skill demands and agent-specific competence/cost instead of directly training an end-to-end router, beating RL-based orchestrators by **up to 22.5%** while cutting learning cost by **700×** vs. Router-R1 and **300×** vs. ToolOrchestra. | [Paper](https://arxiv.org/abs/2602.19672) |
| **SkillNet: Create, Evaluate, and Connect AI Skills**<br>Yuan Liang, Ruobin Zhong, Haoming Xu, Chen Jiang, Yi Zhong, Runnan Fang, Jia-Chen Gu, Shumin Deng, Yunzhi Yao, Mengru Wang, Shuofei Qiao, Xin Xu, Tongtong Wu, Kun Wang, Yang Liu, Zhen Bi, Jungang Lou, Yuchen Eleanor Jiang, Hangcheng Zhu, Gang Yu, Haiwen Hong, Longtao Huang, Hui Xue, Chenxi Wang, Yijun Wang, Zifei Shan, Xi Chen, Zhaopeng Tu, Feiyu Xiong, Xin Xie, Peng Zhang, Zhengke Gui, Lei Liang, Jun Zhou, Chiyu Wu, Jin Shang, Yu Gong, Junyu Lin, Changliang Xu, Hongjie Deng, Wen Zhang, Keyan Ding, Qiang Zhang, Fei Huang, Ningyu Zhang, Jeff Z. Pan, Guilin Qi, Haofen Wang, Huajun Chen | SkillNet introduces an open infrastructure for creating, organizing, and evaluating AI skills with a unified ontology and multi-dimensional quality axes, and its repository spans **200K+ skills** while improving average rewards by **40%** and reducing execution steps by **30%** on ALFWorld, WebShop, and ScienceWorld. | [Paper](https://arxiv.org/abs/2603.04448) |
| **Organizing, Orchestrating, and Benchmarking Agent Skills at Ecosystem Scale**<br>Hao Li, Chunjiang Mu, Jianhao Chen, Siyue Ren, Zhiyao Cui, Yiqun Zhang, Lei Bai, Shuyue Hu | This paper proposes **AgentSkillOS**, which organizes skills into a capability tree and composes them with DAG-based pipelines, showing that tree-based retrieval approximates oracle selection and that DAG orchestration clearly beats native flat invocation from **200 to 200K skills**. | [Paper](https://arxiv.org/abs/2603.02176) |

---

## Skill Benchmarks / Evaluation

| Title & Authors | Introduction | Links |
| --- | --- | --- |
| **SkillsBench: Benchmarking How Well Agent Skills Work Across Diverse Tasks**<br>Xiangyi Li, Wenbo Chen, Yimin Liu, Shenghan Zheng, Xiaokun Chen, Yifeng He, Yubo Li, Bingran You, Haotian Shen, Jiankai Sun, Shuyi Wang, Binxu Li, Qunhong Zeng, Di Wang, Xuandong Zhao, Yuanli Wang, Roey Ben Chaim, Zonglin Di, Yipeng Gao, Junwei He, Yizhuo He, Liqiang Jing, Luyang Kong, Xin Lan, Jiachen Li, Songlin Li, Yijiang Li, Yueqian Lin, Xinyi Liu, Xuanqing Liu, Haoran Lyu, Ze Ma, Bowei Wang, Runhui Wang, Tianyu Wang, Wengao Ye, Yue Zhang, Hanwen Xing, Yiqi Xue, Steven Dillmann, Han-chung Lee | SkillsBench provides **86 tasks across 11 domains** with curated skills and deterministic verifiers, showing that curated skills improve pass rate by **16.2 percentage points on average** whereas self-generated skills provide **no average gain**. | [Paper](https://arxiv.org/abs/2602.12670) |
| **The Tool Decathlon: Benchmarking Language Agents for Diverse, Realistic, and Long-Horizon Task Execution**<br>Junlong Li, Wenshuo Zhao, Jian Zhao, Weihao Zeng, Haoze Wu, Xiaochen Wang, Rui Ge, Yuxuan Cao, Yuzhen Huang, Wei Liu, Junteng Liu, Zhaochen Su, Yiyang Guo, Fan Zhou, Lueyang Zhang, Juan Michelini, Xingyao Wang, Xiang Yue, Shuyan Zhou, Graham Neubig, Junxian He | Toolathlon is a realistic execution benchmark for language agents spanning **32 software applications** and **604 tools**, emphasizing long-horizon, cross-app workflows and diverse initial states instead of a single-domain sandbox. | [Paper](https://arxiv.org/abs/2510.25726) |

---

## Security / Robustness

| Title & Authors | Introduction | Links |
| --- | --- | --- |
| **Agent Skills in the Wild: An Empirical Study of Security Vulnerabilities at Scale**<br>Yi Liu, Weizhe Wang, Ruitao Feng, Yao Zhang, Guangquan Xu, Gelei Deng, Yuekang Li, Leo Zhang | This large-scale empirical study audits agent-skill ecosystems for security flaws and identifies **14 vulnerability patterns** across **42,447 skills**, finding that **26.1%** contain at least one issue while the proposed SkillScan detector reaches **86.7% precision**. | [Paper](https://arxiv.org/abs/2601.10338) |

---

## Survey / Taxonomy / Theory

| Title & Authors | Introduction | Links |
| --- | --- | --- |
| **Agent Skills for Large Language Models: Architecture, Acquisition, Security, and the Path Forward**<br>Renjun Xu, Yang Yan | This survey organizes the agent-skills landscape around architecture, acquisition, evaluation, and security, and its practical value is in turning scattered recent systems such as SAGE, CUA-Skill, and Agentic Proposing into a unified design space for future skill-based agents. | [Paper](https://arxiv.org/abs/2602.12430) |
| **Agent Skill Framework: Perspectives on the Potential of Small Language Models in Industrial Environments**<br>Yangjie Xu, Lujun Li, Lama Sleem, Niccolo Gentile, Yewei Song, Yiqun Wang, Siming Ji, Wenbo Wu, Radu State | This paper formalizes the Agent Skill process and studies whether the paradigm transfers from frontier APIs to industrial **small language models**, finding that tiny models struggle with skill selection, while **12B–30B** SLMs benefit substantially and code-specialized models around **80B** can approach closed-source baselines with better GPU efficiency. | [Paper](https://arxiv.org/abs/2602.16653) |
| **SoK: Agentic Skills -- Beyond Tool Use in LLM Agents**<br>Yanna Jiang, Delong Li, Haiyu Deng, Baihe Ma, Xu Wang, Qin Wang, Guangsheng Yu | This SoK formalizes agentic skills as reusable callable modules and contributes **seven design patterns** plus a **representation × scope** taxonomy, giving a clean conceptual map of the full skill lifecycle from discovery to update. | [Paper](https://arxiv.org/abs/2602.20867) |

---



