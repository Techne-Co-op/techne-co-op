# ledger

**Shared work, made legible.**

A cooperative accounting infrastructure for [RegenHub, LCA](https://techne-co-op.github.io/ledger/) — a Colorado Limited Cooperative Association. Two tools that together form the member-held record from which patronage accounting flows.

---

## The tools

### Daybook

A member's personal record of the day. Every contribution, reflection, exchange, or clearing begins private. Content stays private until the member chooses to land it — at which point it enters the cooperative's shared record. Nothing becomes public without a person deciding to put it there.

The Daybook renders the cooperative's activity as a **bloom**: a clock face where each petal sits at the hour it was made public, in the color of its kind. The bloom shows *when* and *how often* — never *what*. Solid petals are public entries; outline petals are open matters still waiting to land.

Entry kinds:
- **Reflection** — witness and perception; open to observers
- **Contribution** — labor, skill, or resource given; the primary input for patronage accounting
- **Exchange** — goods or services traded between members or with the outside world
- **Clearing** — settlement of a debt, credit, or obligation; closes open matters

### Common Work

The cooperative's shared view of what everyone is working on. Work items move through a defined lifecycle — captured, offered, held, standing, socialized, resolved — with each stage requiring specific actors and conditions. The arc from captured to resolved mirrors the sunset sweep: warm at first notice, cooling toward settlement.

Nothing resolves without a named human performing that action. Agents prepare; people land.

---

## How they connect

The Daybook and Common Work share no tables but reference each other by ID. A **Contribution** entry links a member's action to a work item. A **Clearing** entry closes a matter or resolves a work item. Together they produce the audit trail required for patronage accounting under Subchapter K and RegenHub's member capital account rules.

This is the ledger: the cooperative's authoritative record of who did what, when, and by whose decision it became permanent.

---

## What's in this repo

| Path | Contents |
|---|---|
| `/` | Landing page — introduction for first-time visitors |
| `/architecture/` | Pre-implementation specification: schema, state machines, logic, invariants |
| `/design-system/` | Design System v4 — canonical tokens, components, and site application protocol |
| `/daybook/` | Daybook interface and bloom visualization |
| `/common-work/` | Common Work interface |

Live site: [techne-co-op.github.io/ledger](https://techne-co-op.github.io/ledger/)

---

## Built by

[Techne Studio](https://techne-co-op.github.io/ledger/) — the design and engineering practice of RegenHub, LCA. Boulder, Colorado.

Design System v4 · [Architecture spec](https://techne-co-op.github.io/ledger/architecture/) · Pre-implementation
