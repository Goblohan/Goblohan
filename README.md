# Olusanya Gbolahan V

Co-founder, research and architecture · PerceptraAI Lab

I work on assurance for autonomous systems: whether the authorization behind an AI agent's
action survives the path from the decision to the effect.

- **[darm-monitor](https://github.com/Goblohan/darm-monitor)**: DARM, a machine-checked Lean 4
  theory of authorization and assurance transfer. Every module is checked in CI, and every
  theorem the paper cites is checked on each build.
- **[Darm-Guard](https://github.com/Goblohan/Darm-Guard)**: the runtime. A broker that executes
  only what DARM's decision kernel admits, and records signed evidence of every effect.
  `pip install darm-guard`

Each claim in this work says what supports it (proved, constructed, tested or assumed), the
checks behind it are shown to be load-bearing by breaking them, and the limitations are stated
next to the results.

gbolahan@perceptra.ai
