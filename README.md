# NVIDIA Cert Tracker

Interactive dashboard for tracking progress through NVIDIA's AI certification path. Built for a 6-week study plan covering NCA-AIIO and NCA-GENL.

> **Try it on Perplexity Computer:** [NVIDIA AI Certification Study](https://www.perplexity.ai/computer/tasks/nvidia-ai-certification-study-jGsllbvLQiiP1u.k1iq03A?view=thread#3)

## Certifications

| Cert | Full Name | Timeline | Cost |
|------|-----------|----------|------|
| **NCA-AIIO** | AI Infrastructure & Operations Associate | Weeks 1–2 | $135 |
| **NCA-GENL** | Generative AI LLMs Associate | Weeks 3–6 | $135 |

## Features

- **Progress dashboard** — KPI cards for overall progress, current focus, days until exam, study hours, and practice scores
- **6-week timeline** — visual progress bar across the full study plan
- **Domain breakdown** — per-certification domain weights with completion tracking
- **Task checklists** — 42 pre-loaded study tasks from the study plan, organized by week
- **Practice score tracker** — log mock exam scores, chart progress against pass targets
- **Study log** — track time spent per certification with bar charts
- **Resource library** — filterable table of study resources (Udemy courses, freeCodeCamp, NVIDIA DLI, docs)
- **Dark mode** with NVIDIA green (#76B900) accent

## Study Resources

### NCA-AIIO
- Udemy video course (Ashish Prajapati) — 4h 40m, 72 lectures
- Udemy practice exams — 100 questions
- freeCodeCamp 4-hour course (Andrew Brown)
- NVIDIA Academy course + exam bundle

### NCA-GENL
- NVIDIA DLI recommended courses
- Coursera 6-course specialization
- RAPIDS (cuDF/cuML) documentation

## Stack

```
frontend     react · vite · tailwindcss
data         local storage (browser-persisted)
design       nvidia green (#76B900) · dark mode default
```

## License

Apache 2.0
