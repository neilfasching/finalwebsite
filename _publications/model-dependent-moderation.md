---
title: "Model-Dependent Moderation: Inconsistencies in Hate Speech Detection Across LLM-based Systems"
collection: publications
category: manuscripts
permalink: /publication/model-dependent-moderation
#excerpt: 'Inconsistencies in Hate Speech Detection Across 7 LLM-based Systems.'
date: 2025-07-25
venue: 'Association for Computational Linguistics'
paperurl: 'https://www.neilfasching.com/files/fasching-model-moderation.pdf'
citation: '<b>Fasching, Neil</b> and Lelkes, Yphtach. (2025). &quot;Model-Dependent Moderation: Inconsistencies in Hate Speech Detection Across LLM-based Systems.&quot; <i>Findings of the Association for Computational Linguistics</i>. pages 22271–22285.'
---

**Abstract:** Content moderation systems powered by large language models (LLMs) are increasingly deployed to detect hate speech; however, no systematic comparison exists between different systems. If different systems produce different outcomes for the same content, it undermines consistency and predictability, leading to moderation decisions that appear arbitrary or unfair. Analyzing seven leading models—dedicated Moderation Endpoints (OpenAI, Mistral), frontier LLMs (Claude 3.5 Sonnet, GPT-4o, Mistral Large, DeepSeek V3), and specialized content moderation APIs (Google Perspective API)—we demonstrate that moderation system choice fundamentally determines hate speech classification outcomes. Using a novel synthetic dataset of 1.3+ million sentences from a factorial design, we find identical content receives markedly different classification values across systems, with variations especially pronounced for specific demographic groups. Analysis across 125 distinct groups reveals these divergences reflect systematic differences in how models establish decision boundaries around harmful content, highlighting significant implications for automated content moderation.