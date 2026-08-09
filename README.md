# Jose Manuel Molina Vargas

**Full-stack engineer.** I build platforms end to end — data model, API, deploy —
and I go one layer down when the abstraction starts lying to me.

Founder of [GetDevTools](https://getdevtools.com) · Arequipa, Peru

---

## Axioma

**[JOSEDOWSKI/axioma](https://github.com/JOSEDOWSKI/axioma)** · `Go` · MIT

A versioned requirements chain for AI coding agents, built on top of
[gentle-ai](https://github.com/Gentleman-Programming/gentle-ai).

An agent writes code faster than any human reviews it. The bottleneck stops
being *writing* and becomes *knowing what had to be written* — and being able to
prove afterwards that this is what got written. A requirement that lives in a
chat log doesn't exist: it isn't versioned, isn't reviewed, and can't be checked
against the code that supposedly implements it.

Axioma puts five versioned phases in front of the SDD flow:

```
charter ─▶ requirements ─▶ mockups ─▶ SDD ─▶ validation
```

Two design decisions hold up everything else:

- **Phase state is derived from disk by the tool, not declared by the agent.**
  An agent claiming "phase 2 is done" doesn't move the board. The files in
  `docs/` move the board.
- **Nobody signs off their own work.** Validation runs through four separate
  role filters, and a filter is never passed by loosening the filter. The
  validator succeeds when it rejects.

Requirements are documented in both directions with the same format: forward
from the charter for a new system, and backward from the code by reverse
engineering for one that already exists.

---

## Also worth a look

**[lenovo-fan-monitor](https://github.com/JOSEDOWSKI/lenovo-fan-monitor)** · `Shell`
Reads fan RPM straight from the embedded controller registers on Lenovo LOQ /
IdeaPad laptops — hardware where `hwmon` and `lm-sensors` report no fan data at
all. When the standard interface has no answer, go down a layer and read the
metal.

**[lenovo-fan-control](https://github.com/JOSEDOWSKI/lenovo-fan-control)**
<!-- FILL: one line. What does it control, and what did you have to figure out
     to make it work? -->

**[certificaciones-idema](https://github.com/JOSEDOWSKI/certificaciones-idema)** · `HTML`
<!-- FILL: one line. Does it issue certificates, verify them, or both? Who uses it? -->

---

## Stack

**Backend** — NestJS · Python · PostgreSQL
**Frontend** — Next.js · TypeScript
**Infra** — Docker · Go

---

## Reach me

- Web — [getdevtools.com](https://getdevtools.com)
<!-- FILL: add email / LinkedIn / X. A profile with no contact is a closed door. -->
