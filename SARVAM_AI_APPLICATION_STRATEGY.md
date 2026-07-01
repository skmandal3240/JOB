# Sarvam AI Application Strategy

Target: [Sarvam AI Careers](https://www.sarvam.ai/careers) — India-focused GenAI company building foundational models, speech/text/translation systems, and Indic-language LLMs.

---

## 1. Role Targeting

Sarvam's open roles skew toward ML Engineering (Foundational Models, Training Infra, Inference, Sarvam Studio). There is no dedicated "fresher" ladder listed publicly, so the practical entry points for a fresher profile are:

- **ML Engineer / AI Engineer (Associate or entry band)** — apply even if the listing reads mid-level; a strong project portfolio can offset lack of formal experience.
- **Applied AI / Data roles on Sarvam Studio** (their dubbing/product surface) — good fit if you lean into the Data Analytics certificate + Python/ML skills.
- **Open/general application** — many AI-native companies keep a standing "Talent Pool" form even without a matching req; use it and reference specific teams (Foundational Models, Inference, Studio).

**Action:** Check `sarvam.ai/careers` weekly for new "Foundational Models," "Inference," or "Studio" listings tagged 0–2 years experience, and apply within 48 hours of posting — early applicants get disproportionate attention at fast-scaling startups.

---

## 2. Strategic Learning & Certification Path

Sarvam's core bets are **Indic-language LLMs, speech/translation, and efficient training/inference**. Certifications should prove you can operate in that stack, not just "AI in general."

### Free, respected, fast certifications (do these while applying)
1. **DeepLearning.AI — "Generative AI with LLMs" (Coursera, audit free)** — covers transformer fundamentals, fine-tuning, RLHF; directly maps to Sarvam's core business.
2. **Hugging Face NLP Course (huggingface.co/course, fully free)** — hands-on with `transformers`, tokenizers, fine-tuning on custom datasets; produces a portfolio-ready skill set.
3. **Google Cloud "Introduction to Generative AI" + "Generative AI for Developers" (free tier on Google Cloud Skills Boost)** — short, credentialed, adds a recognizable logo next to your Data Analytics certificate.

Optional stretch (still free): **fast.ai "Practical Deep Learning for Coders"** if you want the strongest hands-on PyTorch grounding.

### Tech stack to master
- **PyTorch** (Sarvam's stack is PyTorch-based) — move past Scikit-learn/Keras-only comfort.
- **Hugging Face ecosystem**: `transformers`, `datasets`, `peft`/LoRA for fine-tuning, `tokenizers`.
- **LLM fine-tuning fundamentals**: LoRA/QLoRA, instruction tuning, evaluation (perplexity, BLEU/chrF for translation tasks).
- **Indic NLP basics**: tokenization challenges for Indian scripts, transliteration, existing corpora (IndicCorp, AI4Bharat datasets).
- **Inference/serving**: vLLM or TGI basics, quantization (GGUF/AWQ), so you can speak to the "training infra" and "inference" job families.
- **Vector/RAG basics**: embeddings, a vector DB (you already use Supabase — its `pgvector` extension is a natural bridge).

---

## 3. Project Portfolio Strategy (beyond the AI OS project)

Build 2–3 projects that map directly onto Sarvam's mission — each should ship with a README, a demo (video/GIF), and be pushed to GitHub under your existing account.

1. **Indic-language fine-tune demo** — Take a small open model (e.g., a 1–3B parameter model) and fine-tune it with LoRA on an Indic-language instruction dataset (AI4Bharat/IndicInstruct or similar open datasets). Publish before/after eval numbers. This single project speaks directly to Sarvam's "Indic LLM" identity.
2. **Local GPU inference & benchmarking project** — Document setting up a local/rented GPU box, running quantized open-weight models, and benchmarking latency/throughput. Ties your existing "researching local GPU requirements" work into a concrete, shareable artifact — relevant to their "Training Infra" and "Inference" teams.
3. **Speech-to-text or translation mini-pipeline for an Indian language** — Wrap an open ASR/translation model (e.g., Whisper variants, IndicTrans2) in a small app (use your existing Supabase/Vercel stack) that takes audio/text in a regional language and returns transcription/translation. This mirrors Sarvam Studio's product surface almost exactly.

Each project should be linked from your resume's GitHub and referenced by name in your application/cover note — recruiters at model-building companies weight demonstrated hands-on model work far above certificates.

---

## 4. Interview Positioning & Long-Term Career/Startup Strategy

### Framing your entrepreneurial background
- Position hub management and AstroVeda/SpiceGlow work as evidence of **ownership and execution speed**, not as a signal you're a flight risk. Use language like: *"I've run the 0-to-1 side of building things — ops, roadmap, GTM — and I'm now deliberately choosing to go deep on the technical/model-building side before I build again. Sarvam is exactly where that depth compounds fastest."*
- Frame it as **sequencing, not detour**: "I know how to build a company; I'm here to learn how to build the technology inside one, at a company that's already doing it at the hardest level (foundational models)."
- Never mention a specific timeline for leaving. Emphasize a 3–5 year horizon of "learn deeply, ship real things, then decide."

### What to learn *while* at Sarvam, in service of your own startup later
- **Model lifecycle end-to-end**: data curation → training/fine-tuning → eval → deployment → monitoring. This is the exact loop you'll need to run yourself later, at much smaller scale.
- **Infra economics**: how Sarvam reasons about GPU cost, training budgets, and inference cost per token/request — the single biggest lever in any future AI startup's unit economics.
- **Product-market fit for AI-native products in India**: how Sarvam scopes Indic-language product surfaces, what data/localization problems actually matter to Indian users/businesses.
- **How a foundational-model team is organized**: research vs. applied vs. infra split, how research gets productized — a blueprint you'll reuse when structuring your own team.
- **Enterprise/GTM motion for deep-tech**: even as an IC, pay attention to how Sarvam sells "hard tech" (not just an app) — this maps directly onto AstroVeda-style deep-tech GTM.

### Interview talking points checklist
- Lead with the AI OS project and the specific fine-tuning/inference projects above — these are your strongest signal as a fresher.
- Have a clear, rehearsed 60-second story connecting: CS degree → entrepreneurial ventures → deliberate pivot to deep AI skill-building → why Sarvam specifically (Indic LLMs, not "AI in general").
- Be ready to whiteboard or talk through basics of transformer architecture, LoRA fine-tuning, and why quantization matters for inference cost — these are the concrete technical bars for ML Engineer interviews at this class of company.
