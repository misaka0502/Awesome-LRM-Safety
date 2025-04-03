## 📰 Latest arXiv Papers (Auto-Updated)
<!-- LATEST_PAPERS_START -->


| Date       | Title                                      | Authors           | Abstract Summary          |
|------------|--------------------------------------------|-------------------|---------------------------|
| 2025-04-02 | [Slot-Level Robotic Placement via Visual Imitation from Single Human Video](http://arxiv.org/abs/2504.01959v1) | Dandan Shan, Kaichun Mo et al. | The majority of modern robot learning methods focus on learning a set of pre-defined tasks with limited or no generalization to new tasks. Extending the robot skillset to novel tasks involves gathering an extensive amount of training data for additional tasks. In this paper, we address the problem of teaching new tasks to robots using human demonstration videos for repetitive tasks (e.g., packing). This task requires understanding the human video to identify which object is being manipulated (the pick object) and where it is being placed (the placement slot). In addition, it needs to re-identify the pick object and the placement slots during inference along with the relative poses to enable robot execution of the task. To tackle this, we propose SLeRP, a modular system that leverages several advanced visual foundation models and a novel slot-level placement detector Slot-Net, eliminating the need for expensive video demonstrations for training. We evaluate our system using a new benchmark of real-world videos. The evaluation results show that SLeRP outperforms several baselines and can be deployed on a real robot. |
| 2025-04-02 | [OpenCodeReasoning: Advancing Data Distillation for Competitive Coding](http://arxiv.org/abs/2504.01943v1) | Wasi Uddin Ahmad, Sean Narenthiran et al. | Since the advent of reasoning-based large language models, many have found great success from distilling reasoning capabilities into student models. Such techniques have significantly bridged the gap between reasoning and standard LLMs on coding tasks. Despite this, much of the progress on distilling reasoning models remains locked behind proprietary datasets or lacks details on data curation, filtering and subsequent training. To address this, we construct a superior supervised fine-tuning (SFT) dataset that we use to achieve state-of-the-art coding capability results in models of various sizes. Our distilled models use only SFT to achieve 61.8% on LiveCodeBench and 24.6% on CodeContests, surpassing alternatives trained with reinforcement learning. We then perform analysis on the data sources used to construct our dataset, the impact of code execution filtering, and the importance of instruction/solution diversity. We observe that execution filtering negatively affected benchmark accuracy, leading us to prioritize instruction diversity over solution correctness. Finally, we also analyze the token efficiency and reasoning patterns utilized by these models. We will open-source these datasets and distilled models to the community. |
| 2025-04-02 | [End-to-End Driving with Online Trajectory Evaluation via BEV World Model](http://arxiv.org/abs/2504.01941v1) | Yingyan Li, Yuqi Wang et al. | End-to-end autonomous driving has achieved remarkable progress by integrating perception, prediction, and planning into a fully differentiable framework. Yet, to fully realize its potential, an effective online trajectory evaluation is indispensable to ensure safety. By forecasting the future outcomes of a given trajectory, trajectory evaluation becomes much more effective. This goal can be achieved by employing a world model to capture environmental dynamics and predict future states. Therefore, we propose an end-to-end driving framework WoTE, which leverages a BEV World model to predict future BEV states for Trajectory Evaluation. The proposed BEV world model is latency-efficient compared to image-level world models and can be seamlessly supervised using off-the-shelf BEV-space traffic simulators. We validate our framework on both the NAVSIM benchmark and the closed-loop Bench2Drive benchmark based on the CARLA simulator, achieving state-of-the-art performance. Code is released at https://github.com/liyingyanUCAS/WoTE. |
| 2025-04-02 | [Strengthening Multi-Robot Systems for SAR: Co-Designing Robotics and Communication Towards 6G](http://arxiv.org/abs/2504.01940v1) | Juan Bravo-Arrabal, Ricardo Vázquez-Martín et al. | This paper presents field-tested use cases from Search and Rescue (SAR) missions, highlighting the co-design of mobile robots and communication systems to support Edge-Cloud architectures based on 5G Standalone (SA). The main goal is to contribute to the effective cooperation of multiple robots and first responders. Our field experience includes the development of Hybrid Wireless Sensor Networks (H-WSNs) for risk and victim detection, smartphones integrated into the Robot Operating System (ROS) as Edge devices for mission requests and path planning, real-time Simultaneous Localization and Mapping (SLAM) via Multi-Access Edge Computing (MEC), and implementation of Uncrewed Ground Vehicles (UGVs) for victim evacuation in different navigation modes. These experiments, conducted in collaboration with actual first responders, underscore the need for intelligent network resource management, balancing low-latency and high-bandwidth demands. Network slicing is key to ensuring critical emergency services are performed despite challenging communication conditions. The paper identifies architectural needs, lessons learned, and challenges to be addressed by 6G technologies to enhance emergency response capabilities. |
| 2025-04-02 | [Overcoming Deceptiveness in Fitness Optimization with Unsupervised Quality-Diversity](http://arxiv.org/abs/2504.01915v1) | Lisa Coiffard, Paul Templier et al. | Policy optimization seeks the best solution to a control problem according to an objective or fitness function, serving as a fundamental field of engineering and research with applications in robotics. Traditional optimization methods like reinforcement learning and evolutionary algorithms struggle with deceptive fitness landscapes, where following immediate improvements leads to suboptimal solutions. Quality-diversity (QD) algorithms offer a promising approach by maintaining diverse intermediate solutions as stepping stones for escaping local optima. However, QD algorithms require domain expertise to define hand-crafted features, limiting their applicability where characterizing solution diversity remains unclear. In this paper, we show that unsupervised QD algorithms - specifically the AURORA framework, which learns features from sensory data - efficiently solve deceptive optimization problems without domain expertise. By enhancing AURORA with contrastive learning and periodic extinction events, we propose AURORA-XCon, which outperforms all traditional optimization baselines and matches, in some cases even improving by up to 34%, the best QD baseline with domain-specific hand-crafted features. This work establishes a novel application of unsupervised QD algorithms, shifting their focus from discovering novel solutions toward traditional optimization and expanding their potential to domains where defining feature spaces poses challenges. |
| 2025-03-31 | [SU-YOLO: Spiking Neural Network for Efficient Underwater Object Detection](http://arxiv.org/abs/2503.24389v1) | Chenyang Li, Wenxuan Liu et al. | Underwater object detection is critical for oceanic research and industrial safety inspections. However, the complex optical environment and the limited resources of underwater equipment pose significant challenges to achieving high accuracy and low power consumption. To address these issues, we propose Spiking Underwater YOLO (SU-YOLO), a Spiking Neural Network (SNN) model. Leveraging the lightweight and energy-efficient properties of SNNs, SU-YOLO incorporates a novel spike-based underwater image denoising method based solely on integer addition, which enhances the quality of feature maps with minimal computational overhead. In addition, we introduce Separated Batch Normalization (SeBN), a technique that normalizes feature maps independently across multiple time steps and is optimized for integration with residual structures to capture the temporal dynamics of SNNs more effectively. The redesigned spiking residual blocks integrate the Cross Stage Partial Network (CSPNet) with the YOLO architecture to mitigate spike degradation and enhance the model's feature extraction capabilities. Experimental results on URPC2019 underwater dataset demonstrate that SU-YOLO achieves mAP of 78.8% with 6.97M parameters and an energy consumption of 2.98 mJ, surpassing mainstream SNN models in both detection accuracy and computational efficiency. These results underscore the potential of SNNs for engineering applications. The code is available in https://github.com/lwxfight/snn-underwater. |
| 2025-03-31 | [UniOcc: A Unified Benchmark for Occupancy Forecasting and Prediction in Autonomous Driving](http://arxiv.org/abs/2503.24381v1) | Yuping Wang, Xiangyu Huang et al. | We introduce UniOcc, a comprehensive, unified benchmark for occupancy forecasting (i.e., predicting future occupancies based on historical information) and current-frame occupancy prediction from camera images. UniOcc unifies data from multiple real-world datasets (i.e., nuScenes, Waymo) and high-fidelity driving simulators (i.e., CARLA, OpenCOOD), which provides 2D/3D occupancy labels with per-voxel flow annotations and support for cooperative autonomous driving. In terms of evaluation, unlike existing studies that rely on suboptimal pseudo labels for evaluation, UniOcc incorporates novel metrics that do not depend on ground-truth occupancy, enabling robust assessment of additional aspects of occupancy quality. Through extensive experiments on state-of-the-art models, we demonstrate that large-scale, diverse training data and explicit flow information significantly enhance occupancy prediction and forecasting performance. |
| 2025-03-31 | [Exploring the Effect of Reinforcement Learning on Video Understanding: Insights from SEED-Bench-R1](http://arxiv.org/abs/2503.24376v1) | Yi Chen, Yuying Ge et al. | Recent advancements in Chain of Thought (COT) generation have significantly improved the reasoning capabilities of Large Language Models (LLMs), with reinforcement learning (RL) emerging as an effective post-training approach. Multimodal Large Language Models (MLLMs) inherit this reasoning potential but remain underexplored in tasks requiring both perception and logical reasoning. To address this, we introduce SEED-Bench-R1, a benchmark designed to systematically evaluate post-training methods for MLLMs in video understanding. It includes intricate real-world videos and complex everyday planning tasks in the format of multiple-choice questions, requiring sophisticated perception and reasoning. SEED-Bench-R1 assesses generalization through a three-level hierarchy: in-distribution, cross-environment, and cross-environment-task scenarios, equipped with a large-scale training dataset with easily verifiable ground-truth answers. Using Qwen2-VL-Instruct-7B as a base model, we compare RL with supervised fine-tuning (SFT), demonstrating RL's data efficiency and superior performance on both in-distribution and out-of-distribution tasks, even outperforming SFT on general video understanding benchmarks like LongVideoBench. Our detailed analysis reveals that RL enhances visual perception but often produces less logically coherent reasoning chains. We identify key limitations such as inconsistent reasoning and overlooked visual cues, and suggest future improvements in base model reasoning, reward modeling, and RL robustness against noisy signals. |
| 2025-03-31 | [Effectively Controlling Reasoning Models through Thinking Intervention](http://arxiv.org/abs/2503.24370v1) | Tong Wu, Chong Xiang et al. | Reasoning-enhanced large language models (LLMs) explicitly generate intermediate reasoning steps prior to generating final answers, helping the model excel in complex problem-solving. In this paper, we demonstrate that this emerging generation framework offers a unique opportunity for more fine-grained control over model behavior. We propose Thinking Intervention, a novel paradigm designed to explicitly guide the internal reasoning processes of LLMs by strategically inserting or revising specific thinking tokens. We conduct comprehensive evaluations across multiple tasks, including instruction following on IFEval, instruction hierarchy on SEP, and safety alignment on XSTest and SORRY-Bench. Our results demonstrate that Thinking Intervention significantly outperforms baseline prompting approaches, achieving up to 6.7% accuracy gains in instruction-following scenarios, 15.4% improvements in reasoning about instruction hierarchies, and a 40.0% increase in refusal rates for unsafe prompts using open-source DeepSeek R1 models. Overall, our work opens a promising new research avenue for controlling reasoning LLMs. |
| 2025-03-31 | [Sim-and-Real Co-Training: A Simple Recipe for Vision-Based Robotic Manipulation](http://arxiv.org/abs/2503.24361v1) | Abhiram Maddukuri, Zhenyu Jiang et al. | Large real-world robot datasets hold great potential to train generalist robot models, but scaling real-world human data collection is time-consuming and resource-intensive. Simulation has great potential in supplementing large-scale data, especially with recent advances in generative AI and automated data generation tools that enable scalable creation of robot behavior datasets. However, training a policy solely in simulation and transferring it to the real world often demands substantial human effort to bridge the reality gap. A compelling alternative is to co-train the policy on a mixture of simulation and real-world datasets. Preliminary studies have recently shown this strategy to substantially improve the performance of a policy over one trained on a limited amount of real-world data. Nonetheless, the community lacks a systematic understanding of sim-and-real co-training and what it takes to reap the benefits of simulation data for real-robot learning. This work presents a simple yet effective recipe for utilizing simulation data to solve vision-based robotic manipulation tasks. We derive this recipe from comprehensive experiments that validate the co-training strategy on various simulation and real-world datasets. Using two domains--a robot arm and a humanoid--across diverse tasks, we demonstrate that simulation data can enhance real-world task performance by an average of 38%, even with notable differences between the simulation and real-world data. Videos and additional results can be found at https://co-training.github.io/ |
| 2025-03-31 | [Sim-and-Real Co-Training: A Simple Recipe for Vision-Based Robotic Manipulation](http://arxiv.org/abs/2503.24361v2) | Abhiram Maddukuri, Zhenyu Jiang et al. | Large real-world robot datasets hold great potential to train generalist robot models, but scaling real-world human data collection is time-consuming and resource-intensive. Simulation has great potential in supplementing large-scale data, especially with recent advances in generative AI and automated data generation tools that enable scalable creation of robot behavior datasets. However, training a policy solely in simulation and transferring it to the real world often demands substantial human effort to bridge the reality gap. A compelling alternative is to co-train the policy on a mixture of simulation and real-world datasets. Preliminary studies have recently shown this strategy to substantially improve the performance of a policy over one trained on a limited amount of real-world data. Nonetheless, the community lacks a systematic understanding of sim-and-real co-training and what it takes to reap the benefits of simulation data for real-robot learning. This work presents a simple yet effective recipe for utilizing simulation data to solve vision-based robotic manipulation tasks. We derive this recipe from comprehensive experiments that validate the co-training strategy on various simulation and real-world datasets. Using two domains--a robot arm and a humanoid--across diverse tasks, we demonstrate that simulation data can enhance real-world task performance by an average of 38%, even with notable differences between the simulation and real-world data. Videos and additional results can be found at https://co-training.github.io/ |
| 2025-03-28 | [Q-Insight: Understanding Image Quality via Visual Reinforcement Learning](http://arxiv.org/abs/2503.22679v1) | Weiqi Li, Xuanyu Zhang et al. | Image quality assessment (IQA) focuses on the perceptual visual quality of images, playing a crucial role in downstream tasks such as image reconstruction, compression, and generation. The rapid advancement of multi-modal large language models (MLLMs) has significantly broadened the scope of IQA, moving toward comprehensive image quality understanding that incorporates content analysis, degradation perception, and comparison reasoning beyond mere numerical scoring. Previous MLLM-based methods typically either generate numerical scores lacking interpretability or heavily rely on supervised fine-tuning (SFT) using large-scale annotated datasets to provide descriptive assessments, limiting their flexibility and applicability. In this paper, we propose Q-Insight, a reinforcement learning-based model built upon group relative policy optimization (GRPO), which demonstrates strong visual reasoning capability for image quality understanding while requiring only a limited amount of rating scores and degradation labels. By jointly optimizing score regression and degradation perception tasks with carefully designed reward functions, our approach effectively exploits their mutual benefits for enhanced performance. Extensive experiments demonstrate that Q-Insight substantially outperforms existing state-of-the-art methods in both score regression and degradation perception tasks, while exhibiting impressive zero-shot generalization to comparison reasoning tasks. Code will be available at https://github.com/lwq20020127/Q-Insight. |
| 2025-03-28 | [Verifying Nonlinear Neural Feedback Systems using Polyhedral Enclosures](http://arxiv.org/abs/2503.22660v1) | Samuel I. Akinwande, Chelsea Sidrane et al. | As dynamical systems equipped with neural network controllers (neural feedback systems) become increasingly prevalent, it is critical to develop methods to ensure their safe operation. Verifying safety requires extending control theoretic analysis methods to these systems. Although existing techniques can efficiently handle linear neural feedback systems, relatively few scalable methods address the nonlinear case. We propose a novel algorithm for forward reachability analysis of nonlinear neural feedback systems. The approach leverages the structure of the nonlinear transition functions of the systems to compute tight polyhedral enclosures (i.e., abstractions). These enclosures, combined with the neural controller, are then encoded as a mixed-integer linear program (MILP). Optimizing this MILP yields a sound over-approximation of the forward-reachable set. We evaluate our algorithm on representative benchmarks and demonstrate an order of magnitude improvement over the current state of the art. |
| 2025-03-28 | [Finding Unknown Unknowns using Cyber-Physical System Simulators (Extended Report)](http://arxiv.org/abs/2503.22646v1) | Semaan Douglas Wehbe, Stanley Bak | Simulation-based approaches are among the most practical means to search for safety violations, bugs, and other unexpected events in cyber-physical systems (CPS). Where existing approaches search for simulations violating a formal specification or maximizing a notion of coverage, in this work we propose a new goal for testing: to discover unknown rare behaviors by examining discrete mode sequences. We assume a CPS simulator outputs mode information, and strive to explore the sequences of modes produced by varying the initial state or time-varying uncertainties. We hypothesize that rare mode sequences are often the most interesting to a designer, and we develop two accelerated sampling algorithms that speed up the process of finding such sequences. We evaluate our approach on several benchmarks, ranging from synthetic examples to Simulink diagrams of a CPS, demonstrating in some cases a speedup of over 100x compared with a random sampling strategy. |
| 2025-03-28 | [Empirical Analysis of Sim-and-Real Cotraining Of Diffusion Policies For Planar Pushing from Pixels](http://arxiv.org/abs/2503.22634v1) | Adam Wei, Abhinav Agarwal et al. | In imitation learning for robotics, cotraining with demonstration data generated both in simulation and on real hardware has emerged as a powerful recipe to overcome the sim2real gap. This work seeks to elucidate basic principles of this sim-and-real cotraining to help inform simulation design, sim-and-real dataset creation, and policy training. Focusing narrowly on the canonical task of planar pushing from camera inputs enabled us to be thorough in our study. These experiments confirm that cotraining with simulated data \emph{can} dramatically improve performance in real, especially when real data is limited. Performance gains scale with simulated data, but eventually plateau; real-world data increases this performance ceiling. The results also suggest that reducing the domain gap in physics may be more important than visual fidelity for non-prehensile manipulation tasks. Perhaps surprisingly, having some visual domain gap actually helps the cotrained policy -- binary probes reveal that high-performing policies learn to distinguish simulated domains from real. We conclude by investigating this nuance and mechanisms that facilitate positive transfer between sim-and-real. In total, our experiments span over 40 real-world policies (evaluated on 800+ trials) and 200 simulated policies (evaluated on 40,000+ trials). |
| 2025-03-28 | [Reinforcement Learning for Machine Learning Model Deployment: Evaluating Multi-Armed Bandits in ML Ops Environments](http://arxiv.org/abs/2503.22595v1) | S. Aaron McClendon, Vishaal Venkatesh et al. | In modern ML Ops environments, model deployment is a critical process that traditionally relies on static heuristics such as validation error comparisons and A/B testing. However, these methods require human intervention to adapt to real-world deployment challenges, such as model drift or unexpected performance degradation. We investigate whether reinforcement learning, specifically multi-armed bandit (MAB) algorithms, can dynamically manage model deployment decisions more effectively. Our approach enables more adaptive production environments by continuously evaluating deployed models and rolling back underperforming ones in real-time. We test six model selection strategies across two real-world datasets and find that RL based approaches match or exceed traditional methods in performance. Our findings suggest that reinforcement learning (RL)-based model management can improve automation, reduce reliance on manual interventions, and mitigate risks associated with post-deployment model failures. |
| 2025-03-27 | [HS-SLAM: Hybrid Representation with Structural Supervision for Improved Dense SLAM](http://arxiv.org/abs/2503.21778v1) | Ziren Gong, Fabio Tosi et al. | NeRF-based SLAM has recently achieved promising results in tracking and reconstruction. However, existing methods face challenges in providing sufficient scene representation, capturing structural information, and maintaining global consistency in scenes emerging significant movement or being forgotten. To this end, we present HS-SLAM to tackle these problems. To enhance scene representation capacity, we propose a hybrid encoding network that combines the complementary strengths of hash-grid, tri-planes, and one-blob, improving the completeness and smoothness of reconstruction. Additionally, we introduce structural supervision by sampling patches of non-local pixels rather than individual rays to better capture the scene structure. To ensure global consistency, we implement an active global bundle adjustment (BA) to eliminate camera drifts and mitigate accumulative errors. Experimental results demonstrate that HS-SLAM outperforms the baselines in tracking and reconstruction accuracy while maintaining the efficiency required for robotics. |
| 2025-03-27 | [Video-R1: Reinforcing Video Reasoning in MLLMs](http://arxiv.org/abs/2503.21776v1) | Kaituo Feng, Kaixiong Gong et al. | Inspired by DeepSeek-R1's success in eliciting reasoning abilities through rule-based reinforcement learning (RL), we introduce Video-R1 as the first attempt to systematically explore the R1 paradigm for eliciting video reasoning within multimodal large language models (MLLMs). However, directly applying RL training with the GRPO algorithm to video reasoning presents two primary challenges: (i) a lack of temporal modeling for video reasoning, and (ii) the scarcity of high-quality video-reasoning data. To address these issues, we first propose the T-GRPO algorithm, which encourages models to utilize temporal information in videos for reasoning. Additionally, instead of relying solely on video data, we incorporate high-quality image-reasoning data into the training process. We have constructed two datasets: Video-R1-COT-165k for SFT cold start and Video-R1-260k for RL training, both comprising image and video data. Experimental results demonstrate that Video-R1 achieves significant improvements on video reasoning benchmarks such as VideoMMMU and VSI-Bench, as well as on general video benchmarks including MVBench and TempCompass, etc. Notably, Video-R1-7B attains a 35.8% accuracy on video spatial reasoning benchmark VSI-bench, surpassing the commercial proprietary model GPT-4o. All codes, models, data are released. |
| 2025-03-27 | [Optical control of orbital magnetism in magic angle twisted bilayer graphene](http://arxiv.org/abs/2503.21750v1) | Eylon Persky, Minhao He et al. | Flat bands in graphene-based moir\'e structures host a wide range of emerging strongly correlated and topological phenomena. Optically probing and controlling them can reveal important information such as symmetry and dynamics, but have so far been challenging due to the small energy gap compared to optical wavelengths. Here, we report near infrared optical control of orbital magnetism and associated anomalous Hall effects (AHE) in a magic angle twisted bilayer graphene (MATBG) on monolayer WSe$_2$ device. We show that the properties of the AHE, such as hysteresis and amplitude, can be controlled by light near integer moir\'e fillings, where spontaneous ferromagnetism exists. By modulating the light helicity, we observe periodic modulation of the transverse resistance in a wide range of fillings, indicating light induced orbital magnetization through a large inverse Faraday effect. At the transition between metallic and AHE regimes, we also reveal large and random switching of the Hall resistivity, which are attributed to optical control of percolating cluster of magnetic domains. Our results open the door to optical manipulation of correlation and topology in MATBG and related structures. |
| 2025-03-27 | [GateLens: A Reasoning-Enhanced LLM Agent for Automotive Software Release Analytics](http://arxiv.org/abs/2503.21735v1) | Arsham Gholamzadeh Khoee, Shuai Wang et al. | Ensuring the reliability and effectiveness of software release decisions is critical, particularly in safety-critical domains like automotive systems. Precise analysis of release validation data, often presented in tabular form, plays a pivotal role in this process. However, traditional methods that rely on manual analysis of extensive test datasets and validation metrics are prone to delays and high costs. Large Language Models (LLMs) offer a promising alternative but face challenges in analytical reasoning, contextual understanding, handling out-of-scope queries, and processing structured test data consistently; limitations that hinder their direct application in safety-critical scenarios. This paper introduces GateLens, an LLM-based tool for analyzing tabular data in the automotive domain. GateLens translates natural language queries into Relational Algebra (RA) expressions and then generates optimized Python code. It outperforms the baseline system on benchmarking datasets, achieving higher F1 scores and handling complex and ambiguous queries with greater robustness. Ablation studies confirm the critical role of the RA module, with performance dropping sharply when omitted. Industrial evaluations reveal that GateLens reduces analysis time by over 80% while maintaining high accuracy and reliability. As demonstrated by presented results, GateLens achieved high performance without relying on few-shot examples, showcasing strong generalization across various query types from diverse company roles. Insights from deploying GateLens with a partner automotive company offer practical guidance for integrating AI into critical workflows such as release validation. Results show that by automating test result analysis, GateLens enables faster, more informed, and dependable release decisions, and can thus advance software scalability and reliability in automotive systems. |

<!-- LATEST_PAPERS_END -->


<!-- HISTORICAL_PAPERS_START -->

<details>
<summary>📚 View Historical Papers (1 entries)</summary>



| Date       | Title                                      | Authors           | Abstract Summary          |
|------------|--------------------------------------------|-------------------|---------------------------|
| 2025-03-27 | [ReaRAG: Knowledge-guided Reasoning Enhances Factuality of Large Reasoning Models with Iterative Retrieval Augmented Generation](http://arxiv.org/abs/2503.21729v1) | Zhicheng Lee, Shulin Cao et al. | Large Reasoning Models (LRMs) exhibit remarkable reasoning abilities but rely primarily on parametric knowledge, limiting factual accuracy. While recent works equip reinforcement learning (RL)-based LRMs with retrieval capabilities, they suffer from overthinking and lack robustness in reasoning, reducing their effectiveness in question answering (QA) tasks. To address this, we propose ReaRAG, a factuality-enhanced reasoning model that explores diverse queries without excessive iterations. Our solution includes a novel data construction framework with an upper bound on the reasoning chain length. Specifically, we first leverage an LRM to generate deliberate thinking, then select an action from a predefined action space (Search and Finish). For Search action, a query is executed against the RAG engine, where the result is returned as observation to guide reasoning steps later. This process iterates until a Finish action is chosen. Benefiting from ReaRAG's strong reasoning capabilities, our approach outperforms existing baselines on multi-hop QA. Further analysis highlights its strong reflective ability to recognize errors and refine its reasoning trajectory. Our study enhances LRMs' factuality while effectively integrating robust reasoning for Retrieval-Augmented Generation (RAG). |

</details>

<!-- HISTORICAL_PAPERS_END -->
---

