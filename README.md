# Hi, I'm Marvin 

I'm an AI Engineer building LangGraph systems.

## What I Build

**LangGraph Lead Enrichment Pipeline**: finds the owner's name for local storefront businesses, with a source link for every name and a blank instead of a guess. Measured on a sealed holdout the code had never seen: 17 of 23 delivered names correct (74%, range 54% to 87%), about $0.045 per lead.

- **Fan-out/fan-in parallelism:** 4 concurrent Brave searches, 32s → 1.2s
- **Confidence cascades:** Cheap model first (Haiku), verify on uncertainty (Sonnet)
- **Error isolation:** Every API failure handled gracefully
- **Cost tracking:** Per-lead cost from design day 1
- **Measurement:** frozen code, hand-verified answers sealed before the run, scorer committed first

**Portfolio:** [langgraph-lead-enrichment](https://github.com/mluequee/langgraph-lead-enrichment)

## Stack

`LangGraph` · `LangChain` · `Claude (Haiku + Sonnet)` · `Python` · `SQLite` · `Brave Search API`

## Looking For

Remote AI Engineer roles. Interested in companies building with LangGraph, Claude, or LLM systems that need production thinking (error isolation, cost discipline, measurement).

---

Available for hire • [Portfolio](https://github.com/mluequee/langgraph-lead-enrichment) • Veteran • Founder @ MBG Automations
