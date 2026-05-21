# Hi, I'm Aniruddha Fale

# Interests
## ML Systems
## AI Agents

# Projects

## Distributed ML Systems
- https://github.com/aniruddha1607/autodiff-kernel-mpi
  
- Built an automatic differentiation engine from scratch in Python using DFS-based gradient computation, then used it to implement a transformer language model with self-attention for next-word prediction.

- Wrote a custom fused GPU kernel in Triton which combines matrix multiplication, addition, and activation into a single operation which reduces per-step compute overhead for large tensor inputs.

- Developed a distributed training system using MPI Interface to synchronize and aggregate gradients across multiple machines.

- Working on Analyzing Llama-3 8B and DeepSeek-V3 training costs

- Working on Implementing Speculative Decoding with draft-target models


## UNIX Agent 
- https://github.com/aniruddha1607/UNIX_Agent.git

- Built a conversational CLI agent that translates natural language into shell commands using the OpenAI Agents SDK, enabling beginners to perform UNIX operations without memorizing syntax.

- Designed a 3-tier safety architecture (guardrails) autonomous execution for safe commands, confirmation prompts for destructive actions, and hard blocks for system paths and privilege escalation, with all attempts logged to SQLite for full auditability.

- Achieved 0.92–1.00 pass@1 task success rate across scenario-driven evaluation runs covering filesystem operations, tutoring quality, and guardrail enforcement.

- Working to make the system fully offline by creating a macOS App so not a single API call leaves the machine


## Intelli-Assist; A architecture to process videos using LLMs
- https://github.com/semisenioritis/Intelli-assist

- Designed a multimodal LLM architecture using LLaMA 80B and LLaVA via Hugging Face Transformers, enabling vision-language models to process screen recordings and predict user intent.

- Implemented a frame selection algorithm using PCA and K-Means clustering, reducing the number of frames sent to the model for processing by 90\%, improving inference latency.

- Built a pipeline to process screen recordings by extracting frames, performing cursor-focused OCR, adding screen metadata, selecting representative frames, and passing processed data to NVIDIA DGX-hosted models for scalable inference.


