# VIALM
This repository offers a survey and benchmark for Visual Impairment Assistance using Large Models (VIALM).
## 1. Task Illustration
The following figure illustrates a sample input and output of VIALM.
The input is a pair of a visual display of the environment (the image on the left) and a user request in human language (the grey box).
The yellow box shows the output guidance for VI users to complete the request within the environment (the image on the right).
The output should be grounded and fine-grained for VI users to follow easily.
![VIALM](./images/VIALM_task.png 'VIALM_task')
## 2. Paper Collections
For the survey part, we have collected a list of related papers, which will be continually updated. The image below summarizes the timeline of the papers.
![Timeline](./images/timeline.png 'LM Timeline')
### 2.1 Large Language models (LLMs)
* Tom B. Brown, Benjamin Mann, and et al. Language models are few-shot learners. In NeurIPS, 2020.
* Nan Du, Yanping Huang, and et al. GLaM: Efficient scaling of language models with mixture-of-experts. In ICML,2022.
* Jack W. Rae, Sebastian Borgeaud, and et al. Scaling language models: Methods, analysis & insights from training gopher. arXiv, 2112.11446, 2021.
* Romal Thoppilan, Daniel De Freitas, and et al. LaMDA: Language models for dialog applications. arXiv, 2201.08239, 2022.
* Aakanksha Chowdhery, Sharan Narang, and et al. PaLM: Scaling language modeling with pathways. J. Mach. Learn. Res., 2023.
* Jordan Hoffmann, Sebastian Borgeaud, and et al. Training compute-optimal large language models. arXiv, 2203.15556, 2022.
* Susan Zhang, Stephen Roller, and et al. OPT: open pre-trained transformer language models. arXiv, 2205.01068, 2022.
* Aohan Zeng, Xiao Liu, and et al. GLM-130B: an open bilingual pre-trained model. In ICLR, 2023.
* Teven Le Scao, Angela Fan, and et al. BLOOM: A 176b-parameter open-access multilingual language model. arXiv, 2211.05100, 2022.
* Ross Taylor, Marcin Kardas, and et al. Galactica: A large language model for science. arXiv, 2211.09085, 2022.
* Hugo Touvron, Thibaut Lavril, and et al. LLaMA: Open and efficient foundation language models. arXiv, 2302.13971, 2023.
* Bo Peng, Eric Alcaide, and et al. RWKV: Reinventing rnns for the transformer era. In EMNLP (Findings), 2023.
* Rohan Anil, Andrew M. Dai, and et al. PaLM 2 technical report. arXiv, 2305.10403, 2023.
* Hugo Touvron, Louis Martin, and et al. Llama 2: Open foundation and fine-tuned chat models. arXiv, 2307.09288, 2023.
* Ebtesam Almazrouei, Hamza Alobeidli, and et al. The falcon series of open language models. arXiv, 2311.16867, 2023

### 2.2 Visual-Language Models (VLMs)
* Wenhai Wang, Zhe Chen, and et al. VisionLLM: Large language model is also an open-ended decoder for vision-centric tasks. arXiv, 2305.11175, 2023.
* Wenbo Hu, Yifan Xu, and et al. BLIVA: A simple multimodal LLM for better handling of text-rich visual questions. arXiv, 2308.09936, 2023.
* Srinivasan Iyer, Xi Victoria Lin, and et al. OPT-IML: scaling language model instruction meta learning through the lens of generalization. arXiv, 2212.12017, 2022.
* Junnan Li, Dongxu Li, and et al. BLIP-2: bootstrapping language-image pre-training with frozen image encoders and large language models. In ICML, 2023.
* Haotian Liu, Chunyuan Li, and et al. Improved baselines with visual instruction tuning. arXiv, 2310.03744, 2023.
* Haotian Liu, Chunyuan Li, and et al. Visual instruction tuning. arXiv, 2304.08485, 2023.
* James Manyika. An overview of bard: an early experiment with generative ai. AI. Google Static Documents, 2023.
* Weihan Wang, Qingsong Lv, and et al. CogVLM: Visual expert for pretrained language models. arXiv, 2311.03079, 2023.






### 2.3 Embodied Agents
* * Jacky Liang, Wenlong Huang, and et al. Code as Policies:Language model programs for embodied control. In ICRA, 2023.
* Danny Driess, Fei Xia, and et al. PaLM-E: An embodied multimodal language model. In ICML, 2023.
* Guanzhi Wang, Yuqi Xie, and et al. Voyager: An open-ended embodied agent with large language models. arXiv, 2305.16291, 2023.
* Wenlong Huang, Fei Xia, and et al. Inner monologue: Embodied reasoning through planning with language models. In CoRL, 2022.
* Wenlong Huang, Fei Xia, and et al. Grounded decoding: Guiding text generation with grounded models for robot control. arXiv, 2303.00855, 2023.
* Brian Ichter, nthony Brohan, and et al. Do as I can, not as I say: Grounding language in robotic affordances. In CoRL, 2022.
* Ishika Singh, Valts Blukis, and et al. ProgPrompt: Generating situated robot task plans using large language models. In ICRA, 2023.
* Chan Hee Song, Jiaman Wu, and et al. Llm-planner: Few-shot grounded planning for embodied agents with large language models. arXiv, 2212.04088, 2022.
## 3. Benchmark Evaluation
Our benchmark consists of two common daily life environment, domestic home and supermarket. 

Example:
![Benchmark](./images/benchmark_example.png 'Benchmark annotations')

### 3.1 Benchmark Annotations
The annotated evaluation dataset can be found at ./benchmark/annotations .
The input environment images can be found at ./benchmark/environment_images .

### 3.2 LM Predictions
The predictions made by the six large models (LMs) can be found at ./benchmark/lm_predictions .

A list of large models used:
* GPT-4
* CogVLM
* MiniGPT
* Qwen-VL
* LLaVA
* BLIVA
