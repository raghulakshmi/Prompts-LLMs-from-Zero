# LLM Book Series — Overview

A four-book series that takes readers from no AI background to understanding, building, and operating LLM systems.

## Our Teaching Standard

Explain each concept and its purpose before relying on it. Develop the mechanism patiently, then use worked examples to make it concrete.

- Assume intelligence and curiosity, but no unexplained prerequisites.
- Introduce terminology before using it to explain another concept.
- Explain why an approach is useful, how it works, and where it fails.
- Distinguish teaching analogies from actual mechanisms.
- Separate historical development from the order used for teaching.
- Introduce mathematics and programming progressively where needed.
- Use examples from different disciplines.
- Verify technical claims and label illustrative or synthetic examples.
- Keep the main explanations durable and maintain changing implementation details in a companion repository.

## Book 1 — Prompts: LLMs from Zero

### Purpose

Build a foundation for readers from any discipline, with no assumed AI or programming knowledge.

### Scope

- Artificial intelligence: meaning, purpose, and applications.
- Programs, explicit rules, and their limitations.
- Machine learning, models, parameters, and training.
- Neural networks and deep learning.
- Generative AI.
- Language models and large language models.
- Transformers and GPT at a conceptual level.
- Conversational applications and AI assistants.
- Prompts, instructions, examples, and context.
- Capabilities, limitations, uncertainty, and verification.
- Systematic comparison and evaluation of responses.

### Reader Outcome

The reader can explain the main concepts, use assistants thoughtfully, and assess their responses.

### Capstone

A practical, no-code project with documented prompts, test cases, results, revisions, and limitations.

### Boundary

Conceptual understanding and informed use. Implementing models and building software applications belong in later books.

## Book 2 — Parameters: Inside the Model

### Purpose

Explain the internal computations that allow a language model to learn and generate text.

### Scope

- Necessary mathematical and programming foundations.
- Numerical representations and embeddings.
- Neural networks and their computations.
- Parameters, predictions, and loss.
- Gradients, backpropagation, and optimization.
- Training data and generalization.
- Attention and transformer architecture.
- Token generation and sampling.
- Building and training a small language model.
- Fine-tuning and adaptation, including LoRA.
- Conceptual introduction to further post-training methods.

### Reader Outcome

The reader can trace the computations in the model we build, train a small language model, and explain what changes during training and adaptation.

### Capstone

A small language model the reader has trained, inspected, evaluated, and modified.

### Boundary

Model mechanisms and small-scale implementation. Large-scale operation belongs primarily in Book 4.

## Book 3 — Pipelines: Building Reliable Systems

### Purpose

Teach readers to build useful, measurable applications around language models.

### Scope

- Programming and API foundations for application development.
- Requests, responses, credentials, and error handling.
- Structured outputs, schemas, and validation.
- Document preparation and retrieval.
- Retrieval-augmented generation (RAG).
- Tool calling and execution boundaries.
- Workflows, orchestration, and agents.
- Conversation state and application-managed memory.
- Application security and input trust.
- Evaluation datasets, scoring, and regression checks.
- Failure investigation.
- Quality, latency, and cost tradeoffs.

### Reader Outcome

The reader can build and evaluate an LLM application, explain its design choices, and investigate failures.

### Capstone

A working application that uses reference information and bounded tools, supported by an evaluation report.

### Boundary

Application design and implementation. Book 2 is not a prerequisite; the necessary model concepts receive a concise bridge.

## Book 4 — Production: The LLM Engineer’s Handbook

### Purpose

Teach readers to deploy, operate, and improve LLM systems under real constraints.

### Scope

- Deployment architectures and model serving.
- Performance, capacity, and scaling.
- Resource requirements and cost management.
- Security, privacy, and access control.
- Monitoring, logging, and operational visibility.
- Production evaluation and regression.
- Model, prompt, data, and application versioning.
- Controlled releases and rollback.
- Dependency failures and resilience.
- Incident investigation and recovery.
- Relevant large-scale training and infrastructure considerations.
- System design case studies.

### Reader Outcome

The reader can operate an LLM application and manage its quality, reliability, security, and cost over time.

### Capstone

An operational application taken through deployment, monitoring, a controlled change, and a failure-and-recovery exercise.

## How the Books Fit Together

| Book | Governing Question |
|---|---|
| Prompts | What is this technology, and how do I use it thoughtfully? |
| Parameters | How does the model compute and learn? |
| Pipelines | How do I build and evaluate a useful application? |
| Production | How do I operate that application reliably over time? |

Each book provides a complete learning outcome and a bridge to the next relevant stage.

Readers interested in application development may move from Book 1 to Book 3. Readers seeking model internals may proceed from Book 1 to Book 2.

