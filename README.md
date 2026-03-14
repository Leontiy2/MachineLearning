# MachineLearning
Data MachineLearningPRO


# LLM Tools & Retrieval Project

## Project overview
A compact set of notebooks exploring tokenization and embeddings, attention/transformer intuition, LLM limitations, and practical model adaptation workflows (fine-tuning/LoRA) with model hosting and experiment tracking.


## Files

### Tokenization  
**Purpose:** explain tokenization and embeddings at a conceptual and toy-code level.  
**Content:** simple tokenizer → token→id mapping, embedding vectors, cosine similarity, PCA 2D visualization.  
**Result:** demonstration how text → token ids → embeddings → similarity produces semantic layout.

### limitationLLM.ipynb  
**Purpose:** summarize LLM limits and practical constraints.  
**Content:** context window sizes (examples for GPT-3.5 / GPT-4), memory vs. stateless inference, compute/cost tradeoffs, common failure modes (hallucinations, bias), mitigation patterns (retrieval, fine-tuning, distillation).  
**Result:** concise checklist of architectural and operational limitations when applying LLMs.

### ProjectHuggingFace.ipynb  
**Purpose:** pipeline for retrieval-augmented search and adapter-based model adaptation.  
**Content:** sentence embedding generation, building a small knowledge base, cosine similarity retrieval, demo search assistant; hands-on with model registration and adaptation tools (fine-tuning and LoRA) and experiment logging using :contentReference[oaicite:0]{index=0}.  
**Result:** working QA/search assistant and reproducible adaptation workflow ready for deployment to :contentReference[oaicite:1]{index=1} or export to cloud notebooks (e.g., :contentReference[oaicite:2]{index=2}) and code/portfolio on :contentReference[oaicite:3]{index=3}.
