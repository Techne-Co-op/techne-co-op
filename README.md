# journal

**The CIS journal module. Book of original entry for cooperative event capture and work coordination.**

A module of the [Common Information System (CIS)](https://techne-co-op.github.io/commons/) — the cooperative accounting infrastructure of [RegenHub, LCA](https://techne-co-op.github.io/journal/), a Colorado Limited Cooperative Association built on REA (Resource-Event-Agent) accounting.

In accounting, a journal is the book of original entry: where events are first recorded before they post to accounts. This module is that layer. Members capture contributions, reflections, exchanges, and clearings here. Common Work coordinates which events are ready. Both feed into the CIS's REA engine, which posts events to member capital accounts under Subchapter K patronage accounting rules.

---

## The tools

### Daybook

A member's personal record of the day. Every entry begins private — a contribution, reflection, exchange, or clearing written by the member alone. Content stays private until the member chooses to land it, at which point it enters the cooperative's shared record. Nothing becomes public without a person deciding to put it there.

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

The Daybook and Common Work share no tables but reference each other by ID. A **Contribution** entry links a member's action to a work item. A **Clearing** entry closes a matter or resolves a work item. Together they produce the audit trail the CIS needs to post events to member capital accounts.

This module sits between member action and cooperative accounting: what you did becomes legible to the cooperative at the moment you choose, in the form the REA engine can process.

---

## Relation to CIS

The CIS is the full system — REA schema, roles, capital accounts, grant reporting, governance. This repo is one module within it: the event capture and work coordination layer. The CIS general ledger is the authoritative record; the journal is where entries originate.

See the [CIS documentation](https://techne-co-op.github.io/commons/) for the full architecture, build roadmap, and implementation plan.

---

## What's in this repo

| Path | Contents |
|---|---|
| `/` | Landing page — introduction for first-time visitors |
| `/architecture/` | Pre-implementation specification: schema, state machines, logic, invariants |
| `/design-system/` | Design System v4 — canonical tokens, components, and site application protocol |
| `/daybook/` | Daybook interface and bloom visualization |
| `/common-work/` | Common Work interface |

Live site: [techne-co-op.github.io/journal](https://techne-co-op.github.io/journal/)

---

## Built by

[Techne Studio](https://techne-co-op.github.io/journal/) — the design and engineering practice of RegenHub, LCA. Boulder, Colorado.

Part of the Common Information System · [CIS documentation](https://techne-co-op.github.io/commons/) · [Architecture spec](https://techne-co-op.github.io/journal/architecture/)
