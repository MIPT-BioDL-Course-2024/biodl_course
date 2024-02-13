# biodl_course
A course on biological and medical applications of deep learning.

## Preliminary Plan

WIP

- Block 1. Classic NLP and Transformers
	- **Word2Vec**: Continuous Bag-of-Words and Skip-Gram. TF-IDF
	- Tokenization: BPE. Revisiting transformers: Encoders vs Decoders vs Full Transformers. BERT family, GPTs, T5.
	- Vector Search. Algorithms for fast nearest neighbors search.
- Block 2. Graphs
	- Classical graph methods. Centrality, clustering, DeepWalk, Node2Vec and Matrix decomposition.
	- Graph Neural Networks. **GCN**, GAT. Heterogeneous Graphs, a bit on Knowledge Graphs,RGCN.
	- Proteins. GNN in 3D, equivariance in deep learning. **AlphaFold 2**.
- Block 3. Images
	- Visual transformers. Self-supervision on images. SimCLR, DINO
	- Segment Anything models.
- Block 4. Reinforcement Learning
	- Intro to RL. Markov Decision Processes. Policy and Value. **Q-learning**. DQN.
	- Policy Gradient Methods. REINFORCE. **PPO**
- Block 5. Generative AI
	- LLM Applications. **RAG**, **Agents**, Chain-of-Thoughts and Co.
	- **Diffusion**. Generating images. *Schedules*.
	- Diffusion for chemical compounds, 3D structures (proteins and peptides). *Latent Diffusion Models*

## Homeworks

As homeworks are on the **Kaggle** platform, here is instruction on how to register for a competition (from Russia):

- Log in to your account on [Kaggle](https://www.kaggle.com/) (or create one)
- Open the link to a competition
- Click on the "Join competition" button and accept the rules
- If a phone number is required, do the following (Russian phone numbers are not accepted):
	- Rent a phone number on any suitable service, for example:
		- Register for [onlinesim.io](https://onlinesim.io/)
		- Top up the balance in the left corner (**15.60 RUB is sufficient** - Yes, you have to invest your money to the course... but _Kaggle_ and _onlinesim_ accounts are yours and you can use them in the future)
		- Open [Receive SMS](https://onlinesim.io/v2/numbers/)
		- Find country: **Sweden +46**, find a site: **Kaggle**, rent a phone number by clicking on the price button
		- You have a number on the right side that you need to enter into kaggle to verify your account
		- Now wait for the SMS with the code in the box on the right, update if necessary
- Now you have a Kaggle account! Let's see
- There are different tabs in the competition, the most important: **Overview**, **Data**, **Leaderboard**:
	- **Overview**: competition description
	- **Data**: here you can download train data for training and test data for competition, as well as sample_submission.csv (see below)
	- **Leaderboard**: list of competitors and their scores
- To send a solution click on the **Submit predictions** button on the right and upload a **.csv** file **_the same as sample_submission.csv_**