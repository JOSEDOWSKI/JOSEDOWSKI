<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:4c1d95,100:8A2BE2&height=180&section=header&text=Jose%20Molina&fontSize=54&fontColor=ffffff&fontAlignY=36&desc=Requirements%20first.%20Code%20second.&descSize=18&descAlignY=58" alt="" />

**Full-stack engineer.** I build platforms end to end — data model, API, deploy —
and I go one layer down when the abstraction starts lying to me.

CPO & co-founder of [Promesa.tech](https://promesa.tech) · Arequipa, Peru

<p>
<img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Go" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white" alt="NestJS" />
<img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
</p>

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

## Reach me

- Web — [promesa.tech](https://promesa.tech)
- LinkedIn — [in/jmolinadev](https://www.linkedin.com/in/jmolinadev/)
- Email — [jose.molina@promesa.tech](mailto:jose.molina@promesa.tech)
