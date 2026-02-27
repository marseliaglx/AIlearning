# Module 19: A Brief History of AI — From Turing to Transformers

[← Previous: AI Security & Ethics](18-ai-security.md) | [Back to Learning Path](../README.md) | [Next: People to Follow →](20-people-to-follow.md)

---

*Your D4B course covers AI history, and Nate tells the story of how we got from spam filters to ChatGPT. This module synthesizes both into a timeline that helps you understand why things happened when they did.*

---

## Why History Matters

Understanding AI's history prevents two common mistakes: thinking AI is brand new (it's not — the field is 70 years old) and thinking the current moment is just another hype cycle (it's qualitatively different, and the history explains why).

---

## The Timeline

### 1950s: The Birth of AI
- **1950** — Alan Turing publishes "Computing Machinery and Intelligence," proposing the Turing Test
- **1956** — Dartmouth Conference: John McCarthy coins the term "Artificial Intelligence." Researchers believe human-level AI is 20 years away
- Early programs could play checkers and prove mathematical theorems
- **Approach:** Symbolic AI — encoding human knowledge as rules and logic. "If X then Y."

### 1970s: The First AI Winter
- Early optimism collided with reality. Symbolic AI couldn't scale — real-world problems had too many rules and exceptions
- Funding dried up as promises went unmet
- Key lesson: **"Pure logic is brittle"** — it breaks when facing noise, uncertainty, or incomplete knowledge (as your D4B course emphasizes)

### 1980s: Expert Systems
- AI revival through **expert systems** — software that encoded domain expertise into decision trees
- MYCIN diagnosed bacterial infections. XCON configured computer orders at Digital Equipment Corporation
- Commercial success, but limited: expensive to build, impossible to maintain, brittle at edges
- **Relevance to KM:** Expert systems were essentially formalized knowledge management — capturing expert knowledge in rules. The challenge of keeping them current mirrors today's knowledge base maintenance challenges.

### Late 1980s–1990s: The Second AI Winter
- Expert systems proved too expensive and rigid
- Another funding collapse
- But beneath the surface, a different approach was gaining traction...

### 1990s–2010s: The Machine Learning Renaissance
- **New paradigm:** Instead of encoding rules, let the algorithm learn patterns from data
- **1997** — IBM's Deep Blue defeats Garry Kasparov at chess (your D4B course's Kasparov reference)
- **Key techniques:** Support Vector Machines, Random Forests, logistic regression — "classic ML" that powered spam filters, recommendation engines, and credit scoring
- **The limitation:** These methods required humans to decide which features of the data mattered (**feature engineering**). Success depended more on human intuition than algorithm sophistication.

### 2012: The Deep Learning Breakthrough
Three forces converged simultaneously:
1. **Cheap parallel GPUs** — Graphics cards became general-purpose math engines
2. **Large labeled datasets** — ImageNet provided millions of categorized images
3. **Deeper neural networks** — More layers could learn features automatically

**AlexNet** (2012) won the ImageNet competition by a massive margin using a deep convolutional neural network, proving that deep learning worked at scale. This is the moment modern AI begins.

- **2013** — Word2Vec showed that neural networks trained on text could learn semantic relationships: **king − man + woman ≈ queen**. Embeddings were born.
- **2014** — GANs (Generative Adversarial Networks) enabled AI image generation
- **2016** — Google DeepMind's **AlphaGo** defeats the world Go champion — a game believed to require human intuition

### 2017: "Attention Is All You Need"
Google researchers publish the **transformer** paper. Everything changes.
- Replaced sequential processing (RNNs, LSTMs) with parallel attention
- Enabled training on thousands of GPUs simultaneously
- Could handle long-range dependencies in text

(See [Module 5](05-neural-networks-transformers.md) for how transformers work.)

### 2018–2022: The Scaling Era
- **BERT** (2018, Google) — Transformed search by understanding query intent
- **GPT-2** (2019, OpenAI) — Generated surprisingly coherent text; OpenAI initially withheld it over misuse concerns
- **GPT-3** (2020) — 175 billion parameters. First model to feel genuinely capable in conversation. API launched; developers started building on top of it
- **DALL-E** (2021) — Text-to-image generation became real
- **ChatGPT** (Nov 2022) — GPT-3.5 with RLHF in a chat interface. Reached 100 million users in 2 months. The inflection point for public AI awareness.

### 2023–2025: The Current Era
- **GPT-4** (March 2023) — Multimodal, dramatically more capable
- **Claude** (Anthropic), **Gemini** (Google), **Llama** (Meta open-source) — Multiple competing frontier models
- **RAG, agents, and tool use** become standard enterprise patterns
- **AI regulation** — EU AI Act enters force
- Nate's "summer of consolidation" — models converging toward unified, enterprise-grade platforms

---

## The Pattern: Logic vs Learning

Your D4B course highlights a fundamental spectrum in AI:

**Pure Logic** (symbolic AI, expert systems) → Slow thinking, deliberative, model-based. Amazing achievements but "pure logic is brittle" — it breaks with noise and uncertainty.

**Pure Learning** (deep learning, LLMs) → Fast thinking, instinctive, pattern-based. Amazing recent achievements but "pure learning is brittle" — it has bias, interpretability, and robustness problems.

The frontier of AI research is about combining both — **neuro-symbolic AI** that can learn from data AND reason with logic. This is on your D4B course syllabus as a current trend, and it's worth watching.

---

## The Kahneman Connection

Your D4B course also draws a parallel to Daniel Kahneman's System 1 and System 2 thinking:

- **System 1** (fast, intuitive, automatic) ≈ Current LLMs (pattern matching, quick responses)
- **System 2** (slow, deliberate, logical) ≈ Reasoning models, chain-of-thought, planning

The newest models (like OpenAI's o-series reasoning models) are essentially adding System 2 capabilities on top of System 1 — "thinking harder" when the problem requires it. This is the direction GPT-5 is pushing toward.

---

## Key Takeaways

- AI is 70 years old, with repeated cycles of hype and winter
- The current era is qualitatively different because of transformers, scale, and data
- Expert systems (1980s) were early KM — encoding expert knowledge in rules
- Deep learning breakthrough (2012) came from GPUs + data + deeper networks converging
- The transformer (2017) enabled everything we see today
- ChatGPT (2022) was the public inflection point
- The logic vs learning spectrum is the fundamental tension in AI — combining both is the frontier

---

[← Previous: AI Security & Ethics](18-ai-security.md) | [Back to Learning Path](../README.md) | [Next: People to Follow →](20-people-to-follow.md)
