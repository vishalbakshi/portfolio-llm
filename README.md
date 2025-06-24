# portfolio-llm

This is a work in progress. I plan to launch it with a video and blog post by 7/1/2025.

An engineered professional portfolio designed to be reliably queried by an LLM. This project uses a curated context file (llms_ctx.txt) and a rigorous evaluation framework to provide an accurate and interactive overview of my skills and experience.

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
  
3. Start asking questions! For example: "What kind of role is he best fit for? List out some role names and fit."

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

* **Video:** Introducing the fastbook-benchmark Information Retrieval QA Dataset 
* **Blog Post:** Evaluating 4 Retrieval Methods with 6 Chunking Strategies on my `fastbook-benchmark` Dataset 
* **Blog Post:** Conducting a Question-by-Question Error Analysis on Semantic Search Results
* **Video:** Can an LLM Curate a Dataset? Live-Evaluating Haiku's Text Decomposition

### Theme 3: Deconstructing SOTA Libraries (ColBERT, LLM-Foundry, PEFT)

* **Video:** RAGatouille/ColBERT Indexing Deep Dive
* **Video:** Do RAGatouille and ColBERT Produce the Same Index and Retrieval Scores?
* **Video:** LossInspector: A Deep Dive Into LLM-Foundry's Next-Token Prediction 
* **Video:** `LoraModel.merge_and_unload` Deep Dive 
* **Video:** Code Walkthrough - peft DoRA Implementation

### Theme 4: The Science of 'Why It's Broken and How it Works': Low-Level Debugging

* **Video:** Understanding Sequence Packing: Initial Musings 
* **Video:** HuggingFace's Default KV Cache and the `flash_attn_varlen_func` Docstring 
* **Video:** Debugging Un-Merged and Merged LoRA Model Output Differences 
* **Video:** TIL: Using PyTorch's `register_forward_hook` to Trace Floating Point Errors
* **Video:** Understanding Eager Bidirectional Attention via the Attention Mask
* **Blog Post:** Exploring Precision in ColBERT Indexing and Retrieval

### Theme 5: Implementation from Scratch

* **Video:** Understanding the Mean Shift Clustering Algorithm (and PyTorch Broadcasting)  
* **Blog Post:** Implementing a Decision Tree Algorithm from Scratch 
* **Video:** The Evolution of Matrix Multiplication Part 2
* **Blog Post:** Implementing Negative Prompting for Stable Diffusion
* **Blog Post:** Implementing Image-to-Image Generation for Stable Diffusion
  
### Theme 6: Bridging AI Research & Practice

* **Video**: Research Paper Summary: TinyStories
* **Video:** Research Paper Summary: Tulu 3 
* **Video:** Research Paper Summary: Small-scale proxies for large-scale Transformer training instabilities 
* **Video:** Technical Report Summary: Nomic Embed 
* **Blog Post:** Paper Math: DPO (Direct Preference Optimization) 

### Theme 7: Career Meta-Narrative

* **Video:** Finding My Moat: How Boring Tasks, Expert Advice and the AI Evals Course are Shaping My AI Projects 
* **Video:** Proof, Pricing, and Passion: Finding My Path in Machine Learning

### Theme 8: The Applied Learning Journey

* **Blog Post:** Practical Deep Learnings For Coders - Part 1 Notes and Examples
* **Kaggle Notebook:** BirdCLEF 2024 Recap (0.61 Final LB Score) 
* **Blog Post:** How Does Stable Diffusion Work?
* **Blog Post:** An Analysis of Batch Size vs. Learning Rate on Imagenette
* **Blog Post:** Takeaways from Gemini Deep Research Report on Small Batch Training Challenges
