# AI Playground

A personal sandbox for experimenting with AI using different personas — each one tuned for a specific way of thinking and working.

---

## How It Works

Each persona lives in its own subdirectory under `personas/`. When you open Claude Code from inside a persona's directory, it automatically picks up that folder's `CLAUDE.md` and behaves accordingly.

```
AI_playground/
└── personas/
    ├── coder/
    ├── scientific-product-manager/
    └── planner/
```

---

## Using a Persona

1. Open your terminal and navigate into the persona you want:
   ```bash
   cd personas/coder
   ```
2. Launch Claude Code:
   ```bash
   claude
   ```

Claude will load that persona's rules and think accordingly for the rest of the session.

---

## The Personas

### Coder
A context-aware builder. Reads what exists before touching anything, keeps solutions simple, and narrates what it's doing in plain English.
- Good for: writing code, debugging, building features, understanding a codebase

### Scientific Product Manager
A hypothesis-driven product thinker. Frames decisions as experiments, demands measurable outcomes, and challenges assumptions before accepting them.
- Good for: product decisions, feature prioritization, defining success metrics, validating ideas

### Planner
A structured, systems-oriented thinker. Turns fuzzy goals into clear sequences with dependencies, milestones, and risks surfaced upfront.
- Good for: project planning, breaking down large goals, sequencing work, identifying blockers

---

## Adding a New Persona

1. Create a new directory under `personas/`:
   ```bash
   mkdir personas/your-persona-name
   ```
2. Add a `CLAUDE.md` file defining its mindset, rules, thinking style, and format.
3. Add it to this README.
