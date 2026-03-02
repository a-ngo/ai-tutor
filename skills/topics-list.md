# AI Engineering — Master Topic List

## 1. Machine Learning Foundations

- Supervised learning (regression, classification)
- Unsupervised learning (clustering, dimensionality reduction)
- Bias-variance tradeoff
- Cross-validation and model selection
- Feature engineering and selection
- Evaluation metrics (precision, recall, F1, AUC-ROC, etc.)
- Regularization (L1, L2, dropout, early stopping)
- Ensemble methods (bagging, boosting, stacking)

## 2. Deep Learning

- Neural network architectures (MLP, CNN, RNN, LSTM, GRU)
- Backpropagation and gradient descent variants (SGD, Adam, AdamW)
- Batch normalization, layer normalization
- Attention mechanisms
- Transfer learning and fine-tuning
- Residual connections and skip connections
- Loss functions and when to use them
- Hyperparameter tuning strategies

## 3. Transformer Architecture & LLMs

- Self-attention and multi-head attention
- Positional encoding (sinusoidal, RoPE, ALiBi)
- Tokenization (BPE, WordPiece, SentencePiece)
- Pre-training objectives (CLM, MLM, T5-style)
- Scaling laws (Chinchilla, compute-optimal training)
- Decoder-only vs encoder-decoder architectures
- KV cache and inference optimization
- Context window and long-context techniques

## 4. Prompt Engineering & LLM Application

- Zero-shot, few-shot, chain-of-thought prompting
- System prompts and instruction tuning
- Function calling / tool use
- RAG (Retrieval-Augmented Generation)
- Prompt injection and safety
- Output parsing and structured generation
- Evaluation of LLM outputs (human eval, automated metrics)
- Agentic patterns (ReAct, planning, tool loops)

## 5. Fine-Tuning & Alignment

- Full fine-tuning vs parameter-efficient methods
- LoRA, QLoRA, adapters
- RLHF (Reward modeling, PPO)
- DPO (Direct Preference Optimization)
- Constitutional AI
- Instruction tuning datasets and curation
- Catastrophic forgetting and mitigation

## 6. MLOps & Production ML

- ML pipelines (Kubeflow, Airflow, Prefect)
- Experiment tracking (MLflow, W&B)
- Model versioning and registry
- CI/CD for ML
- A/B testing for models
- Feature stores
- Data versioning (DVC)
- Monitoring and drift detection

## 7. Model Serving & Infrastructure

- Model serving frameworks (TorchServe, Triton, vLLM, TGI)
- Batching strategies (dynamic batching, continuous batching)
- GPU optimization (CUDA, mixed precision, Flash Attention)
- Quantization (INT8, INT4, GPTQ, AWQ, GGUF)
- Model distillation
- Containerization and Kubernetes for ML
- Cost optimization for GPU workloads
- Edge deployment

## 8. Data Engineering for ML

- Data pipelines and ETL for ML
- Data quality and validation
- Handling imbalanced datasets
- Data augmentation techniques
- Synthetic data generation
- Annotation tools and strategies
- Data privacy (differential privacy, federated learning)

## 9. Vector Databases & Retrieval

- Embedding models and spaces
- Vector similarity search (cosine, dot product, L2)
- Vector databases (Pinecone, Weaviate, Qdrant, Milvus, pgvector)
- Chunking strategies for documents
- Hybrid search (sparse + dense)
- Re-ranking
- Indexing algorithms (HNSW, IVF, PQ)

## 10. AI Safety & Ethics

- Bias detection and mitigation
- Model interpretability (SHAP, LIME, attention visualization)
- Hallucination detection and reduction
- Red-teaming and adversarial testing
- Responsible AI frameworks
- AI regulation awareness (EU AI Act basics)

## 11. Software Engineering for AI

- Python best practices for ML code
- Testing ML systems (unit tests, integration tests, data tests)
- API design for ML services (REST, gRPC)
- Async processing and queuing for ML workloads
- Error handling and fallback strategies
- Documentation for ML systems
- Code review practices for ML

## 12. Emerging / Advanced Topics

- Mixture of Experts (MoE)
- Multimodal models (vision-language, audio)
- Diffusion models
- State space models (Mamba)
- Speculative decoding
- Reinforcement learning from environment feedback
- AI agents and multi-agent systems
