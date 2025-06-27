# portfolio-llm

An engineered professional portfolio designed to be reliably queried by an LLM. This project uses a curated context file ([llms_ctx.txt](https://raw.githubusercontent.com/vishalbakshi/portfolio-llm/refs/heads/main/llms_ctx.txt)) and a rigorous evaluation framework to provide an accurate and interactive overview of my skills and experience.

- [Video walkthrough](https://youtu.be/Qhax3JerFP0?feature=shared)
- [Blog post](https://vishalbakshi.github.io/blog/posts/2025-06-26-portfolio-llm/)
- [Twitter](https://x.com/vishal_learner)

## An Interactive Way to Learn About My Work

This portfolio is designed to be interactive. You can have a conversation with it using any modern LLM (like Gemini, Claude, or ChatGPT).

How it Works:

1. Copy my [portfolio llms_ctx.txt](https://raw.githubusercontent.com/vishalbakshi/portfolio-llm/refs/heads/main/llms_ctx.txt)
2. Go to your favorite LLM and paste the following prompt followed by the llms_ctx.txt content:

```
I'm going to give you a block of text that is a professional portfolio for Vishal Bakshi.

After you read it, I will ask you some questions.

Please base all of your answers only on the text I've provided and don't use any of your outside knowledge.

If you can't find an answer in the text, it's important that you say the information is not available.

Here is the text:
```
  
3. Start asking questions! For example: "What kind of role is he best fit for? List out some role names and fit." or "Tell me about his work experience."

## For a Deeper Dive

Below are the core themes that structure my work. Use these to ask more specific questions, such as "Tell me about the AgentFastbook, TinyScaleLab and fastbook-benchmark projects", or "What is his experience with the StanfordNLP/ColBERT library?"

### Theme 1: Building Evaluation Infrastructure & LLM Judges

* [Can an LLM Curate a Dataset? Live-Evaluating Haiku's Text Decomposition](https://youtu.be/NwPKy1rqXT8)
* [TSL: Curating Evaluation Prompts, Defining Scoring Criteria + Designing LLM Judge Prompt Template](https://youtu.be/k5J1S9N_j2g)
* [Building an LLM Judge Agreement App: 7 Iterations from Basic to Full Functionality](https://youtu.be/-a2D9cqXgN4) 
* [Evaluating First Attempt LLM Judge Scores: Improving Claude Haiku Alignment for Story Scoring](https://youtu.be/shIqv520AFY)
* [Look at Your Data: Building an LM Scoring App with FastHTML](https://youtu.be/tcTehUHyrGk) 
* [Manual Scoring Results for TinyStories Models: Grammar, Reasoning, and Emergent Capabilities](https://youtu.be/ZFu8N1Lc3oY)

### Theme 2: The `fastbook-benchmark` Project: Building & Evaluating RAG Systems

* [fastbook-benchmark GitHub repo](https://github.com/vishalbakshi/fastbook-benchmark)
* [Introducing the fastbook-benchmark Information Retrieval QA Dataset](https://youtu.be/VsVIy8k9rMU) 
* [Scoring Full Text and Semantic Search on Chunk Sizes from 100 to 2000 Tokens](https://vishalbakshi.github.io/blog/posts/2024-11-29-fastbook-benchmark-results/)
* [Conducting a Question-by-Question Error Analysis on Full Text Search Results](https://vishalbakshi.github.io/blog/posts/2024-09-05-fastbookRAG-bm25-error-analysis/)
* [Can an LLM Curate a Dataset? Live-Evaluating Haiku's Text Decomposition](https://youtu.be/NwPKy1rqXT8)

### Theme 3: Deconstructing SOTA Libraries (ColBERT, LLM-Foundry, PEFT)

* [RAGatouille/ColBERT Indexing Deep Dive](https://youtu.be/P9KXQ7pbv9s)
* [Recreating the PLAID ColBERTv2 Scoring Pipeline](https://vishalbakshi.github.io/blog/posts/2024-12-24-PLAID-ColBERTv2-scoring-pipeline/)
* [LossInspector: A Deep Dive Into LLM-Foundry's Next-Token Prediction](https://youtu.be/9ffnmeiDF_M)
* [`LoraModel.merge_and_unload` Deep Dive](https://youtu.be/NEosNY_d4zg) 
* [Code Walkthrough - peft DoRA Implementation](https://youtu.be/GE6jRudHhzY)

### Theme 4: The Science of 'Why It's Broken and How it Works': Low-Level Debugging

* [Understanding Sequence Packing: Initial Musings](https://youtu.be/xWnMDL9FDbg) 
* [HuggingFace's Default KV Cache and the `flash_attn_varlen_func` Docstring](https://youtu.be/pZpK5uGr7Lo) 
* [Debugging Un-Merged and Merged LoRA Model Output Differences](https://youtu.be/7fM8FClG66s) 
* [TIL: Using PyTorch's `register_forward_hook` to Trace Floating Point Errors](https://youtu.be/Y6qgWxU3oO4)
* [Understanding Eager Bidirectional Attention via the Attention Mask](https://youtu.be/u_v6HHyv4No)
* [Exploring Precision in ColBERT Indexing and Retrieval](https://youtu.be/aiNQ4I8YaD0)

### Theme 5: Implementation from Scratch

* [Understanding the Mean Shift Clustering Algorithm (and PyTorch Broadcasting)](https://youtu.be/kfl-cUz9iWw)  
* [The Evolution of Matrix Multiplication Part 2](https://youtu.be/iV63qy4ETJQ)
* [Implementing Negative Prompting for Stable Diffusion](https://youtu.be/_nzRTwEb47A)
* [Implementing Image-to-Image Generation for Stable Diffusion](https://youtu.be/POisZHNP23c)
  
### Theme 6: Bridging AI Research & Practice

* [TinyScaleLab: Exploring the Connection Between Training Dynamics and Model Capabilities](https://youtu.be/82mE39Ef5eY) 
* [Research Paper Summary: TinyStories](https://youtu.be/VqgHxKSEspw)
* [Research Paper Summary: Small-scale proxies for large-scale Transformer training instabilities](https://youtu.be/wY774B4JNLM)

### Theme 7: Career Meta-Narrative

* [Finding My Moat in AI: How Boring Tasks, Expert Advice and the AI Evals Course are Shaping My AI Projects](https://youtu.be/GkLAeWOi0r8)
* [Proof, Pricing, and Passion: Finding My Path in Machine Learning](https://youtu.be/9s88C8XBBiQ)

### Theme 8: The Applied Learning Journey

* [BirdCLEF 2024 Recap (0.61 Final LB Score)](https://www.kaggle.com/code/vishalbakshi/birdclef-2024-recap-0-61-final-lb-score) 
* [How Does Stable Diffusion Work?](https://vishalbakshi.github.io/blog/posts/2024-08-08-how-does-stable-diffusion-work/index.html)
* [Takeaways from Gemini's Deep Research Report for Small Batch Training](https://youtu.be/HMOyhKnZ5W0)
