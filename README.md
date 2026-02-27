# 🧠 AI & LLM Knowledge Base

**A structured learning repository for understanding Large Language Models, AI concepts, and their practical applications in knowledge management and content strategy.**

*Built by Marcela Gleixner — Knowledge Management Professional exploring the intersection of KM, content strategy, and AI.*

---

## Why This Exists

The AI landscape moves fast and information is scattered across substacks, YouTube videos, courses, and Twitter threads. This repository is a **single source of truth** — organized, referenced, and designed to be revisited as concepts click into place over time.

Each topic is a standalone module you can read in any order, though the suggested path below builds understanding progressively.

---

## 📚 Learning Path

### Foundation Layer (Start Here)
| # | Module | What You'll Learn |
|---|--------|-------------------|
| 1 | [What Is a Large Language Model?](modules/01-what-is-an-llm.md) | The core concept — what LLMs actually are and aren't |
| 2 | [Tokens & Tokenization](modules/02-tokens.md) | The basic units AI "thinks" in |
| 3 | [The Context Window](modules/03-context-window.md) | The most important constraint in modern AI |
| 4 | [How Responses Are Generated](modules/04-how-responses-work.md) | Probability, temperature, and why AI "hallucinates" |

### Architecture & Training
| # | Module | What You'll Learn |
|---|--------|-------------------|
| 5 | [Neural Networks & Transformers](modules/05-neural-networks-transformers.md) | The architecture underneath it all |
| 6 | [Training: Pre-training, Fine-tuning & RLHF](modules/06-training.md) | How a model goes from raw text to helpful assistant |
| 7 | [Embeddings & Vector Search](modules/07-embeddings.md) | How AI understands meaning mathematically |

### Practical Application Layer
| # | Module | What You'll Learn |
|---|--------|-------------------|
| 8 | [Prompt Engineering](modules/08-prompt-engineering.md) | Writing effective instructions for AI systems |
| 9 | [RAG: Retrieval-Augmented Generation](modules/09-rag.md) | How enterprise AI connects to real knowledge bases |
| 10 | [AI Agents & Agentic Systems](modules/10-agents.md) | The frontier: AI that takes actions, not just answers |
| 11 | [Multimodal AI](modules/11-multimodal.md) | Vision, audio, and beyond text |

### Strategic & Career Layer
| # | Module | What You'll Learn |
|---|--------|-------------------|
| 12 | [AI in the Enterprise](modules/12-ai-enterprise.md) | How organizations are actually deploying AI |
| 13 | [The KM–AI Connection](modules/13-km-ai-connection.md) | Why knowledge management is critical to AI success |
| 14 | [Key Terms Glossary](modules/14-glossary.md) | Quick-reference for interviews and conversations |

### Deep Dives (Nate's A-to-Z + D4B Course)
| # | Module | What You'll Learn |
|---|--------|-------------------|
| 15 | [Inside the Machine — Advanced Architecture](modules/15-advanced-architecture.md) | Latent space, attention heads, MoE, feature superposition |
| 16 | [How AI Learns — Gradient Descent & Beyond](modules/16-how-ai-learns.md) | Scaling laws, emergent abilities, LoRA, quantization |
| 17 | [Sampling & Inference](modules/17-sampling-and-inference.md) | Top-k, top-p, beam search — how AI picks words |
| 18 | [AI Security, Ethics & Governance](modules/18-ai-security.md) | Prompt injection, EU AI Act, bias, the 4 ethical principles |
| 19 | [AI History — Turing to Transformers](modules/19-ai-history.md) | 70 years of AI, AI winters, and why now is different |
| 20 | [People to Follow & Resources](modules/20-people-to-follow.md) | Nate's 11 voices, 7 resources, and a learning strategy |

---

## 🗺️ Concept Map

```
                    ┌─────────────────────┐
                    │   Neural Networks    │
                    │   & Transformers     │
                    └────────┬────────────┘
                             │
                    ┌────────▼────────────┐
                    │    Pre-training      │
                    │  (learns language)   │
                    └────────┬────────────┘
                             │
                    ┌────────▼────────────┐
                    │    Fine-tuning       │
                    │  (learns to help)    │
                    └────────┬────────────┘
                             │
                    ┌────────▼────────────┐
                    │       RLHF          │
                    │ (learns human values)│
                    └────────┬────────────┘
                             │
              ┌──────────────▼──────────────┐
              │     THE TRAINED MODEL        │
              │  (Claude, GPT, Gemini, etc.) │
              └──────────────┬──────────────┘
                             │
            ┌────────────────┼────────────────┐
            │                │                │
   ┌────────▼───────┐ ┌─────▼──────┐ ┌───────▼───────┐
   │ Context Window  │ │  Tokens    │ │  Temperature  │
   │ (working memory)│ │ (the units)│ │ (randomness)  │
   └────────┬───────┘ └────────────┘ └───────────────┘
            │
   ┌────────▼────────────────────────────────┐
   │          HOW IT'S USED                   │
   ├──────────────┬──────────┬───────────────┤
   │  Prompt      │  RAG     │   Agents      │
   │  Engineering │          │               │
   │              │ Embeddings│  Tool Use     │
   │  System      │ Vector DB │  Orchestration│
   │  Prompts     │ Retrieval │  Multi-step   │
   └──────────────┴──────────┴───────────────┘
            │
   ┌────────▼────────────────────────────────┐
   │     ENTERPRISE / KM CONNECTION           │
   │                                          │
   │  Content quality → Better retrieval      │
   │  Structured KBs → Better RAG             │
   │  Metadata/taxonomy → Better embeddings   │
   │  Governance → Trustworthy AI             │
   └──────────────────────────────────────────┘
```

---

## 🔖 How to Use This Repository

1. **Read the modules** in order for a progressive learning path, or jump to any topic that interests you
2. **Make your handwritten notes** — each module ends with "Key Takeaways" to summarize
3. **Use the glossary** (Module 14) as interview prep and quick reference
4. **Revisit** as your understanding deepens — these concepts layer on each other

---

## 📎 Recommended External Resources

These complement the modules — you don't need to consume them all at once:

- **Nate Jones' Substack** — Practical AI breakdowns and learning roadmaps (primary source for this repo's structure)
- **Nate's A-to-Z AI Cheat Sheet** — 26 concepts with mnemonics (Modules 15-18 expand on these)
- **3Blue1Brown: Neural Networks** (YouTube) — Visual math explanations
- **Andrej Karpathy: "Let's Build GPT from Scratch"** (YouTube) — Deep technical walkthrough
- **Simon Willison's Blog** — Practical LLM experimentation and honest assessments
- **Anthropic's Documentation** — docs.anthropic.com for understanding Claude specifically
- **Ethan Mollick's "One Useful Thing"** — AI in education and work (Substack)
- **Latent Space Podcast** — Technical but accessible AI industry coverage
- **Chip Huyen's "AI Engineering"** (O'Reilly, 2025) — Production AI systems guide
- **Digital4Business / Linköping University** — EU-funded AI in Business microcredential (Modules 18-19 incorporate this curriculum)

---

*Last updated: February 2026*
