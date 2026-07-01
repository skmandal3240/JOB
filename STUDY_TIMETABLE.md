# Study Timetable

This is the single, authoritative week-by-week schedule — it reconciles `CURRICULUM.md` (the phases) with the certs and projects in `SARVAM_AI_APPLICATION_STRATEGY.md`. Assumes ~3–4 focused hours/day, 6 days/week; adjust up if you can go full-time.

Phases 0–2 are compressed because your CV already shows Python/JS and a Data Analytics certificate — you're verifying and proving those, not learning them from zero. Everything from Phase 4 onward is genuinely new ground and gets the real time.

| Week | Phase | Daily focus | Certs to slot in (background, ~30–60 min/day) | Checkpoint due at end of week |
|---|---|---|---|---|
| **1** | Phase 0 + 1 (Foundations + DSA) | Solve DSA problems, refresh Python fundamentals, Git/GitHub hygiene | Start Anthropic Academy Developer track | 20 foundational problems + 30 DSA problems pushed to `/projects/phase0-foundations/` and `/projects/phase1-dsa/` |
| **2** | Phase 2 + 3 (Python for Data + Classical ML) | Pandas/NumPy data-analysis notebook, then a classical ML model (regression/classification) | Finish Anthropic Academy; Google Cloud Skills Boost (4 short courses); NVIDIA "Generative AI Explained"; IBM SkillsBuild GenAI Fundamentals | Data-analysis notebook + a Kaggle notebook/competition entry in `/projects/phase2-data-analysis/` and `/projects/phase3-classical-ml/` |
| **3** | Phase 4 (Deep Learning + PyTorch), part 1 | fast.ai lessons 1–3, train a small neural net from scratch in PyTorch | Kaggle Learn "Intro to Deep Learning" | Working from-scratch net, results logged |
| **4** | Phase 4, part 2 | fast.ai remaining lessons, fine-tune a pretrained vision/text model with PyTorch | Hugging Face NLP Course, intro chapters | Fine-tuned model + README in `/projects/phase4-deep-learning/` |
| **5** | Phase 5, Project 1 | Indic-language LoRA fine-tune — pick model/dataset, get a rough training run working, then clean it up | Hugging Face NLP Course, remaining chapters | Fine-tuned model + eval numbers pushed to GitHub, model + demo Space on Hugging Face Hub |
| **6** | Phase 5, Project 2 | Local/rented GPU inference benchmarking — quantized models, latency/throughput numbers | — | Benchmark writeup in `/projects/phase5-gpu-benchmark/` |
| **7** | Phase 5, Project 3 | Speech/translation mini-pipeline for an Indian language, deployed on Vercel + Supabase | — | Live demo link + `/projects/phase5-speech-pipeline/` |
| **8** | Phase 6 (Portfolio + Distribution) | GitHub profile polish, portfolio site, one open-source PR to AI4Bharat/Hugging Face `transformers`, short blog post per project | Kaggle Learn micro-courses if not done yet | All external links filled into `SKILL_TRACKER.md`'s "External Evidence" section; start applying |

**Total: ~8 weeks** to go from today's 25/100 to genuinely interview-ready. This supersedes the looser "6-week" estimate in `SARVAM_AI_APPLICATION_STRATEGY.md` §6 — that version skipped straight to Phase 5 assuming fundamentals were already solid; this version proves that first.

---

## Suggested daily rhythm (3–4 hrs/day)
1. **~45–60 min** — course/certificate material for the week.
2. **~2–2.5 hrs** — hands-on coding on that week's checkpoint. This is the block that actually moves your score.
3. **~15–20 min** — commit and push whatever you did today, even if unfinished. Small, frequent commits are better evidence than one big dump at the end of the week.
4. **1 rest day/week** — sustainable pace beats a burnout sprint; an 8-week plan only works if you actually run all 8 weeks.

## How this connects to the rest of the system
- Progress is scored in `SKILL_TRACKER.md` against whatever's actually in `/projects/` — not against this timetable. Running ahead or behind schedule is fine; what's committed is what counts.
- The recurring check-in (every 3 days) reads the repo and tells you where you stand against this timetable and what to do next.
