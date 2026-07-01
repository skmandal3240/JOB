# AI Engineer Curriculum: Beginner → Job-Ready

Goal: go from wherever you actually are today to a skill level that top AI companies (Sarvam AI and peers) recruit for, with every step verifiable — not self-reported.

## How this system works
1. **Phases below**, each with free resources (courses + YouTube) and a **checkpoint** (something you build/solve/ship).
2. Every checkpoint gets pushed as real code into `/projects/<phase>-<name>/` **in this same repo** — that's what makes progress checkable instead of just claimed.
3. `SKILL_TRACKER.md` is the scorecard. It only moves when there's a commit, a link, or a certificate to point at.
4. A recurring check-in re-reads this repo, updates the tracker, and hands you the next concrete task.
5. Day-by-day scheduling of all of this lives in `STUDY_TIMETABLE.md` — this file is "what to learn and where," that file is "when."

This is a genuine fresh start, per your request — no phase is skipped or fast-tracked because of your CV or degree. Your CV/certificate still stand as real, honest history for the resume itself — they just don't buy you a shortcut here.

**How to use the resource lists:** you don't need every link in a phase — pick the course *or* the video series that clicks for you, and use the other as backup if you get stuck on a concept. Watching a video and doing the exercises beats watching without doing every time.

---

## Phase 0 — Programming Foundations (done fully, start to finish)
**Learn:** what a program is, variables, data types, control flow (if/loops), functions, basic recursion, Git/GitHub basics (clone, add, commit, push, branch).

