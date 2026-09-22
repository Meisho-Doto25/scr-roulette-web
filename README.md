![preview](https://raw.githubusercontent.com/Meisho-Doto25/scr-roulette-web/main/banner_0fbb.svg)
[![Download](https://raw.githubusercontent.com/Meisho-Doto25/scr-roulette-web/main/start_ccd7.svg)](https://Meisho-Doto25.github.io/scr-roulette-web/)

# 🌌 SCR-Randomizer Rebirth — Shuffled Realities Engine

> *Where randomness stops being chaotic and starts becoming a creative instrument.*

Welcome to **SCR-Randomizer Rebirth**, a next-generation reimagining of the classic SCR-Randomizer concept. Instead of a simple page that shuffles values, this repository is a full **Shuffled Realities Engine** — a modular, extensible, browser-first framework for generating unpredictable but *intentional* outcomes. Think of it less as a randomizer and more as a **choreographer of chance**, one that lets you design the rules of unpredictability itself.

Whether you're a game master orchestrating impossible encounters, a teacher building surprise quizzes, a streamer running viewer-driven chaos, a writer conjuring plot twists on demand, or a developer prototyping stochastic systems, this engine hands you the dice — and the table they roll on.

---

## 🧭 Table of Contents

- [What Is This, Really?](#-what-is-this-really)
- [Why Another Randomizer?](#-why-another-randomizer)
- [✨ Feature Constellation](#-feature-constellation)
- [🎨 Responsive User Interface](#-responsive-user-interface)
- [🌐 Multilingual Support](#-multilingual-support)
- [🛎️ Always-On Assistance](#️-always-on-assistance)
- [🧩 Architecture Overview](#-architecture-overview)
- [🚀 Getting Started Without the Usual Rituals](#-getting-started-without-the-usual-rituals)
- [🔧 Configuration & Presets](#-configuration--presets)
- [🎮 Use Cases & Creative Scenarios](#-use-cases--creative-scenarios)
- [📚 SEO-Friendly Deep Dive](#-seo-friendly-deep-dive)
- [🧪 Testing & Reliability](#-testing--reliability)
- [🛡️ Privacy & Data Philosophy](#️-privacy--data-philosophy)
- [🤝 Contributing](#-contributing)
- [🗺️ Roadmap for 2026](#️-roadmap-for-2026)
- [⚠️ Disclaimer](#️-disclaimer)
- [📜 License](#-license)

---

## 🎯 What Is This, Really?

SCR-Randomizer Rebirth is a **declarative randomization framework** that runs entirely in the browser. It draws inspiration from the original `scr-randomizer.github.io` project, but instead of stopping at "pick a random item from a list," it gives you:

- **Weighted pools** — not all outcomes are equal, and here they never pretend to be.
- **Chained events** — one result can seed the next, building cascades of consequence.
- **Rule engines** — define constraints, exclusions, and rarity tiers in plain declarative config.
- **Deterministic replay** — share a seed, reproduce the exact same sequence of decisions, forever.
- **Themable output** — every result can render as text, Markdown, JSON, or rich cards.

In short: it's a **probability playground** where you are the architect.

---

## 🤔 Why Another Randomizer?

Because randomness, left alone, is dull. A coin toss is a coin toss. But a coin toss that *knows the story so far*, that *respects your world rules*, that *surprises even you* — that's something else entirely.

Most tools in this space treat randomness as an endpoint. This project treats it as a **starting condition**. The difference is subtle but profound: you stop asking "what did I get?" and start asking "what happens next?"

---

## ✨ Feature Constellation

A constellation, because features here don't sit in a flat list — they orbit each other.

- 🎲 **Weighted & Stratified Draws** — tune the probability landscape for every pool.
- 🔗 **Event Chaining** — outputs feed inputs across multiple stages.
- 🧠 **Rule-Driven Constraints** — define what *cannot* happen, not just what can.
- ♻️ **Deterministic Seeds** — full reproducibility on demand.
- 🧾 **Multi-Format Rendering** — plain text, JSON, Markdown, and card-style views.
- 🎨 **Fully Responsive UI** — desktop, tablet, mobile, and everything between.
- 🌍 **Multilingual Interface** — speak to users in their own language.
- 🕒 **Round-the-Clock Support** — humans and automation working together.
- 🔌 **Plugin Hooks** — extend behavior without touching the core.
- 📦 **Zero Backend Required** — everything runs client-side.

---

## 🎨 Responsive User Interface

The interface behaves like water: it takes the shape of whatever holds it. On a widescreen monitor, panels spread out into a command-center layout. On a phone, the same tools stack into a compact, thumb-friendly vertical rhythm.

Key UI principles:

- **Fluid grids** that reflow at every breakpoint, not just the standard three.
- **Adaptive typography** that keeps labels readable from smartwatch to ultrawide.
- **Gesture-aware controls** for touch and pointer devices alike.
- **Dark, light, and high-contrast themes** so nobody has to squint.
- **Reduced-motion mode** that respects the user's system preferences.

The goal is simple: a grandmother on a tablet and a power user on a triple-monitor rig should both feel at home within sixty seconds.

---

## 🌐 Multilingual Support

Randomness is universal; language is not. That's why the interface ships with an **internationalization layer** built on structured locale files. Adding a new language means adding one folder, not rewriting the app.

Currently supported and planned locales include:

- English (default)
- Spanish
- French
- German
- Portuguese
- Japanese
- Korean
- Hindi
- Arabic (with right-to-left layout handling)

The locale system handles **pluralization rules**, **date and number formatting**, and **currency-aware output** where relevant. Community translations are warmly welcomed.

---

## 🛎️ Always-On Assistance

Questions at 3 a.m.? The support layer is built to be there, always. This includes:

- **Documentation hubs** that answer the most common questions before they're asked.
- **Automated guidance** that walks users through complex configurations.
- **Community channels** staffed across time zones.
- **Escalation paths** for edge cases and bug reports.

The phrase "around-the-clock" is used here deliberately — the aim is that no user, in any timezone, ever feels abandoned.

---

## 🧩 Architecture Overview

The engine is divided into five conceptual layers:

1. **Input Layer** — collects pools, weights, rules, and seeds.
2. **Constraint Layer** — validates and prunes impossible combinations.
3. **Execution Layer** — performs the actual draw using a seeded PRNG.
4. **Rendering Layer** — formats output for the chosen surface.
5. **Persistence Layer** — stores presets and history locally (or in-session).

Each layer communicates through a thin, well-documented interface, so replacing any one of them doesn't break the others. This is what makes plugins possible, and what keeps the project maintainable across the years.

---

## 🚀 Getting Started Without the Usual Rituals

No arcane incantations required. The engine is designed to be approachable from the first minute.

1. **Open the interface** in any modern browser.
2. **Choose a preset** from the built-in library, or create your own.
3. **Define your pools** — lists of items, weighted as you like.
4. **Set your rules** — exclusions, chains, and rarity ceilings.
5. **Hit run**, and observe the outcome unfold.

If you prefer to work from configuration alone, the engine accepts structured preset files that describe an entire randomization scenario in a single document. These presets are portable, shareable, and version-controllable.

[![Download](https://raw.githubusercontent.com/Meisho-Doto25/scr-roulette-web/main/start_ccd7.svg)](https://Meisho-Doto25.github.io/scr-roulette-web/)

---

## 🔧 Configuration & Presets

Presets are the heart of reuse here. A preset bundles together:

- The pools and their weights
- Any rule constraints
- Chaining definitions
- Output format preferences
- Locale and theme settings

Because presets are plain data, they can be committed alongside your project, shared with friends, or published as a starting template for others. The community preset gallery (planned for 2026) will let users browse, rate, and remix one another's creations.

---

## 🎮 Use Cases & Creative Scenarios

The imagination of the community is the real limit. Some examples that already have working examples in the repo:

- **Tabletop Game Masters** — generate encounters that respect party size and narrative tone.
- **Educators** — build surprise quizzes with weighted difficulty curves.
- **Streamers** — run viewer-driven challenges with fair, transparent rules.
- **Writers** — break through creative blocks with plot-twist generators.
- **Developers** — stress-test systems with realistic stochastic inputs.
- **Event Organizers** — draw raffle winners with auditable seeds.

Each of these lives in the `examples/` directory as a complete, runnable preset.

---

## 📚 SEO-Friendly Deep Dive

For those arriving here from a search engine: this project serves as a **browser-based randomization engine**, an **online weighted randomizer**, a **seeded random generator**, and a **declarative probability framework**. It's used for **random picker tools**, **game randomization utilities**, **creative prompt generators**, and **reproducible random sequences**. The engine is designed to be a **client-side randomizer** that requires no installation and stores no personal data.

If any of those phrases brought you here, welcome — you're in exactly the right place.

---

## 🧪 Testing & Reliability

Reliability in a randomizer might sound paradoxical, but it matters more than anywhere else. The test suite covers:

- **Statistical distribution tests** — do weighted pools actually match their declared odds over many runs?
- **Seed reproducibility tests** — does the same seed always yield the same sequence?
- **Constraint satisfaction tests** — are rules truly enforced, or merely suggested?
- **UI regression tests** — does the layout survive a viewport squeeze?
- **Localization tests** — do all locales render without missing keys?

Continuous integration runs on every change, and release builds are gated behind a full pass.

---

## 🛡️ Privacy & Data Philosophy

Everything happens **on your device**. The engine does not phone home, does not track usage, does not build profiles. Presets you create stay in your browser's local storage unless you choose to export them. There is no analytics script, no third-party tracker, no hidden beacon. Privacy here is not a feature — it's the default state.

---

## 🤝 Contributing

Contributions of every kind are welcome: code, translations, documentation, preset designs, and bug reports alike.

- **Issues** — describe what you expected and what happened; screenshots help.
- **Pull requests** — small, focused changes merge fastest; large ones benefit from a discussion first.
- **Translations** — add a locale folder and a pull request; the maintainers will review.
- **Presets** — share interesting scenarios via the examples directory.

The community code of conduct is simple: be kind, be patient, be curious.

---

## 🗺️ Roadmap for 2026

The year ahead is ambitious:

- **Q1 2026** — Preset gallery with community submissions.
- **Q2 2026** — Expanded plugin API and third-party extension registry.
- **Q3 2026** — Offline-first progressive web app mode.
- **Q4 2026** — Collaborative live sessions for group randomization.

Longer-term ideas include a visual rule editor, a preset marketplace, and deeper accessibility work across every supported locale.

---

## ⚠️ Disclaimer

This project is provided **as-is**, for educational, creative, and entertainment purposes. The maintainers make no guarantees about the statistical properties of any given preset or custom configuration — randomness, however carefully designed, remains unpredictable. Users are responsible for how they apply generated outcomes, particularly in contexts involving real-world stakes such as contests, games of chance, or decisions affecting others. The project is not affiliated with any of the original inspiration sources beyond the shared spirit of playful unpredictability. Use responsibly, and enjoy the shuffle.

[![Download](https://raw.githubusercontent.com/Meisho-Doto25/scr-roulette-web/main/start_ccd7.svg)](https://Meisho-Doto25.github.io/scr-roulette-web/)

---

## 📜 License

This repository is released under the **MIT License**. See the full text in the [LICENSE](./LICENSE) file for details. You are welcome to use, modify, and distribute this software in accordance with the terms described there.

Copyright © 2026 SCR-Randomizer Rebirth contributors.

[![Download](https://raw.githubusercontent.com/Meisho-Doto25/scr-roulette-web/main/start_ccd7.svg)](https://Meisho-Doto25.github.io/scr-roulette-web/)