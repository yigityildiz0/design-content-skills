<!-- CURRENT-SKILL-PUBLICATION -->
![Design & Content Skills](assets/collection-hero.svg)

# Design & Content Skills

UI/UX, visual identity, writing and creative workflows. These **13 workflows** help the assistant select tools, check evidence and produce reviewable results. They do not change model weights or guarantee better decisions.

[![Download ChatGPT](https://img.shields.io/badge/ChatGPT-Download_ZIP-10a37f?style=for-the-badge)](https://github.com/yigityildiz0/design-content-skills/raw/refs/heads/main/downloads/ChatGPT.zip) [![Download Claude](https://img.shields.io/badge/Claude-Download_ZIP-d97757?style=for-the-badge)](https://github.com/yigityildiz0/design-content-skills/raw/refs/heads/main/downloads/Claude.zip)

**ChatGPT:** the button downloads a plugin with all listed skills and supporting files. Use the personal-plugin/skill import supported by your account. A single-skill ChatGPT button downloads a one-skill plugin. **Claude:** unpack the collection ZIP, then upload its individual skill ZIPs; the outer collection is not a single Claude skill. Local Codex/Claude Code files and cloud-account installation are separate.

Use natural English or Turkish requests. A slash-prefixed word typed in chat does not register a host command. Explicit local skill invocation uses the canonical skill name; available tools, network access and credentials remain host-dependent.

## Included skills

| Skill | What it solves / example request | ChatGPT | Claude |
|---|---|---|---|
| [`web-ui-design`](skills/common/web-ui-design/SKILL.md) | Design, improve and review usable web/app interfaces | [↓ ZIP](packages/chatgpt/web-ui-design.zip) | [↓ ZIP](packages/claude/web-ui-design.zip) |
| [`ui-ux-pro-max`](skills/common/ui-ux-pro-max/SKILL.md) | Choose visual styles, palettes, fonts and UX patterns | [↓ ZIP](packages/chatgpt/ui-ux-pro-max.zip) | [↓ ZIP](packages/claude/ui-ux-pro-max.zip) |
| [`ui-styling`](skills/common/ui-styling/SKILL.md) | Style accessible responsive interfaces with Tailwind and shadcn | [↓ ZIP](packages/chatgpt/ui-styling.zip) | [↓ ZIP](packages/claude/ui-styling.zip) |
| [`web-animation`](skills/common/web-animation/SKILL.md) | Implement meaningful scroll, transition and micro-interaction motion | [↓ ZIP](packages/chatgpt/web-animation.zip) | [↓ ZIP](packages/claude/web-animation.zip) |
| [`design`](skills/common/design/SKILL.md) | Choose and execute an appropriate visual design workflow | [↓ ZIP](packages/chatgpt/design.zip) | [↓ ZIP](packages/claude/design.zip) |
| [`design-system`](skills/common/design-system/SKILL.md) | Build design tokens and coherent component specifications | [↓ ZIP](packages/chatgpt/design-system.zip) | [↓ ZIP](packages/claude/design-system.zip) |
| [`brand`](skills/common/brand/SKILL.md) | Keep voice, identity and messaging consistent | [↓ ZIP](packages/chatgpt/brand.zip) | [↓ ZIP](packages/claude/brand.zip) |
| [`banner-design`](skills/common/banner-design/SKILL.md) | Create banners for web, social media and advertising | [↓ ZIP](packages/chatgpt/banner-design.zip) | [↓ ZIP](packages/claude/banner-design.zip) |
| [`slides`](skills/common/slides/SKILL.md) | Design structured HTML presentations and pitch decks | [↓ ZIP](packages/chatgpt/slides.zip) | [↓ ZIP](packages/claude/slides.zip) |
| [`campaign-plan`](skills/common/campaign-plan/SKILL.md) | Plan audience, channels, content, budget and measurement | [↓ ZIP](packages/chatgpt/campaign-plan.zip) | [↓ ZIP](packages/claude/campaign-plan.zip) |
| [`site-seo-audit`](skills/common/site-seo-audit/SKILL.md) | Audit metadata, schema, crawlability, links and performance | [↓ ZIP](packages/chatgpt/site-seo-audit.zip) | [↓ ZIP](packages/claude/site-seo-audit.zip) |
| [`yigit-writer`](skills/common/yigit-writer/SKILL.md) | Write and revise messages, emails and articles in natural language | [↓ ZIP](packages/chatgpt/yigit-writer.zip) | [↓ ZIP](packages/claude/yigit-writer.zip) |
| [`ai-image-video-studio`](skills/common/ai-image-video-studio/SKILL.md) | Plan and troubleshoot ComfyUI and AI media workflows | [↓ ZIP](packages/chatgpt/ai-image-video-studio.zip) | [↓ ZIP](packages/claude/ai-image-video-studio.zip) |

## Installation and technical boundaries

- Full canonical sources: `skills/common/`; provider packages: `packages/chatgpt/`, `packages/claude/`, `packages/codex/`.
- Every Claude skill has at most 200 files and a description of at most 200 characters. ZIPs include all files of the selected provider source.
- External services (Gemini, Parallel, Context7), local CLIs and subscriptions are not provided by these ZIPs. Report missing tools rather than simulating access.
- Validation checks package integrity, paths, descriptions, source/package parity and hashes. It is not a live account-installation test or a clinical/financial effectiveness claim.
- See [checksums](downloads/SHA256SUMS.txt), [provenance](PUBLICATION.md), and [third-party notices](THIRD_PARTY_NOTICES.md). Existing license and copyright files retain their scope; there is no blanket license grant over third-party content.

<!-- END-CURRENT-SKILL-PUBLICATION -->

