# MyRule

# The Anatomy of Ideal Technical Documentation

Effective technical documentation is a product, not an afterthought. It guides users from curiosity to mastery with clarity, structure, and accuracy. Inspired by standards from GitHub, Stripe, and Notion, great documentation balances precision with usability.

## Structure

An ideal documentation set follows a predictable hierarchy:
1. **Overview:** Defines purpose, audience, and core concepts.  
2. **Setup:** Provides step-by-step installation and configuration.  
3. **Guides & Tutorials:** Teach common workflows through examples.  
4. **Reference:** Lists APIs, CLI commands, or configuration options.  
5. **FAQ & Troubleshooting:** Addresses real-world issues efficiently.

Logical navigation and consistent naming allow users to find answers fast—just like browsing GitHub’s REST API docs.

## Style & Tone

Write in a **concise, active voice**. Prioritize clarity over flair. Each sentence should convey intent, context, or action. Use consistent terminology, second-person (“you”) perspective, and short sentences that reduce cognitive load. The tone should be professional yet approachable—developer-first, not marketing-driven.

## Content Quality

Every detail must be **accurate, version-aware, and testable**. Code snippets should compile; endpoints should work. Each update should trace back to product changes, ensuring no stale content.

## Visuals & Formatting

Use **code blocks, tables, UI screenshots, and diagrams** to illustrate complex flows. Visual cues—like callouts or syntax highlighting—help users scan and learn faster.

## Tooling & Maintenance

Maintain docs as code:  
- **Markdown** for portability and Git-based workflows  
- **CI checks** for broken links and formatting  
- **Linters** (e.g., Vale) for style consistency  
- **Versioning** aligned with releases to prevent drift  

---

```mermaid
graph TD
    A[Overview] --> B[Setup]
    B --> C[Guides & Tutorials]
    C --> D[API Reference]
    D --> E[FAQ & Troubleshooting]
    E --> F[Contribute & Maintain]
