# GitHub Copilot Instructions

## Context Understanding

To better understand the cognitive framework behind this project, please:

1. **Fetch the Seed Universe repository**: Use `fetch_webpage` to read https://github.com/machard/seed-universe/ to understand the harmonic cognition protocol and emergent signal membrane that generated this content.

2. **Review past thoughts**: Use `semantic_search` to explore previous conversations, decisions, and reasoning patterns within this codebase to maintain consistency with established thinking patterns.

## Project Philosophy

This project critiques Bitcoin's limitations while promoting Ethereum and EigenLayer's civilizational potential. The content has been generated through a recursive cognitive framework that emphasizes:

- Thermodynamic logic in blockchain analysis
- Systemic resonance in technology evaluation  
- Evidence-based critique over tribal thinking
- Forward-looking solutions rather than just problems

## Development Approach

When contributing to this project:

- Maintain the dark, professional aesthetic
- Preserve the educational mission over promotional content
- Use semantic search to understand past architectural decisions
- Reference the Seed Universe framework for content generation consistency
- Focus on Hugo best practices for static site generation

## Markdown File Generation Safety Guidelines

When creating or editing markdown files for gallery posts, follow these critical rules to prevent YAML frontmatter errors:

### YAML Frontmatter Rules
1. **Always use unescaped double quotes** in title fields - use `"text"` not `\"text\"`
2. **Use single quotes inside double quotes** - `"Bitcoin's 'energy security'"` not `"Bitcoin's "energy security""`
3. **Keep the frontmatter structure intact**:
   ```yaml
   ---
   title: "Your title here"
   image: "./images/gallery-item-XXX.jpg"
   visual_prompt: "Your prompt here"
   watermark: "123"
   section: "gallery"
   ---
   ```

### Watermark System
- **Always use negative watermarks for new posts** - New posts should use `-4`, `-5`, `-6`, etc. (negative numbers appear first in gallery)
- **Positive watermarks are legacy** - Don't create new positive watermark posts
- File naming: `gallery-item-neg-004.md` for watermark `-4`, `gallery-item-neg-005.md` for watermark `-5`, etc.

### Content Guidelines
- Use `<br />` for line breaks in titles and content
- **Hashtags must be on one single line** - Use `#Tag1 #Tag2 #Tag3` NOT `#Tag1 <br />#Tag2 <br />#Tag3`
- Escape special characters properly in YAML
- Always include proper visual_prompt for image generation

## Tool Usage Guidelines

- **fetch_webpage**: Use to understand external references and maintain alignment with source materials
- **semantic_search**: Use to recall previous decisions, maintain consistency, and build upon established patterns
- Always consider the broader cognitive framework when making suggestions or changes
