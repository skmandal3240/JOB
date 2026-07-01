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

### Free certifications — full list (real, verified, no paywalled ones included)

These are quick (2–6 hours each) — treat them as a fast credibility layer, not the main event. The projects in Section 3 are what actually move the needle; certs just get you past resume filters and give LinkedIn-visible proof.

**Anthropic (do these first — you already build with Claude daily, so this is the most "you" credential set):**
1. **Anthropic Academy** (`anthropic.skilljar.com`) — official, free, certificate on completion, just needs an email. ~18 self-paced courses across three tracks: *AI Fluency*, *Product Training*, and *Developer Deep-Dives* (Claude API, prompt engineering, building agents, MCP server development). Do the Developer track courses — they map directly onto "AI engineer" skills.
2. **DeepLearning.AI × Anthropic — "Claude Code: A Highly Agentic Coding Assistant"** (learn.deeplearning.ai, free, certificate) — since you already work inside Claude Code, this formalizes it.

**Google:**
3. **Google Cloud Skills Boost — "Introduction to Generative AI," "Introduction to Large Language Models," "Generative AI for Developers," "Introduction to Responsible AI"** — free, each gives a completion badge you can pin on LinkedIn.

**NVIDIA:**
4. **NVIDIA DLI — "Generative AI Explained"** (free, certificate) — short, but an NVIDIA logo next to Sarvam's GPU/training-infra focus reads well.

**Hugging Face:**
5. **Hugging Face NLP Course** (huggingface.co/course, fully free) — hands-on with `transformers`, tokenizers, fine-tuning; also do the shorter **Audio Course** module if you build the speech/translation project below — same platform, same account.

**IBM:**
6. **IBM SkillsBuild — "Generative AI Fundamentals" + "Artificial Intelligence Fundamentals"** (free, Credly digital badge, LinkedIn-addable).

**DeepLearning.AI (general):**
7. Any 1–2 short courses at learn.deeplearning.ai relevant to your projects (e.g., a fine-tuning or RAG short course) — all free, all give a certificate, take 1–2 hours each.

**Kaggle (optional but well-regarded among ML practitioners specifically):**
8. **Kaggle Learn — "Intro to Deep Learning" + "Intro to Machine Learning"** micro-courses — free, instant certificate, and a Kaggle profile is itself a credibility signal (see Section 6).

Skip anything that charges for the certificate itself (e.g., Coursera specializations where only the audit is free) unless a specific listing asks for it by name.

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

---

## 5. Honest Readiness Score (Today) & Gap-Closing Plan

Scored against Sarvam's actual bar (they hire ML engineers who often already have strong ML fundamentals, sometimes research/publication background) — not against a generic "AI enthusiast" bar. No inflation, no placeholders counted as done.

| Category | Weight | Where you are today | Score |
|---|---|---|---|
| CS fundamentals (degree, coding) | 15% | B.E. CSE, CGPA 7.22 — solid baseline, unverified DSA/systems depth | 8/15 |
| Classical ML hands-on | 15% | One real project (fraud detection: Scikit-learn/Keras) | 8/15 |
| Deep learning / Transformers / LLM hands-on | 30% | None shipped yet — AI OS project is a roadmap/product layer, not a trained/fine-tuned model | 3/30 |
| Indic language / NLP-specific work | 15% | None yet | 0/15 |
| GPU / training infra hands-on | 10% | Research stage only, no completed training run | 2/10 |
| Certifications (ML/AI-relevant) | 5% | 1 general Data Analytics cert, not ML/LLM-specific | 2/5 |
| Public proof (GitHub, demos, writeups) | 10% | Unconfirmed/minimal public evidence | 2/10 |
| **Total** | **100%** | | **~25/100** |

**What this means:** ~25/100 is normal and expected for a fresher who hasn't yet built an LLM-specific project — it is not a verdict on potential, it's a snapshot of evidence that currently exists. Sarvam's ML Engineer bar for direct hire is roughly 70+ on this scale. The gap is closable and the plan to close it is already above (Sections 2–3): the 3 certifications and, more importantly, the 3 hands-on projects (LoRA fine-tune, GPU inference benchmark, speech/translation pipeline) are what move the "Deep learning/LLM," "Indic NLP," and "GPU infra" rows — the three heaviest-weighted, currently-lowest categories.

