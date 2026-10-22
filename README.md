# Darren Foote — tape archive

**Data Analyst | Business Analyst — Python · SQL · Power BI · Salesforce CRM**
Owings Mills, Maryland · UMBC Information Systems (B.S., May 2026)

I build systems that keep receipts on themselves — and publish what the receipts say, including when it's unflattering.

**Portfolio:** [darren-dev141.github.io](https://darren-dev141.github.io/) · **LinkedIn:** [linkedin.com/in/darren-foote-jr](https://www.linkedin.com/in/darren-foote-jr/) · 📫 [darrenfootejr@outlook.com](mailto:darrenfootejr@outlook.com)

---

## FR-001 — Field Recording №1

### [Composed from AI chain of thought](https://darren-dev141.github.io/field-recording-001.html)

One day of machine logs — a decision engine, a router, a failure database, an audit — arranged as verbatim excerpts only. Nothing paraphrased, nothing invented; every excerpt names its source file.

From the tape:

> Receipts for Oct 22: 715 calls — 611 were the system's own local test traffic. […] the OpenCode Go leader lane served ZERO and appeared only as a 429 GoUsageLimitError.
> — failure-db/failures.jsonl, F-20261022-06

> Hard-confirmed live: 22 of 62 · NOT LIVE: 12 · UNPROVEN: 27
> — the feed, audited against employers' own open-jobs lists

## The machines on the tape

- **Laya + Divergence Guard** — a local decision server with **11,192 logged decisions**. It reproduces the calls its operator accepted — and re-asserts the ones he rejected **96.5%** of the time. The guard exists to catch it doing that: **182 flags** raised on real history. *(Running locally)*
- **QD-Rec** — a quality-diversity recommender that writes judged hypotheses about research papers. First run: **240-paper pool → archive of 34**, 24/24 evaluations, each entry with a plain-language judged hypothesis. *(First run complete)*
- **[JobLens](https://github.com/Darren-dev141/joblens)** — is this job posting still real? Follows each listing back to the employer's own site and records a working apply path, a dead posting, or an honest "couldn't verify." [Live demo](https://darren-dev141.github.io/joblens/) · Python · vanilla HTML/CSS/JavaScript
- **Switchboard / Omnirouter** — a local router for AI traffic with **a receipt on every call**: model requested vs. model served, fallbacks, errors. Embeddings lane live; router suite **100 tests green**. The claim is the receipts, not the health check. *(Running locally)*

## Oct 22 — Falsification Day

One day spent trying to prove my own systems wrong, with the hardest test available for each:

- **My job feed:** 62 postings labeled "verified live," re-checked against each employer's own open-jobs list → **22 confirmed, 12 dead, 2 with wrong details, 27 unproven**. Fixed the same day.
- **My application ledger:** 194 recorded applications checked against employer email → **166 proven, 26 already rejected** while my records showed them open. Corrected the same day.
- **My router:** "up" meant the process, not the lanes. The receipts showed the leader lane at zero serves.

Every number on this page traces to a log, a report, or a live check. Unverified means unverified.

## Earlier projects

- **[digit-recognizer-android](https://github.com/Darren-dev141/digit-recognizer-android)** — Android app that recognizes handwritten digits on-device with TensorFlow Lite
- **[face-censor](https://github.com/Darren-dev141/face-censor)** — Face detection and censoring in video with OpenCV and a PyQt6 interface
- **[nlp-chatbot](https://github.com/Darren-dev141/nlp-chatbot)** — TF-IDF question-answering chatbot built with NLTK and scikit-learn
- **[news-search](https://github.com/Darren-dev141/news-search)** — Command-line article search powered by the NewsAPI
- **[stock-dashboard](https://github.com/Darren-dev141/stock-dashboard)** — Yahoo Finance data downloader with a Streamlit dashboard
- **Agent Action Auditor** — open-source tool that reviews what AI agents actually did against what they were asked to do. GitLab Transcend hackathon entry.

## Skills

Python · SQL · Java · pandas · Power BI · Salesforce CRM · Data Analysis · Data Validation · Data Automation · Excel · HTML/CSS/JavaScript · TensorFlow Lite · Streamlit · Dashboard Design · Business Analysis · Technical Writing

## Background

- **Constellation Energy** — Business Development Specialist (contract) and Quantitative Analytics intern
- **Customer operations** — Walmart · Target · Chick-fil-A
- **UMBC** — B.S. Information Systems, May 2026
