# Comic Generation Tool

## Table of Contents
- [Project Overview](#project-overview)
- [Project Goals](#project-goals)
- [Primary Design Principle](#primary-design-principle)
- [How It Works](#how-it-works)
- [Project Components](#project-components)
- [License](#license)

---

## Project Overview

This tool is intended to generate comics that maintain consistency and are true to the storyline of the WattNext Suxxess Dynamics plot. It serves as a comprehensive knowledge base that houses information about each character, the plot, visual assets, and creative guidelines.

**Purpose:** To empower the marketing team to produce high-quality, consistent comic content efficiently while maintaining narrative continuity and character authenticity.

---

## Project Goals

- **Maintain consistent character appearances** across every comic
- **Preserve character personalities and dialogue styles** across all interactions
- **Maintain storyline continuity** throughout the comic series
- **Keep environments and locations consistent** in visual presentation
- **Produce detailed panel descriptions and image prompts** for efficient generation
- **Enable team scalability** by allowing future employees or interns to continue the comic series with minimal training
- **Support multiple LLM providers** (ChatGPT, Claude, Gemini, etc.) through a modular architecture

---

## Primary Design Principle

The highest priority of this project is **visual consistency**. All decisions should be evaluated based on the following priority order:

1. Character appearance
2. Art style
3. Story continuity
4. Character personalities
5. Relationships
6. Dialogue consistency

---

## How It Works

### User Input
The user provides a simple script or story idea for the next comic.

### Agent Process
The agent performs the following steps:

1. **Load the character database** — Retrieve all character information
2. **Load the current story state** — Access timeline and ongoing plot threads
3. **Load organization style guidelines** — Apply WattNext branding and visual standards
4. **Load visual reference information** — Gather character sheets and environment assets
5. **Build an optimized prompt** — Combine all data into a comprehensive LLM prompt
6. **Send the prompt to an LLM** — Generate comic content

### Output & Update
The agent delivers:
- A completed comic script
- Detailed image prompts for each panel
- Updated project memory for future comics

This ensures the user receives production-ready content while maintaining consistency across the entire comic series.

---

## Project Components

### Character Database
Stores permanent information about each character needed to maintain consistency:
- **Appearance** — Physical traits, distinctive features
- **Personality** — Core characteristics and quirks
- **Relationships** — Connections with other characters
- **Speech style** — Dialogue patterns and vocabulary
- **Reference images** — Visual examples and character sheets
- **Character history** — Background and development arc

### Story Database
Stores information about the ongoing comic series:
- **Current storyline** — Active narrative threads
- **Timeline** — Chronological events and pacing
- **Story summaries** — Overviews of completed arcs
- **Important events** — Key plot points and turning moments
- **Open plot threads** — Unresolved story elements for future development

### Visual Reference Library
Stores visual assets to maintain art consistency:
- **Character reference sheets** — Anatomically accurate guides
- **Expressions** — Emotional expressions and reactions
- **Poses** — Common and action poses
- **Color palettes** — Brand colors and character color schemes
- **Location reference images** — Environments and backgrounds

### Style Guide
Stores organization-specific creative guidelines:
- **Art style** — Visual aesthetic and techniques
- **Tone** — Overall mood and atmosphere
- **Humor** — Comedy style and comedic timing
- **Panel format** — Layout and composition standards
- **Branding** — Logo placement and visual identity
- **Writing standards** — Grammar, narrative voice, and content guidelines

### Prompt Library
Contains reusable prompt templates for efficient LLM communication:
- **Comic generation** — Prompts for creating full comic scripts
- **Image prompt generation** — Prompts for detailed visual descriptions
- **Memory updates** — Prompts for capturing new information
- **Continuity checking** — Prompts for verifying consistency

---

## License

This tool is intended for use only by the WattNext Team.

**You may:**
- Use for research, education, and non-commercial purposes

**You may not:**
- Use for commercial purposes without permission
- Remove attribution to WattNext.ai
