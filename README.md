# 3LOCK Firewall

**Author:** David Wise (ROOT 0)  
**Version:** 0.07  
**License:** Open Evolution — see below  

> Keeps the internet out. Keeps your data in. Both by consent.

---

## What this is

A consent-driven firewall model with two independent gates:

| Gate | Name | Controls |
|------|------|----------|
| **KARSA** | Internet gate | Inbound — internet allowed in only when explicitly opened |
| **ICURIAM** | Data gate | Outbound — your data released only when explicitly opened |

Both gates are **closed by default**. The seal only opens when you open both. No implicit consent. No defaults that leak.

The system runs in three operational modes:

| Mode | Units active | Crystal freq |
|------|-------------|-------------|
| **3/3 FULL** | 21/21 | 195.000 Hz |
| **2/3 FIELD** | 14/21 | 195.000 Hz |
| **1/3 SURVIVAL** | 7/21 | 65.000 Hz |

---

## Architecture — 5 layers

```
1/5  Logic      — 4 cubi + 1 cortex = logical cubit
2/5  Cortex     — reasoning layer
3/5  God Egg    — origin isolation
4/5  Integration — cross-layer coherence
5/5  Copper     — physical substrate (crystal-locked at FUSE)
```

**FUSE 5/5** locks all layers to the crystal substrate. Maximum coherence, maximum isolation.

---

## Open Evolution

This is not a closed standard. The version increments by +0.01 for each public derivation:

```
0.00  ROOT 0 — David Wise — 4+1 concept
0.01  + God Egg
0.02  + Consent
0.03  + Field Mode
0.04  + Boron/O₂/Plasma
0.05  + Crystal
0.06  + Copper
0.07  + Karsa/Icuriam     ← current
0.08  your derivation here
```

**Rule:** ROOT 0 stays David Wise. Derivatives add +0.01 and credit their contribution. Knowledge evolves through derivation, not replacement.

To derive: fork this repo, make your addition, increment the version in `index.html`, open a PR.

---

## Run

Open `index.html` in any browser. No server, no build, no dependencies.

State is saved to `localStorage` — your gate settings persist across sessions.

---

## Key distinctions

- **Not binary** — three modes (FULL / FIELD / SURVIVAL), not on/off
- **Dual gate** — KARSA and ICURIAM are independent. Opening one doesn't open the other
- **Consent-first** — both closed by default. You must explicitly open each gate
- **Versioned evolution** — not a closed spec. Derivatives are tracked and numbered
