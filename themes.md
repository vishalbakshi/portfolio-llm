## Background

This is the first step I took. I fed Gemini 2.5 Pro metadata (titles and descriptions) of my 61 videos and 134 blog posts and asked it to 1) come up with themes and 2) identify "gold content pieces" for each theme. I slightly modified its response. The next step will be to add links and add a handwritten summary for each gold content piece.

## Theme 1: Building Evaluation Infrastructure & LLM Judges

* **Video:** TSL: Curating Evaluation Prompts, Defining Scoring Criteria + Designing LLM Judge Prompt Template 
* **Video:** Building an LLM Judge Agreement App: 7 Iterations from Basic to Full Functionality 
* **Video:** Evaluating First Attempt LLM Judge Scores: Improving Claude Haiku Alignment for Story Scoring 
* **Video:** Look at Your Data: Building an LM Scoring App with FastHTML 
* **Video:** Manual Scoring Results for TinyStories Models: Grammar, Reasoning, and Emergent Capabilities
* **Video:** Can an LLM Curate a Dataset? Live-Evaluating Haiku's Text Decomposition

## Theme 2: The `fastbook-benchmark` Project: Building & Evaluating RAG Systems

* **Video:** Introducing the fastbook-benchmark Information Retrieval QA Dataset 
* **Blog Post:** Evaluating 4 Retrieval Methods with 6 Chunking Strategies on my `fastbook-benchmark` Dataset 
* **Blog Post:** Conducting a Question-by-Question Error Analysis on Semantic Search Results
* **Video:** Can an LLM Curate a Dataset? Live-Evaluating Haiku's Text Decomposition

## Theme 3: Deconstructing SOTA Libraries (ColBERT, LLM-Foundry, PEFT)

* **Video:** RAGatouille/ColBERT Indexing Deep Dive
* **Video:** Do RAGatouille and ColBERT Produce the Same Index and Retrieval Scores?
* **Video:** Understanding ColBERT's ivf.pid.pt: Inspecting Intermediate Artifacts 
* **Video:** LossInspector: A Deep Dive Into LLM-Foundry's Next-Token Prediction 
* **Video:** `LoraModel.merge_and_unload` Deep Dive 
* **Video:** Code Walkthrough - peft DoRA Implementation

## Theme 4: The Science of 'Why It's Broken and How it Works': Low-Level Debugging

* **Video:** Understanding Sequence Packing: Initial Musings 
* **Video:** HuggingFace's Default KV Cache and the `flash_attn_varlen_func` Docstring 
* **Video:** Debugging Un-Merged and Merged LoRA Model Output Differences 
* **Video:** TIL: Using PyTorch's `register_forward_hook` to Trace Floating Point Errors
* **Video:** Understanding Eager Bidirectional Attention via the Attention Mask
* **Blog Post:** Exploring Precision in ColBERT Indexing and Retrieval

## Theme 5: Implementation from Scratch

* **Video:** Understanding the Mean Shift Clustering Algorithm (and PyTorch Broadcasting)  
* **Blog Post:** Implementing a Decision Tree Algorithm from Scratch 
* **Video:** The Evolution of Matrix Multiplication Part 2
* **Blog Post:** Implementing Negative Prompting for Stable Diffusion
* **Blog Post:** Implementing Image-to-Image Generation for Stable Diffusion
  
## Theme 6: Bridging AI Research & Practice

* **Video**: Research Paper Summary: TinyStories
* **Video:** Research Paper Summary: Tulu 3 
* **Video:** Research Paper Summary: Small-scale proxies for large-scale Transformer training instabilities 
* **Video:** Technical Report Summary: Nomic Embed 
* **Blog Post:** Paper Math: DPO (Direct Preference Optimization) 

## Theme 7: Career Meta-Narrative

* **Video:** Finding My Moat: How Boring Tasks, Expert Advice and the AI Evals Course are Shaping My AI Projects 
* **Video:** Proof, Pricing, and Passion: Finding My Path in Machine Learning
* **Video:** Can an LLM Curate a Dataset? Live-Evaluating Haiku's Text Decomposition
* **Video description:** "I'm a data analyst transitioning into machine learning research, I'm passionate about tiny models, resource constrained research and deeply understanding how things work." 
* **Video description:** "I believe using tiny models as proxies to study phenomena relevant to models of all sizes represents an underexplored path that could benefit all resource-constrained researchers."

## Theme 8: The Applied Learning Journey

* **Blog Post:** Practical Deep Learnings For Coders - Part 1 Notes and Examples
* **Kaggle Notebook:** BirdCLEF 2024 Recap (0.61 Final LB Score) 
* **Blog Post:** Recap: My First Live Kaggle Competition 
* **Blog Post:** Recap: HMS HBAC Kaggle Competition
* **Blog Post:** How Does Stable Diffusion Work?
* **Blog Post:** Initial Experiments with Imagenette
* **Blog Post:** An Analysis of Batch Size vs. Learning Rate on Imagenette
* **Blog Post:** Takeaways from Gemini Deep Research Report on Small Batch Training Challenges