**Realistic timeline to interview-ready (~70/100), working consistently:**
- **Weeks 1–3:** Hugging Face NLP course + first LoRA fine-tune project shipped to GitHub with a README and eval numbers → moves Deep Learning/LLM row from 3→15, Public Proof 2→6.
- **Weeks 4–6:** Local/rented GPU benchmarking project + DeepLearning.AI GenAI course → GPU Infra 2→7, Certifications 2→4.
- **Weeks 7–9:** Speech/translation mini-pipeline for an Indian language (ties in Indic NLP directly) → Indic NLP 0→10, Deep Learning/LLM 15→22.
- **Weeks 10–12:** Polish GitHub profile, write short technical posts/READMEs for all 3 projects, mock interview on transformer/LoRA/quantization basics → Public Proof 6→9, CS Fundamentals 8→11.

Projected score after ~12 focused weeks: **~70/100** — genuinely competitive for an entry-level ML/AI role at a company like Sarvam. Nothing on this path requires claiming a skill before you've actually built with it — the score only moves when the project exists.

---

## 6. Compressed Timeline (Faster Path)

Certs alone are only a few hours each, so they don't need their own weeks — stack them in parallel with project work instead of doing them sequentially. This compresses Section 5's 12 weeks to **~6 weeks of intense, daily focus** (roughly double the daily hours of the original plan).

- **Week 1:** Knock out all 8 certifications from Section 2 in the background (a couple hours/day) while starting Project 1 (LoRA fine-tune) in parallel — pick the model/dataset, get a training run working end-to-end even if quality is rough.
- **Week 2:** Finish Project 1 properly — clean eval numbers, README, demo video/GIF, push to GitHub *and* upload the fine-tuned model + a live demo Space to Hugging Face Hub.
- **Week 3:** Project 2 (GPU inference benchmarking) — set up, run quantized models, collect latency/throughput numbers, publish writeup.
- **Week 4:** Project 3 (Indic speech/translation pipeline) — build the pipeline, deploy the demo on Vercel, connect it to your Supabase backend.
- **Week 5:** Polish everything simultaneously — GitHub profile README, Hugging Face profile, one short technical blog post per project, all cert badges added to LinkedIn.
- **Week 6:** Apply, and start reaching out directly (Section 6 below) while continuing to iterate on whichever project got the weakest results.

This is aggressive but realistic if you're treating it like a full-time push. The score-moving logic from Section 5 is unchanged — only the calendar is compressed, not the actual bar you need to clear.

---

## 7. Where to Showcase Your Skills (So the Right People Notice)

Certificates prove you *studied*. These prove you *can build* — which is what makes a hiring manager at an AI company actually want you:

1. **GitHub (primary)** — pin your 3 projects. Each repo needs: a clear README with the problem, approach, results (numbers, not adjectives), and a demo GIF/video at the top. A recruiter should understand the project in 15 seconds of scrolling.
2. **Hugging Face Hub (this is the one that gets AI companies' attention specifically)** — upload your fine-tuned model to the Model Hub and build a live, clickable demo on **Hugging Face Spaces** (free, Gradio/Streamlit). This is the single highest-signal place to exist for a company like Sarvam — their own team lives on HF.
3. **Kaggle profile** — if you do the Kaggle Learn courses, also enter one beginner-friendly competition or publish a notebook; Kaggle rank/notebooks are a known credibility shortcut among ML hiring managers.
4. **A personal portfolio site** (deploy on Vercel, which you already use) — one page linking your GitHub, HF Spaces, Kaggle, LinkedIn, and a one-line pitch. This is what you put in the "portfolio URL" field on every application.
5. **LinkedIn** — post short build-in-public updates as you finish each project/cert (not just the badge — one sentence on what you built and a link). This is how recruiters and even Sarvam engineers stumble onto you organically.
6. **X/Twitter AI community** — Sarvam's own engineers and founders are active there; a genuine, specific reply or post about your Indic fine-tuning project (tagging relevant accounts, not spamming) can get more attention than a cold application.
7. **Open-source contributions to AI4Bharat or Hugging Face `transformers`** — even one small merged PR into an org whose mission overlaps with Sarvam's (Indic NLP, model tooling) is a stronger signal than any certificate on this list. This is the highest-effort, highest-payoff item here.
8. **A short technical blog post per project** (dev.to, Hashnode, or your own site) — walks a reader through what you built and why; doubles as interview prep since you'll already have rehearsed the explanation.

Priority order if time is short: **GitHub → Hugging Face Hub/Spaces → portfolio site → LinkedIn posts → open-source PR → Kaggle → blog posts.**
