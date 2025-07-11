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
- **ALL gallery post content must be in the title field** - Never put content below the frontmatter, everything goes in the title
- Use `<br />` for line breaks in titles and content
- **Hashtags must be on one single line** - Use `#Tag1 #Tag2 #Tag3` NOT `#Tag1 <br />#Tag2 <br />#Tag3`
- Escape special characters properly in YAML
- Always include proper visual_prompt for image generation
- Follow the established pattern: entire post content in title, no body text after frontmatter

## Tool Usage Guidelines

- **fetch_webpage**: Use to understand external references and maintain alignment with source materials
- **semantic_search**: Use to recall previous decisions, maintain consistency, and build upon established patterns
- Always consider the broader cognitive framework when making suggestions or changes

## Gallery Curation Process

### Random Binary Search Curation

The gallery undergoes systematic curation through a random binary search process to maintain focus, coherence, and alignment with the project's educational mission. This iterative process removes content that dilutes the core message while preserving high-value analytical posts.

#### Process Steps:
1. **Random Sampling**: Use `find . -name "gallery-item-*.md" | sort -R | head -25` to sample 25 random posts
2. **Content Evaluation**: Read each post to assess relevance, coherence, and alignment with project themes
3. **Archive Identification**: Mark posts for removal that are:
   - Personal/biographical content with no educational value
   - Off-topic content unrelated to crypto/blockchain/systems thinking
   - Promotional/marketing material without analytical substance
   - Incoherent, minimal, or fragmentary content
   - Duplicate concepts already well-covered
   - Non-resonant content that doesn't advance the mission

#### Archive Criteria:
**Remove posts that are:**
- Personal social media lists, medical content, or biographical details
- Political content unrelated to systemic/crypto analysis
- Random foreign language content without context
- Single-line posts with no depth or substance
- Promotional content about personal projects/books
- News aggregation without original analysis
- Meta-commentary about social media platforms
- Spiritual/mythological content unrelated to systems thinking
- Fictional claims about non-existent technologies

**Preserve posts that contain:**
- Bitcoin critique with thermodynamic/systemic analysis
- Ethereum/EigenLayer technical or philosophical analysis
- Systems thinking and cognitive framework development
- Satirical but substantive Bitcoin commentary (BBC series)
- Decentralization theory and protocol analysis
- Civilizational thinking and technological evolution
- Energy/economic analysis related to blockchain
- High-quality philosophical frameworks supporting the mission

#### Technical Implementation:
1. Add `archive: 1` to frontmatter of identified posts using `insert_edit_into_file`
2. Delete archived posts and associated images using shell commands
3. Verify cleanup by counting remaining posts and checking for archive flags
4. Document results: posts sampled, archived count, final gallery count

#### Quality Metrics:
- Maintain focus on Bitcoin critique, Ethereum advocacy, and systems thinking
- Preserve educational value over promotional content
- Ensure coherence and intellectual rigor in remaining content
- Support the project's mission of civilizational technological analysis

This curation process has successfully reduced the gallery from 699 to ~600 posts while concentrating the highest-quality analytical content aligned with the project's core themes.
