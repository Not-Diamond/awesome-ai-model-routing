# awesome-ai-model-routing
A curated list of awesome solutions and research in AI model routing. `*` indicates that an entry is open source. Other awesome lists can be found in the [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) list.

- [Awesome AI model routing](#awesome-ai-model-routing)
    - [Intelligent AI model routing](#intelligent-ai-model-routing)
    - [AI model routing papers](#ai-model-routing-papers)
- [Contributing](#contributing)

## Intelligent AI model routing

*Open-source tools and software solutions for AI model routing (ordered alphabetically)*

- [Martian](https://www.withmartian.com/): Dynamically routes requests to the best LLM in real-time.
- [Neutrino AI](https://www.neutrinoapp.com/): Intelligently route queries to the best-suited LLM for the prompt.
- [Not Diamond](https://www.notdiamond.ai/): An AI model router that automatically determines which LLM is best-suited to respond to any query.
- [notdiamond-0001](https://huggingface.co/notdiamond/notdiamond-0001): Automatically determines whether to send queries to GPT-3.5 or GPT-4.
- [Pulze AI KNN router](https://github.com/pulzeai-oss/knn-router): A minimal server for generating a ranked list of targets, for a query, based on its k-nearest semantic neighbors. Written in Go.
- [OpenRouter](https://openrouter.ai/models/openrouter/auto): Prompts will be sent to Llama 3 70B Instruct, Claude 3.5 Sonnet (self-moderated) or GPT-4o.
- [RoRF](https://www.notdiamond.ai/blog/rorf): SOTA open-source pairwise router based on a random forest architecture.
- [RouteLLM](https://github.com/lm-sys/RouteLLM/tree/main): RouteLLM is a framework for serving and evaluating LLM routers.
- [Semantic Router](https://github.com/aurelio-labs/semantic-router): Route inputs to different models using semantic embeddings.
- [Unify](https://unify.ai/): Improve quality, cost and speed by routing to the perfect model and provider for each individual prompt.

## AI model routing papers

*Research papers on AI model routing (ordered by recency)*

- [TensorOpera Router: A Multi-Model Router for Efficient LLM Inference, 2024-10-23](https://arxiv.org/abs/2408.12320): A non-monolithic LLM querying system that seamlessly integrates various LLM experts into a single query interface and dynamically routes incoming queries to the most high-performant expert based on query's requirements.
- [RouteLLM: Learning to Route LLMs with Preference Data, 2024-07-21](https://arxiv.org/abs/2406.18665): A training framework for strong vs weak LLM routers leveraging human preference data and data augmentation.
- [MetaLLM: A High-performant and Cost-efficient Dynamic Framework for Wrapping LLMs, 2024-07-15](https://arxiv.org/abs/2407.10834): Dynamically route each query to the optimal LLM for classification tasks.
- [Merge, Ensemble, and Cooperate! A Survey on Collaborative Strategies in the Era of Large Language Models, 2024-07-08](https://arxiv.org/abs/2407.06089): Comprehensive overview of merging, ensembling, and cooperation in LLMs.
- [AutoMix: Automatically Mixing Language Models, 2024-06-28](https://arxiv.org/abs/2310.12963): Strategically routes queries to larger LMs based on the approximate correctness of outputs from a smaller LM.
- [OptLLM: Optimal Assignment of Queries to Large Language Models, 2023-05-24](https://arxiv.org/abs/2405.15130): Predicts the performance of candidate LLMs on each query using a multi-label classification model with uncertainty estimation.
- [Optimising Calls to Large Language Models with Uncertainty-Based Two-Tier Selection, 2024-05-03](https://arxiv.org/abs/2405.02134): Uses the uncertainty of the generations of a small LLM as the decision criterion for whether to use a strong LLM.
- [Harnessing the Power of Multiple Minds: Lessons Learned from LLM Routing, 2024-05-01](https://arxiv.org/abs/2405.00467): Explores whether it is feasible to direct input queries to the most suitable LLM on reasoning tasks.
- [Hybrid LLM: Cost-Efficient and Quality-Aware Query Routing, 2024-04-22](https://arxiv.org/abs/2404.14618): Uses a router that assigns queries to a small or large model based on the predicted query difficulty and the desired quality level.
- [Predictive Human Preference: From Model Ranking to Model Routing, 2024-02-28](https://huyenchip.com/2024/02/28/predictive-human-preference.html): Predictive human preference aims to predict which model individual users might prefer for a specific query based on their preferences.
- [Routoo: Learning to Route to Large Language Models Effectively, 2024-01-25](https://arxiv.org/abs/2401.13979): Optimize the selection of LLMs for specific prompts based on performance, cost, and efficiency.
- [Fly-Swat or Cannon? Cost-Effective Language Model Choice via Meta-Modeling, 2023-12-18](https://arxiv.org/abs/2308.06077): Assigns each input to an LM predicted to do well on the input according to a so-called meta-model, aiming to achieve high overall performance at low cost.
- [Routing to the Expert: Efficient Reward-guided Ensemble of Large Language Models, 2023-11-15](https://arxiv.org/abs/2311.08692): A reward-guided routing method distilling rewards on training queries to train a routing function, which can precisely route queries to the best LLM.
- [Cache & Distil: Optimising API Calls to Large Language Models, 2023-10-20](https://arxiv.org/abs/2310.13561): A student-teacher framework that includes a policy that learns which requests should be processed by the student alone and which should be redirected to the teacher LLM.
- [EcoAssistant: Using LLM Assistant More Affordably and Accurately, 2023-10-03](https://arxiv.org/abs/2310.03046): Answers code-driven queries by using a hierarchy of LLM assistants, which attempts to answer the query with cheaper LLMs before trying more expensive ones.
- [Large Language Model Routing with Benchmark Datasets, 2023-09-27](https://arxiv.org/abs/2309.15789): Repurposes benchmark datasets to learn a "router" model for LLM selection.
- [Tryage: Real-time, intelligent Routing of User Prompts to Large Language Models, 2023-08-23](https://arxiv.org/abs/2308.11601): Leverages a language model router for optimal selection of expert models from a model library based on analysis of individual input prompts.
- [LLM-Blender: Ensembling Large Language Models with Pairwise Ranking and Generative Fusion, 2023-06-30](https://arxiv.org/abs/2306.02561): An ensembling framework to improve performance by leveraging the diverse strengths of multiple open-source LLMs
- [FrugalGPT: How to Use Large Language Models While Reducing Cost and Improving Performance, 2023-05-09](https://arxiv.org/abs/2305.05176): Proposes an LLM cascade which learns which combinations of LLMs to use for different queries in order to reduce cost and improve accuracy.

# [Contributing](https://github.com/Not-Diamond/awesome-ai-model-routing/blob/main/CONTRIBUTING.md)

Your contributions are always welcome!