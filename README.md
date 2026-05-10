# 🤖 AI Daily Life — by Palak Ramchandani

A collection of AI agents I'm building to automate 
my daily life. No fluff. Just real problems, 
real solutions, real results.

---

## 🧪 Experiments

| # | Agent | Problem Solved | Tools Used | Status |
|---|-------|---------------|------------|--------|
| 01 | [Podcast Summary Agent](./01-podcast-agent/) | 3hr podcasts vs 45min walks | Make.com + Claude AI + Google TTS + Gmail |  Live |
| 02 | Expense Tracker | Where does my money go? | Make.com + Claude AI + Gmail |  Building |

---

## 01 — Podcast Summary Agent

**The problem:** I started walking 45 minutes every 
evening. Wanted to learn something during that time. 
Every podcast was 2-3 hours long.

**What it does:**
- Monitors RSS feeds for new podcast episodes
- Sends each episode to Claude AI for summarization
- Converts summary to audio via Google TTS
- Emails formatted summary + MP3 every morning at 8 AM

**Cost:** ~₹2 per summary  
**Build time:** One Sunday  
**Code written:** Zero lines

### Tools
- Make.com (automation)
- Claude AI API (summarization)
- Google Cloud TTS (audio)
- Gmail (delivery)

### How to use
1. Sign up for Make.com (free)
2. Sign up for Anthropic API (console.anthropic.com)
3. Enable Google Cloud TTS API
4. Import the Make.com blueprint below
5. Add your API keys
6. Set your podcast RSS feeds
7. Schedule and activate

### Make.com Blueprint
Download and import: [podcast-agent-blueprint.json](./01-podcast-agent/blueprint.json)

---


