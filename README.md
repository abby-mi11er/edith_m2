# E.D.I.T.H. M2 — Lightweight Research Assistant

**Even Dead I'm The Hero — Scout Edition**

The lightweight, focused companion to [E.D.I.T.H. M4](https://github.com/YOUR_USERNAME/edith_m4). M2 delivers the core research experience — Winnie chat, Library, and essential tools — in a streamlined 7-panel interface optimized for everyday academic work.

---

## M2 vs M4

| Feature | M2 (Scout) | M4 (Research Forge) |
|---------|-----------|-------------------|
| **Panels** | 7 focused | 24 comprehensive |
| **UI** | Minimal, chat-first | Multi-panel cockpit |
| **Research Modes** | 7 (Grounded, Lit Review, Counter, Gap Analysis, Exam Prep, Teach Me, Office Hours) | Agentic AI with pipeline chaining |
| **Hardware** | Optimized for M1/M2 MacBooks | Designed for M3/M4 Pro |
| **Memory** | 8GB friendly | 16GB+ recommended |
| **Backend** | Shared with M4 or bundled | Full FastAPI server |

**M2 is for daily use. M4 is for deep research sessions.** Both share the same backend and data.

---

## Quick Start

```bash
git clone <repo-url>
cd edith_m2
npm install
npm run dev           # Frontend on port 5176
```

M2 needs a backend. Either:
- **Option A**: Point to a running M4 backend → `http://localhost:5176/?backend=http://localhost:8014`
- **Option B**: Use the bundled Edith.app backend on port 8003

---

## Panels

| Category | Panel | Description |
|----------|-------|-------------|
| **Research** | Winnie | AI chat with 7 research modes and academic citations |
| **Research** | Library | Paper management with folder categories |
| **Research** | Search | Federated paper discovery |
| **Tools** | Vibe Coder | One-click research code generation |
| **Tools** | Methods Lab | Methodology deconstruction |
| **Tools** | Paper Dive | Citation graph explorer |
| **Tools** | Citations | Citation management |

## Research Modes

| Mode | Purpose |
|------|---------|
| **Grounded** | Standard Q&A grounded in your library |
| **Lit Review** | Synthesize literature on a topic |
| **Counter** | Generate counterarguments |
| **Gap Analysis** | Find holes in the literature |
| **Exam Prep** | Study mode with practice questions |
| **Teach Me** | Pedagogical explanations |
| **Office Hours** | Socratic questioning |

---

## Architecture

| Layer | Stack |
|-------|-------|
| **Frontend** | React + Vite, 7 panels |
| **Styling** | Apple-inspired light theme (`#0071e3` accent) |
| **State** | Zustand single store |
| **Backend** | Shared with M4 (FastAPI) |
| **Electron** | Desktop wrapper with drive detection |

---

## Privacy

All data stays local. No telemetry, no cloud storage. See [M4 Privacy Policy](https://github.com/YOUR_USERNAME/edith_m4/blob/main/docs/PRIVACY_POLICY.md).

---

## License

**Source-Available, Non-Commercial.** Free to use, modify, and learn from. Cannot be sold or republished as your own. See [LICENSE](LICENSE).

---

## Related

- **[E.D.I.T.H. M4](https://github.com/YOUR_USERNAME/edith_m4)** — Full 24-panel research forge with agentic AI, causal inference, and Socratic debate.
