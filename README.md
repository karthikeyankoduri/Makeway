# Makeway
AI-Powered Business Launch Automation (n8n + Zapier)

This project is an end-to-end AI automation pipeline that takes a raw business idea from a chat interface and automatically generates marketing content, competitor insights, and a deployable website — all with minimal human intervention.

Built using n8n, LLM-based agents, Zapier webhooks, GitHub, and Netlify, the system demonstrates how autonomous agents can collaborate in parallel to accelerate digital business launches.

🧠 How It Works

User Input (Chat Interface)

The user submits a business idea through a conversational interface.

Router Agent

Refines and structures the input prompt.

Routes the optimized prompt to multiple specialized agents in parallel.

Marketing Agent

Generates:

SEO-optimized captions

Relevant hashtags

AI-generated images aligned with the business niche

Automatically publishes content to:

Instagram

LinkedIn

Twitter (X)

Competitor Analysis Agent

Scrapes publicly available web data.

Identifies the top 5 competitors in the given business domain.

Extracts design and content patterns for inspiration.

Website Builder Agent

Generates static website code inspired by competitor analysis.

Produces production-ready HTML/CSS/JS.

Automation & Deployment

Marketing assets are sent to Zapier via webhook for platform posting.

Website code is sent to another Zapier webhook:

Creates files in a GitHub repository

Triggers Netlify for automatic deployment

⚙️ Tech Stack

n8n – Workflow orchestration & automation

LLMs / AI Agents – Prompt refinement, content generation, analysis

Zapier – Cross-platform automation via webhooks

GitHub – Version control & code storage

Netlify – Continuous deployment for static websites

Web Scraping – Competitor discovery & analysis