**Courses:**
- [CS50x — Harvard's Introduction to Computer Science](https://cs50.harvard.edu/x/) (edX, free) — the gold-standard fundamentals course, do the actual lectures + problem sets.
- [freeCodeCamp — Scientific Computing with Python](https://www.freecodecamp.org/learn/scientific-computing-with-python/) (free, certificate on completion).

**YouTube:**
- [CS50 full 2026 lecture series (CS50 channel)](https://www.youtube.com/@cs50) — same course as above, in video form.
- [freeCodeCamp.org — "Learn Python - Full Course for Beginners"](https://www.youtube.com/@freecodecamp) (search this title on the channel) — good if you want a single long-form Python walkthrough.
- [Git & GitHub for Beginners (freeCodeCamp)](https://www.youtube.com/@freecodecamp) — search "Git and GitHub for Beginners" on the channel.

**Checkpoint:** 20 solved problems (arrays, strings, hashmaps) pushed to `/projects/phase0-foundations/`, each with a one-line comment on what it does and why your approach works.

---

## Phase 1 — Data Structures & Algorithms
**Learn:** arrays, linked lists, trees, graphs, complexity analysis (Big-O).

**Courses:**
- [NeetCode 150](https://neetcode.io/practice) (free curated problem list, maps to real interview questions).
- [CS50](https://cs50.harvard.edu/x/) (later weeks cover data structures).

**YouTube:**
- [NeetCode channel](https://www.youtube.com/@NeetCode) — clean, short explain-and-solve videos for almost every common DSA problem; use this whenever you're stuck on a NeetCode 150 problem.
- [Abdul Bari — Algorithms playlist](https://www.youtube.com/@abdul_bari) — one of the most respected DSA/algorithms teachers on YouTube, especially strong on Big-O and core algorithms.

**Checkpoint:** 50 solved problems + a short written Big-O explanation for 5 of them, in `/projects/phase1-dsa/`. Also do this on [HackerRank](https://www.hackerrank.com/) (your public profile is tracked evidence — see `SKILL_TRACKER.md`).

---

## Phase 2 — Python for Data & ML
**Learn:** Pandas, NumPy, OOP in Python, matplotlib/plotting.

**Courses:**
- [Kaggle Learn — "Python"](https://www.kaggle.com/learn/python) and [Kaggle Learn — "Pandas"](https://www.kaggle.com/learn/pandas) (free, instant certificate).

**YouTube:**
- [Corey Schafer — Pandas tutorial playlist](https://www.youtube.com/@coreyms) — widely regarded as the clearest Pandas walkthroughs available.
- [Corey Schafer — NumPy tutorial](https://www.youtube.com/@coreyms).

**Checkpoint:** a real data-analysis notebook (use your Data Analytics certificate skills on a public dataset) in `/projects/phase2-data-analysis/`.

---

## Phase 3 — Classical Machine Learning
**Learn:** regression, classification, train/test splits, evaluation metrics, overfitting.

**Courses:**
- [Kaggle Learn — "Intro to Machine Learning"](https://www.kaggle.com/learn/intro-to-machine-learning) (free).
- [Andrew Ng's Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction) (Coursera, audit free).

**YouTube:**
- [StatQuest with Josh Starmer](https://www.youtube.com/@statquest) — the best available intuition-first explanations of regression, classification, decision trees, and evaluation metrics; watch before you code each concept.
- [Krish Naik — Machine Learning playlist](https://www.youtube.com/@krishnaik06) — practical, code-along ML tutorials, very popular for exactly this stage.
- [DeepLearning.AI channel](https://www.youtube.com/@Deeplearningai) — official companion videos for Andrew Ng's course.

**Checkpoint:** a Kaggle notebook or competition entry in `/projects/phase3-classical-ml/`.

---

## Phase 4 — Deep Learning & PyTorch
**Learn:** neural nets from scratch, backprop intuition, PyTorch basics, transfer learning.

**Courses:**
- [fast.ai — Practical Deep Learning for Coders](https://course.fast.ai/) (free, project-first approach).
- [Hugging Face NLP Course — intro chapters](https://huggingface.co/learn/nlp-course) (free).

**YouTube:**
- [3Blue1Brown — Neural Networks playlist](https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi) — the best visual/intuitive explanation of what a neural net and backpropagation actually do. Watch this before touching PyTorch code.
- [freeCodeCamp — "PyTorch for Deep Learning & Machine Learning – Full Course" (Daniel Bourke)](https://www.youtube.com/watch?v=Z_ikDlimN6A) — a genuinely full, free, hands-on PyTorch course, ~25 hours, code-along.
- [fast.ai official course videos](https://www.youtube.com/@fastdotai) — paired with the course above.

**Checkpoint:** train a small net from scratch, then fine-tune a pretrained model with PyTorch — `/projects/phase4-deep-learning/`.

---

## Phase 5 — LLMs, Fine-Tuning & Indic NLP (your specialization for Sarvam)
**Learn:** transformers, LoRA/QLoRA fine-tuning, tokenization for Indian scripts, quantized inference.

**Courses:**
- [Hugging Face NLP Course (full)](https://huggingface.co/learn/nlp-course).
- [Anthropic Academy — Developer track](https://anthropic.skilljar.com/) (free, official certificate).
- [AI4Bharat](https://ai4bharat.iitm.ac.in/) — datasets and open models for Indic languages.

**YouTube:**
- [Andrej Karpathy — "Neural Networks: Zero to Hero" playlist](https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ) — builds a GPT-like model from scratch, line by line; the single best resource on the internet for actually understanding transformers instead of just using them.
- [Andrej Karpathy — "Let's build GPT: from scratch, in code, spelled out"](https://www.youtube.com/watch?v=kCc8FmEb1nY) — the specific video for transformer/attention internals.
- [Umar Jamil — LLM/attention/LoRA implementation videos](https://www.youtube.com/@umarjamilai) — detailed from-scratch walkthroughs of attention, LoRA, and fine-tuning, code included.
- [Hugging Face official channel](https://www.youtube.com/@HuggingFace) — fine-tuning and `transformers`/`peft` tutorials straight from the library maintainers.

**Checkpoints (these are the 3 projects from the application strategy doc):**
1. Indic-language LoRA fine-tune — `/projects/phase5-indic-finetune/`.
2. Local/rented GPU inference benchmark — `/projects/phase5-gpu-benchmark/`.
3. Speech/translation mini-pipeline for an Indian language — `/projects/phase5-speech-pipeline/`.

---

## Phase 6 — Portfolio, Certifications & Distribution
- Free certifications with direct links — see `SARVAM_AI_APPLICATION_STRATEGY.md` §2.
- Build presence on: [GitHub](https://github.com/), [Hugging Face Hub/Spaces](https://huggingface.co/spaces), [Kaggle](https://www.kaggle.com/), a portfolio site on [Vercel](https://vercel.com/); one open-source PR (see §6 of the strategy doc for the full showcase priority order).
- Apply to Sarvam AI **and** the wider Indic-AI/GenAI market where this exact skill set is scarce and valuable: Krutrim (Ola's AI), Fractal AI, Gnani.ai, Slang Labs, Soket AI, Two Platforms, AI4Bharat (research collabs), and globally Hugging Face, Together AI, Mistral, Cohere.

**YouTube:**
- [freeCodeCamp — GitHub portfolio/README tutorials](https://www.youtube.com/@freecodecamp) — search "GitHub profile README" for guides on making your GitHub the first thing recruiters see clearly.

---

## Rule for this repo
Every phase checkpoint lives in `/projects/`. If it's not in the repo, it isn't scored yet — that's what keeps the tracker honest. Day-by-day timing for all of the above: `STUDY_TIMETABLE.md`. Extra YouTube channels, GitHub repos to star, stretch project ideas, and your Google Drive bundles (DSA/interview kits): `RESOURCE_LIBRARY.md`.
