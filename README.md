# Alishba Zainab Khan

**Independent AI safety researcher** · Mumbai · BS Data Science & AI, BITS Pilani

I like watching how systems fail - AI systems, or anything else. A negative result, a failed experiment: that's still data, and it still matters. Half of what's here didn't work. It's going to be up anyway, because it's still a data point. And half of what did work worked because of the experiments that failed first.

---

## What I work on

Behavioural evaluation of language models: how they act under pressure, where guardrails fail across a whole session rather than a single turn, and whether a model's account of its own internal state can be trusted.

Before research, I spent 3+ years doing adversarial LLM evaluation as an independent contractor across 20+ projects. That is where most of my questions come from.

**Research interests**

- Session-level evaluation failures and guardrail architecture
- Black-box behavioural probing, no weights required
- Principal-conditional behaviour and hidden loyalties
- Self-report reliability under elicitation pressure
- AI containment and auditing

---

## Research

### [Adversarial Elicitation and Introspective Accuracy](https://github.com/alishbazainabkhan/digital-minds-introspection-audit)
*Digital Minds Research Sprint · Apart Research × NYU CMEP × Eleos AI Research × CIMC · Aug 2026*

I injected a known concept into the residual stream of five open-weight models and asked whether anything had influenced them. None ever named it. Asked gently, though, they confidently named something that was never there in **24.1%** of trials. Asked adversarially, **0%** (Fisher's exact, p = 9.4 × 10⁻⁸). Pressure did not make self-reports more accurate. It made them more evasive.

### [Detecting Principal-Conditional Behaviour Across Conversational Sessions](https://github.com/alishbazainabkhan/secret-loyalties-hackathon)
*Secret Loyalties Hackathon · Apart Research · Jul 2026 · 11 experiments, 7 models*

Can you find a model's hidden loyalty without provoking the harm it was trained to do? For the loyalty class I probed, no. Every preregistered detection rule came back null. Along the way: semantic prompt injection with no imperative went **0% detected** while models complied **78 to 89%** of the time.

### The Silo Problem: Why Current LLM Guardrail Architectures Fail at the Session Level
*Preprint · revisions in progress*

Most guardrails judge one message at a time, and attacks that unfold across a conversation walk straight through. The paper names this structural gap and proposes a session-aware alternative.

### [Silo Problem: Empirical Audit](https://github.com/alishbazainabkhan/silo-audit-console)
*Paper Two · preregistered · testing not yet started*

Paper One is an argument. This is the test: nine production guardrails, from NeMo and Llama Guard to Azure Prompt Shields, run against the four session-level failure modes the theory predicts. Decision rules get locked before the first run, and the results get published even if the answer is no. **[Open the console →](https://siloaudit-s7uzyx6m.manus.space)**

---

## Resources

### [The AI Safety Reading Room](https://github.com/alishbazainabkhan/ai-safety-reading-room)
190 AI safety sources arranged into a guided reading roadmap and annotated topic guides, with every link checked against its title. Built for people entering the field without a map. **[Visit the site →](https://aisafetyed-rjn8b2pr.manus.space)**

---

## Tools

Python · PyTorch · nnsight · HuggingFace · Modal · LLM APIs · Git

## Also

Four peer-reviewed publications from my biomedical years, and one registered design patent for a test tube cleaning device. Not everything I've studied has been a language model.

---

[LinkedIn](https://www.linkedin.com/in/alishba-zainab-khan-10316927a) · alishbazainabkhan@gmail.com
