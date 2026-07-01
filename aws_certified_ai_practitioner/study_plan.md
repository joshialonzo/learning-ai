# AWS Certified AI Practitioner — Study Plan
**Exam date:** July 17, 2026 | **Start date:** June 30, 2026 | **Days remaining:** 17

## Where Things Stand

| Module | Topic | Exam Weight | Status |
|---|---|---|---|
| 1 | Exam Foundation | — | Done |
| 2 | Fundamentals of AI and ML | 20% | Mostly done (ML Lifecycle section missing) |
| 3 | Fundamentals of Generative AI | 24% | Empty |
| 4 | Applications of Foundation Models | 28% | Empty |
| 5 | Responsible and Secure AI Solutions | 28% (14+14) | Empty |

---

## Weekly Schedule

### Week 1: Jun 30 – Jul 6

**Jun 30 – Jul 1: Finish Module 2**
- Complete the ML Development Lifecycle section (data collection → training → evaluation → deployment → monitoring)
- Key AWS services to know: SageMaker, SageMaker Pipelines, SageMaker Data Wrangler
- Write `module_2_questions.md` answers and add more practice questions

**Jul 2 – Jul 6: Module 3 — Fundamentals of Generative AI (24%)**

Core topics to cover:
- Foundation models: what they are, how they differ from traditional ML
- Tokens, embeddings, context windows, temperature, top-p
- Transformer architecture (high-level — encoder, decoder, attention)
- AWS services: Amazon Bedrock, Amazon Titan, Amazon Q, Stability AI on Bedrock
- Retrieval-Augmented Generation (RAG)
- Limitations of generative AI (hallucinations, bias, data freshness)
- AWS infrastructure for generative AI (Trainium, Inferentia chips)

Deliverable: `module_3.md` notes + `module_3_questions.md` practice questions

---

### Week 2: Jul 7 – Jul 13

**Jul 7 – Jul 11: Module 4 — Applications of Foundation Models (28% — highest weight)**

Core topics to cover:
- Prompt engineering techniques: zero-shot, few-shot, chain-of-thought, role prompting
- Fine-tuning vs. RAG vs. prompt engineering (when to use each)
- Amazon Bedrock agents and knowledge bases
- Inference parameters and their effects (temperature, top-k, top-p, max tokens)
- Evaluating foundation model outputs: BLEU, ROUGE, human evaluation, BERTScore
- Cost and latency trade-offs when selecting a model
- Model customization options in Bedrock (continued pre-training, fine-tuning)

Deliverable: `module_4.md` notes + `module_4_questions.md` practice questions

**Jul 12 – Jul 13: Module 5 — Responsible and Secure AI (28%)**

Responsible AI topics (14%):
- Fairness, transparency, accountability, privacy
- Bias types: data bias, algorithmic bias, societal bias
- Explainability tools: SageMaker Clarify, SageMaker Model Cards
- Human-in-the-loop (Amazon Augmented AI / A2I)

Security & Governance topics (14%):
- IAM roles and policies for AI workloads
- VPC endpoints, encryption at rest and in transit for SageMaker/Bedrock
- AWS Artifact, AWS Config, AWS Audit Manager for compliance
- Model governance with SageMaker Model Registry and Model Dashboard
- Data governance: AWS Glue Data Catalog, Lake Formation

Deliverable: `module_5.md` notes + `module_5_questions.md` practice questions

---

### Week 3: Jul 14 – Jul 17

**Jul 14: Full review pass**
- Re-read all module notes
- Focus on AWS service names — the exam tests whether you know which service does what

**Jul 15: Practice exam day**
- Take at least one full 65-question practice exam (AWS Skill Builder, Whizlabs, or Udemy)
- Review every wrong answer and trace it back to the relevant module

**Jul 16: Weak spots only**
- Spend the day only on topics where you got questions wrong
- Do NOT try to learn new material

**Jul 17: Exam day**
- Light review of AWS service names in the morning (15 min max)
- Trust your preparation

---

## High-Priority AWS Services to Know Cold

| Service | What to know |
|---|---|
| Amazon Bedrock | Managed foundation model API; supports fine-tuning and RAG |
| Amazon SageMaker | Full ML lifecycle platform (training, tuning, deployment) |
| SageMaker Clarify | Bias detection and explainability |
| SageMaker Data Wrangler | Data preparation for ML |
| SageMaker Ground Truth | Data labeling with human review |
| Amazon Q | Generative AI assistant for business and developers |
| Amazon Rekognition | Computer vision (image/video analysis) |
| Amazon Comprehend | NLP (sentiment, entity, key phrase extraction) |
| Amazon Transcribe | Speech-to-text |
| Amazon Polly | Text-to-speech |
| Amazon Translate | Machine translation |
| Amazon Lex | Conversational AI / chatbot builder |
| Amazon Personalize | Recommendation engine |
| Amazon Forecast | Time-series forecasting |
| Amazon A2I | Human review of ML predictions |
| AWS Trainium/Inferentia | Custom chips for training and inference |

---

## Key Concepts Cheat Sheet (update as you study)

- **Hallucination**: When a model generates plausible but incorrect information
- **RAG**: Augments model responses with real-time data retrieval to reduce hallucinations
- **Fine-tuning**: Adapting a pre-trained model on domain-specific data
- **Overfitting**: Model performs well on training data but poorly on new data
- **Underfitting**: Model fails to capture patterns in training data
- **Bias in AI**: Systematic errors that lead to unfair outcomes
- **Explainability**: The ability to understand why a model made a decision
- **Prompt injection**: An attack where malicious input manipulates model behavior
