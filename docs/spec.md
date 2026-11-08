---
tags: [flagship, finance, learning, ai, paper-trading, india]
aliases: [Paper, Paper Trading, Stock Learning, Stock Market Learning]
created: 2026-06-26
status: solid
---

# Paper — Learn Markets by Paper Trading

> **Status:** ✅ Solid spec. Ready to build.
> **Platform:** Web (Next.js) + Mobile responsive
> **Stack:** Next.js + SQLite + AI (BYOK or built-in)
> **Effort:** ~58 hours full, ~25 hours MVP

---

## The Story

You want to learn stocks but every resource overwhelms you. No clear path. No prerequisites mapped. You don't even know the difference between a stock and a share. Index funds make sense, but the algorithmic itch says "can't I build something with AI?"

**Paper is a learning project.** Not a product for market. Build to learn, ground knowledge with features.

**The insight:** Every feature teaches a concept. Build the feature → learn the concept → knowledge is permanent.

**Inspired by:**
- SmartBulls (Indian paper trading)
- Neostock (Indian market practice)
- Khan Academy's mastery learning

---

## The Problem

**Financial literacy is hard because:**
- No structured path from "what is a stock" to "options trading"
- Every resource assumes prior knowledge
- No safe practice environment (real money = real fear)
- No feedback loop → you don't know what you don't know

**Why this is a learning project:**
- You'll understand markets by building a trading app
- Every feature requires learning the domain
- Open source when done — no monetization pressure

---

## The Solution

**Paper = Learn by building + Practice with virtual money**

1. **Structured learning path** — Basics → Intermediate → Advanced
2. **Virtual ₹1L** — Practice without real money
3. **Educational overlays** — Every screen teaches something
4. **AI chat** — Ask questions about concepts (BYOK or built-in)
5. **Paper trading** — Virtual trades with real market data

---

## Architecture

```
┌─────────────────────────────────────────────────────────────┐
│                    PAPER ECOSYSTEM                           │
│                                                              │
│  ┌────────────────────────────────────────────────────────┐ │
│  │  WEB APP (Next.js)                                     │ │
│  │  - Learning path (structured curriculum)               │ │
│  │  - Paper trading (virtual ₹1L)                         │ │
│  │  - Portfolio view                                      │ │
│  │  - AI chat for concepts                                │ │
│  │  - Educational overlays                                │ │
│  └──────────────────────┬─────────────────────────────────┘ │
│                         │                                    │
│  ┌──────────────────────┴─────────────────────────────────┐ │
│  │  BACKEND (SQLite + APIs)                               │ │
│  │  - User progress tracking                              │ │
│  │  - Virtual portfolio                                   │ │
│  │  - Market data (Yahoo Finance / Alpha Vantage)         │ │
│  │  - AI integration (BYOK)                               │ │
│  └──────────────────────────────────────────────────────  │ │
└─────────────────────────────────────────────────────────────┘
```

---

## Features

### P0 — MVP (~25h)

1. **Virtual ₹1L** — Start with virtual money, practice trading
2. **Basic learning path** — "What is a stock?" → "How to read a chart?"
3. **Paper trading** — Buy/sell with real market data
4. **Portfolio view** — See your virtual holdings
5. **Educational overlays** — Tooltips explaining every term

### P1 — Learning Path (~20h)

6. **Structured curriculum** — Basics → Intermediate → Advanced
7. **Quizzes** — Test your understanding
8. **Progress tracking** — What you've learned, what's next
9. **AI chat** — Ask questions about concepts

### P2 — Advanced (~13h)

10. **Technical indicators** — RSI, MACD, Moving Averages
11. **Backtesting** — Test strategies on historical data
12. **Options basics** — What are calls and puts

---

## Learning Path

### Phase 1: Foundations
- What is a stock vs share?
- What is an index (Nifty, Sensex)?
- What is a mutual fund?
- What is SIP?
- Risk and diversification

### Phase 2: Intermediate
- How to read a chart?
- What are technical indicators?
- What is fundamental analysis?
- What is a P/E ratio?
- What is market cap?

### Phase 3: Advanced
- What are options?
- What is futures trading?
- What is short selling?
- Portfolio allocation
- Tax implications (Indian)

---

## Monetization

**None.** This is a learning project. Open source when done.

---

## Worth Assessment

| Dimension | Score | Notes |
|-----------|-------|-------|
| Portfolio value | 7/10 | Learning project, not a product |
| Learning value | 10/10 | You'll learn finance by building |
| Market/user value | 5/10 | Not for market, for learning |
| Personal value | 9/10 | Financial literacy is essential |

---

## Dependencies

- **Paisa** — Uses PSF format for trade data (optional)

---

## Quality Markers

- [ ] Virtual ₹1L works
- [ ] Paper trading with real market data
- [ ] Learning path is structured
- [ ] Educational overlays explain concepts
- [ ] AI chat answers questions
- [ ] Portfolio view shows holdings

---

**Build fifth.** Depends on Paisa for data format. Learning-first approach.
