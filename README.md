# 🚀 PyTorch Journey for AI Engineering

Welcome to my PyTorch learning and AI Engineering journey.

This repository contains:
- PyTorch fundamentals
- Tensor operations
- Deep learning basics
- Neural networks
- GPU training
- Agentic AI foundations
- Production-level AI engineering concepts

My goal is to become a strong AI Engineer capable of building real-world AI systems and Agentic AI applications.

---

# 📚 Topics Covered

## 🔹 PyTorch Basics
- Tensors
- Tensor operations
- Tensor shapes
- Tensor indexing
- Broadcasting
- GPU usage
- Autograd
- Gradients

## 🔹 Tensor Operations
- `torch.tensor()`
- `torch.zeros()`
- `torch.ones()`
- `torch.empty_like()`
- `torch.sum()`
- `torch.mean()`
- `torch.clamp()`
- `torch.ceil()`
- `torch.floor()`

## 🔹 Neural Networks
- `nn.Module`
- `nn.Linear`
- Activation functions
- Forward propagation
- Loss functions
- Optimizers
- Backpropagation

## 🔹 Deep Learning
- CNN basics
- RNN basics
- Transformers
- Attention mechanisms
- Embeddings

## 🔹 AI Engineering
- Model serving
- AI workflows
- Vector databases
- LangChain
- LangGraph
- CrewAI
- AutoGen
- Multi-agent systems

## 🔹 Production AI Systems
- FastAPI
- Docker
- Kubernetes
- Redis
- PostgreSQL
- Kafka
- Kestra workflows
- CI/CD pipelines

---

# 🧠 Sample Tensor Operations

## Create Tensor

```python
import torch

x = torch.tensor([
    [1, 2, 3],
    [4, 5, 6]
])

print(x)
```

---

## Sum Operations

```python
# total sum
torch.sum(x)

# sum along columns
torch.sum(x, dim=0)

# sum along rows
torch.sum(x, dim=1)
```

---

## Ceil, Floor, Clamp

```python
x = torch.tensor([1.2, 2.7, -1.4])

print(torch.ceil(x))
print(torch.floor(x))

y = torch.tensor([-5, 2, 8, 15])

print(torch.clamp(y, min=0, max=10))
```

---

## Empty Like

```python
x = torch.tensor([[1, 2], [3, 4]])

y = torch.empty_like(x)

print(y)
```

---

# 🎯 Goal of This Repository

This repository is focused on:
- mastering PyTorch deeply
- understanding AI systems internally
- building production-ready AI applications
- learning Agentic AI engineering
- preparing for AI/ML interviews
- creating scalable AI architectures

---

# 🛠️ Tech Stack

- Python
- PyTorch
- FastAPI
- LangChain
- LangGraph
- Docker
- Kubernetes
- Redis
- PostgreSQL
- Kafka
- Kestra

---

# 📈 Future Additions

- LLM fine-tuning
- RAG pipelines
- AI agents
- Multi-agent orchestration
- Vector search systems
- Distributed training
- AI observability
- Production deployment

---

# 🤝 Connect & Learn

This repository is part of my continuous learning journey in AI Engineering and Agentic AI.

Always learning.
Always building.
Always shipping.

🚀
