# Six Human-Agent Interaction Patterns for Enterprise Agent Systems

> Beyond the chat window — how humans and AI agents actually collaborate in real enterprise workflows.

When AI Agents move from consumer chat interfaces into real enterprise operations, "conversation" becomes just one of six distinct interaction patterns — and often not the most frequent one.

This repository contains **interactive prototypes** illustrating each pattern, designed as companion material for the [LinkedIn article](https://www.linkedin.com/pulse/TODO) by [Jeff Zhang](https://www.linkedin.com/in/eaglez/).

## 🔗 Live Demo

**[→ View Interactive Prototypes](https://eaglez.github.io/six-enterprise-agent-interaction-modes/)**

## The Six Patterns

| # | Pattern | Metaphor | Description |
|---|---------|----------|-------------|
| 1 | **Supervisory** | 🗼 Air Traffic Control | Watch agents work in real time; intervene only on exceptions |
| 2 | **Adjudicative** | ⚖️ Judge & Case Brief | Agent presents evidence; human renders final judgment |
| 3 | **Calibrative** | 🎓 Mentoring an Intern | Correct agent mistakes as structured teaching moments |
| 4 | **Strategic** | 📜 Legislator Drafting Law | Configure rules, signals, and thresholds agents operate within |
| 5 | **Exploratory** | 🔍 Detective & Partner | Co-investigate open-ended problems through dialogue |
| 6 | **Retrospective** | 📊 Performance Review | Periodic review of agent accuracy, cost, drift, and health |

## Key Insight

Most enterprise Agent UX discussions focus on the **Exploratory** pattern (conversational AI). But in production enterprise systems, the other five patterns collectively account for the majority of human-agent interaction time. Designing for all six — and understanding when each applies — is essential for building Agent systems that operators actually trust and use.

## Repository Structure

```
├── index.html              # Landing page with all prototype previews
├── prototypes/
│   ├── 01_home.html        # Agent Ops Hub (central dashboard)
│   ├── 02_supervisory.html # Real-time monitoring dashboard
│   ├── 03_adjudicative.html# Structured case review interface
│   ├── 04_calibrative.html # Feedback and correction workflow
│   ├── 05_strategic.html   # Strategy and policy configuration
│   ├── 06_exploratory.html # Investigation workbench (conversational)
│   └── 07_retrospective.html # Weekly performance report
└── README.md
```

## About

These prototypes are static HTML files — no build step, no dependencies, no frameworks. Just open any `.html` file in a browser.

They illustrate interaction patterns abstracted from real enterprise Agent platform design, using a fictional "AgentOps" compliance operations platform as the example domain.

## Author

**Jeff Zhang** — Head of Product (AI) | ex-Microsoft Group Product Manager

- [LinkedIn](https://www.linkedin.com/in/eaglez/)
- Series: Enterprise AI & Agent Systems

## License

MIT License — feel free to reference, adapt, or build upon these patterns.
