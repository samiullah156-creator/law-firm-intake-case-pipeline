# CaseFlow: Law Firm Intake & Case Pipeline

**A React dashboard that follows every lead from first contact to signed case, with live intake KPIs and a pipeline board by stage and owner.**

![Legal](https://img.shields.io/badge/Legal-167dfe?style=flat-square) ![Intake pipeline dashboard](https://img.shields.io/badge/Intake%20pipeline%20dashboard-9533fa?style=flat-square) ![React](https://img.shields.io/badge/React-231f20?style=flat-square) ![Node.js](https://img.shields.io/badge/Node.js-231f20?style=flat-square) ![Python](https://img.shields.io/badge/Python-231f20?style=flat-square) ![Clio API](https://img.shields.io/badge/Clio%20API-231f20?style=flat-square) ![n8n](https://img.shields.io/badge/n8n-231f20?style=flat-square) ![Supabase](https://img.shields.io/badge/Supabase-231f20?style=flat-square)

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

React · Node.js · Python · Clio API · n8n · Supabase · OpenAI

## Demo

A working version of the dashboard UI with **sample data** is in [`demo/index.html`](demo/index.html). Download it and open it in a browser; it has no build step.

## Privacy

Client names and records are confidential. Every screen in this repository uses sample data, and source code that belongs to the client is not published.

## Links

- Case study on Lexvaxa: https://lexvaxa.com/work/law-firm-intake-case-pipeline
- Built by **Ch Muhammad Samiullah** ([GitHub](https://github.com/samiullah156-creator)) at [Lexvaxa](https://lexvaxa.com)
