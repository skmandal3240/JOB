# AI Engineer Curriculum: Beginner → Job-Ready

Goal: go from wherever you actually are today to a skill level that top AI companies (Sarvam AI and peers) recruit for, with every step verifiable — not self-reported.

## How this system works
1. **Phases below**, each with free resources and a **checkpoint** (something you build/solve/ship).
2. Every checkpoint gets pushed as real code into `/projects/<phase>-<name>/` **in this same repo** — that's what makes progress checkable instead of just claimed.
3. `SKILL_TRACKER.md` is the scorecard. It only moves when there's a commit, a link, or a certificate to point at.
4. A recurring check-in re-reads this repo, updates the tracker, and hands you the next concrete task — see the note at the bottom.

This is a genuine fresh start, per your request — no phase is skipped or fast-tracked because of your CV or degree. Every phase, starting with Phase 0, gets done and proven in this repo as if from zero. Your CV/certificate still stand as real, honest history for the resume itself — they just don't buy you a shortcut here.

---

## Phase 0 — Programming Foundations (done fully, start to finish)
- **Learn:** what a program is, variables, data types, control flow (if/loops), functions, basic recursion, Git/GitHub basics (clone, add, commit, push, branch).
- **Free resources:** CS50x (Harvard, edX, free) — go through the actual introductory lectures/problem sets, not just a skim. freeCodeCamp's "Scientific Computing with Python" for extra reps.
- **Checkpoint:** 20 solved problems (arrays, strings, hashmaps) pushed to `/projects/phase0-foundations/`, each with a one-line comment on what it does and why your approach works.

## Phase 1 — Data Structures & Algorithms
- **Learn:** arrays, linked lists, trees, graphs, complexity analysis (Big-O).
- **Free resources:** NeetCode 150 (free), CS50.
- **Checkpoint:** 50 solved problems + a short written Big-O explanation for 5 of them, in `/projects/phase1-dsa/`.

## Phase 2 — Python for Data & ML
- **Learn:** Pandas, NumPy, OOP in Python, matplotlib/plotting.
- **Free resources:** Kaggle Learn "Python" + "Pandas" micro-courses.
- **Checkpoint:** a real data-analysis notebook (use your Data Analytics certificate skills on a public dataset) in `/projects/phase2-data-analysis/`.

## Phase 3 — Classical Machine Learning
- **Learn:** regression, classification, train/test splits, evaluation metrics, overfitting.
- **Free resources:** Kaggle Learn "Intro to Machine Learning," Andrew Ng's Machine Learning Specialization (audit free on Coursera).
- **Checkpoint:** a Kaggle notebook or competition entry in `/projects/phase3-classical-ml/`.

## Phase 4 — Deep Learning & PyTorch
- **Learn:** neural nets from scratch, backprop intuition, PyTorch basics, transfer learning.
- **Free resources:** fast.ai "Practical Deep Learning for Coders," Hugging Face NLP Course (intro chapters).
- **Checkpoint:** train a small net from scratch, then fine-tune a pretrained model with PyTorch — `/projects/phase4-deep-learning/`.

## Phase 5 — LLMs, Fine-Tuning & Indic NLP (your specialization for Sarvam)
- **Learn:** transformers, LoRA/QLoRA fine-tuning, tokenization for Indian scripts, quantized inference.
- **Free resources:** Hugging Face NLP Course (full), Anthropic Academy Developer track, AI4Bharat datasets.
- **Checkpoints (these are the 3 projects from the application strategy doc):**
  1. Indic-language LoRA fine-tune — `/projects/phase5-indic-finetune/`.
  2. Local/rented GPU inference benchmark — `/projects/phase5-gpu-benchmark/`.
  3. Speech/translation mini-pipeline for an Indian language — `/projects/phase5-speech-pipeline/`.

## Phase 6 — Portfolio, Certifications & Distribution
- Free certifications (see `SARVAM_AI_APPLICATION_STRATEGY.md` §2).
- GitHub, Hugging Face Hub/Spaces, Kaggle, portfolio site, one open-source PR (see §7).
- Apply to Sarvam AI **and** the wider Indic-AI/GenAI market where this exact skill set is scarce and valuable:
  - Krutrim (Ola's AI), Fractal AI, Gnani.ai, Slang Labs, Soket AI, Two Platforms, AI4Bharat (research collabs), and globally Hugging Face, Together AI, Mistral, Cohere — companies who will genuinely compete for someone with a shipped Indic-LLM fine-tune are a wider set than Sarvam alone.

---

## Rule for this repo
Every phase checkpoint lives in `/projects/`. If it's not in the repo, it isn't scored yet — that's what keeps the tracker honest.
