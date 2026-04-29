# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is a **documentation-only repository** — a curated educational guide for mobile system design interviews targeting iOS and Android engineers. There are no build systems, test suites, or package dependencies. All content is plain markdown.

## Content Structure

```
/
├── README.md            # Core guide (~76KB): interview framework, API design, storage, architecture patterns
├── TEMPLATE.md          # Interview note-taking template
├── BLOGPOSTS.MD         # Curated real-world engineering blog posts
├── common-interview-mistakes.md
├── exercises/           # Practical design scenarios with example solutions
│   ├── chat-app.md
│   ├── file-downloader-library.md
│   ├── caching-library.md
│   └── image-library.md
├── topics/              # Technical deep-dives on specific areas
│   ├── caching-deep-dive.md
│   ├── image-loading-deep-dive.md
│   ├── mobile-pagination-deep-dive.md
│   ├── offline-first-architecture-deep-dive.md
│   └── ... (10 files total)
└── images/              # SVG architecture diagrams (14 files)
```

## Content Conventions

- **Platform-agnostic language:** Use abstract terms (e.g., "Persistence layer") rather than platform-specific ones (Room, CoreData) unless illustrating a platform-specific point.
- **Code examples:** Use both Kotlin (Android) and Swift (iOS) when showing platform-specific implementations.
- **Trade-offs first:** Every design decision should include a pros/cons comparison, ideally as a markdown table.
- **Interview framing:** Content is written from the perspective of a candidate in a 45–60 minute system design interview. Emphasize communication, clarifying questions, and structured thinking over perfect solutions.
- **Diagrams:** Architecture diagrams live in `images/` as SVGs and are referenced inline in the markdown.

## Editing Guidelines

- Keep the breadth-first approach: cover multiple options at a high level before deep-diving.
- Exercises in `exercises/` follow a consistent format: problem statement → requirements gathering → high-level design → deep dives → follow-up questions.
- Deep-dive files in `topics/` are standalone references that exercises link to — keep them self-contained.
- External blog post links in `BLOGPOSTS.MD` should include the company name and a brief description of relevance.
