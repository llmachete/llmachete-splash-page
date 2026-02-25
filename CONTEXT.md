# LLMachete Splash Page Context

## Project Identity

### Purpose
The main landing page for LLMachete - the first impression for visitors. Communicates the value proposition of LLMachete as the AI Investment Measurement Authority and provides clear paths to content, services, and engagement.

### Spirit / Intent / Zeitgeist
**First impression matters.** Clear, confident, direct. The landing page embodies the machete metaphor - cutting through complexity to show exactly what LLMachete offers. No fluff, no corporate speak. Professional authority without pomposity.

### What Good Looks Like
- Value proposition is immediately clear (above the fold)
- Brand identity is unmistakable (colors, typography, voice)
- CTA is prominent and compelling
- Page loads fast (< 3 seconds)
- Works flawlessly on mobile
- Builds credibility quickly

### Validation Rubric
- [ ] LLMachete brand guidelines fully applied
- [ ] Value proposition above the fold
- [ ] Page loads under 3 seconds
- [ ] Mobile responsive and complete
- [ ] CTA is clear and compelling
- [ ] Voice is direct, no unnecessary words
- [ ] Typography: TeX Gyre Adventor properly loaded
- [ ] Colors: #D97D42, #0E5A61, #1A2332, #F0E7E0

---

## Current State

### Active Tasks
| Task | Status | Notes |
|------|--------|-------|
| Initial scaffolding | unknown | Git repo exists |
| Brand compliance | pending | Apply full guidelines |
| Content writing | pending | Need copy for sections |
| Design implementation | pending | Ready to build |

### Recent Decisions
| Date | Decision | Rationale |
|------|----------|-----------|
| TBD | Separate splash page project | Dedicated repo for main landing |

### Open Questions / Blockers
- [ ] What sections should the landing page include?
- [ ] What is the primary CTA (newsletter, contact, content)?
- [ ] Should it link to Rice to AirPods and other content?

### Technical Debt / Known Issues
- Project state needs verification
- May need to start fresh with brand compliance

---

## Architecture

### Tech Stack
- **Framework**: Next.js (assumed, like other LLMachete content)
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Deployment**: Vercel

### Key Patterns
- Follow LLMachete brand guidelines strictly
- Self-hosted TeX Gyre Adventor fonts
- Brand color CSS variables
- Mobile-first responsive design

### External Dependencies
| Dependency | Purpose | Status |
|------------|---------|--------|
| Vercel | Hosting | Available |
| Google Analytics | Tracking | TBD |

### File Structure Highlights
```
llmachete-splash-page/
├── [Git repo initialized]
├── [Structure TBD]
└── CONTEXT.md
```

---

## Session Log

### Latest Session: 2026-01-31
**Focus**: Project Context Management System setup

**Accomplished**:
- Created CONTEXT.md for Splash Page project
- Added to project registry with aliases

**In Progress**:
- N/A (context setup only)

**Next Steps**:
1. Review current project state
2. Define page sections and content strategy
3. Implement with full brand compliance

**Key Context for Next Session**:
- Project needs review to understand current state
- Must be brand-compliant (this is the brand's front door)
- Reference Rice to AirPods for implementation patterns

---

## Reference Materials

### Key Documentation
- `/home/llmachete/projects/claude-code/LLMachete/CLAUDE.md` - Brand guidelines
- `/home/llmachete/projects/claude-code/LLMachete/LLMachete_Style_Guide.md` - Voice and tone
- `/home/llmachete/projects/claude-code/LLMachete/brand-identity-docs/` - Full brand assets

### Related Projects
- **LLMachete**: Parent project
- **Rice to AirPods**: Reference implementation for brand compliance

### External Resources
- Landing page best practices
- LLMachete brand guidelines documentation
