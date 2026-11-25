<!-- styled:v2 -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1d1726,50:167dfe,100:9533fa&height=180&section=header&text=CaseFlow%3A%20Law%20Firm%20Intake%20%26%20Case%20Pipeline&fontSize=25&fontColor=ffffff&fontAlignY=36&desc=Case%20study%20%E2%80%A2%20Legal%20%E2%80%A2%20Intake%20pipeline%20dashboard&descAlignY=58&descSize=16&animation=fadeIn" width="100%" alt="CaseFlow: Law Firm Intake & Case Pipeline" />

**A React dashboard that follows every lead from first contact to signed case, with live intake KPIs and a pipeline board by stage and owner.**

<p>
  <img src="https://img.shields.io/badge/Legal-167dfe?style=flat-square" alt="Legal" />
  <img src="https://img.shields.io/badge/Intake%20pipeline%20dashboard-9533fa?style=flat-square" alt="Intake pipeline dashboard" />
  <img src="https://img.shields.io/badge/React-231f20?style=flat-square" alt="React" />
  <img src="https://img.shields.io/badge/Node.js-231f20?style=flat-square" alt="Node.js" />
  <img src="https://img.shields.io/badge/Python-231f20?style=flat-square" alt="Python" />
  <img src="https://img.shields.io/badge/Clio%20API-231f20?style=flat-square" alt="Clio API" />
  <img src="https://img.shields.io/badge/n8n-231f20?style=flat-square" alt="n8n" />
  <img src="https://img.shields.io/badge/Supabase-231f20?style=flat-square" alt="Supabase" />
</p>

<p>
  <a href="#overview">Overview</a> ·
  <a href="#key-features">Key features</a> ·
  <a href="#results">Results</a> ·
  <a href="#tech-stack">Tech stack</a>
</p>

</div>

---

![CaseFlow intake pipeline: new leads, consults booked, signed cases and conversion, with a pipeline board from new lead to signed.](assets/cover.webp)

## Overview

Partners had no single view of new leads, consultations and signed cases, so intake numbers lived in spreadsheets. Lexvaxa built CaseFlow, a custom web dashboard connected to the firm's case data through the Clio API. It shows live KPIs for new leads, consults booked, signed cases and conversion rate, the weekly trend of leads against signed cases, cases by practice area and lead source, and a pipeline board by stage and owner. Screens shown use sample data, so no client records are exposed.

## The challenge

Intake performance was only visible in month-end spreadsheets, too late to act on.

## The solution

n8n syncs leads and matters from Clio and other sources into Supabase, and a React app shows the pipeline and conversion numbers live, with OpenAI tagging lead details.

## Key features

- Live KPIs: new leads, consults, signed cases, conversion
- Pipeline board from new lead to signed
- Weekly leads against signed cases
- Cases by practice area and lead source
- Pipeline table by stage and owner
- Urgency and status tags on each lead

## Results

- Partners see intake performance live and act on it the same day

## Tech stack

![React](https://img.shields.io/badge/React-1d1726?style=for-the-badge) ![Node.js](https://img.shields.io/badge/Node.js-1d1726?style=for-the-badge) ![Python](https://img.shields.io/badge/Python-1d1726?style=for-the-badge) ![Clio API](https://img.shields.io/badge/Clio%20API-1d1726?style=for-the-badge) ![n8n](https://img.shields.io/badge/n8n-1d1726?style=for-the-badge) ![Supabase](https://img.shields.io/badge/Supabase-1d1726?style=for-the-badge) ![OpenAI](https://img.shields.io/badge/OpenAI-1d1726?style=for-the-badge)

## Demo

A working version of the dashboard UI with **sample data** is in [`demo/index.html`](demo/index.html). Download it and open it in a browser; it has no build step.

## Privacy

Client names and records are confidential. Every screen in this repository uses sample data, and source code that belongs to the client is not published.

## Links

- Case study on Lexvaxa: https://lexvaxa.com/work/law-firm-intake-case-pipeline

---

<div align="center">

**Built by [Ch Muhammad Samiullah](https://github.com/samiullah156-creator)** · AI Automation Engineer and Full-Stack Developer at [Lexvaxa](https://lexvaxa.com)

<a href="https://github.com/samiullah156-creator"><img src="https://img.shields.io/badge/More%20projects-181717?style=for-the-badge&logo=github&logoColor=white" alt="More projects" /></a>
<a href="https://lexvaxa.com/contact"><img src="https://img.shields.io/badge/Work%20with%20me-167dfe?style=for-the-badge&logo=googlecalendar&logoColor=white" alt="Work with me" /></a>
<a href="https://www.linkedin.com/in/sami-lexvaxa/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>

<sub>⭐ Star this repo if you found it useful</sub>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:9533fa,50:167dfe,100:1d1726&height=110&section=footer" width="100%" alt="" />
