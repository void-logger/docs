# Documentation project instructions

## About this project

- This is a Mintlify documentation site for the Chameleon Discord API framework.
- Pages are MDX files with YAML frontmatter.
- Site configuration lives in `docs.json`.
- The generated low-level API reference still lives in `/docs` and can be linked from Mintlify pages.

## Style preferences

- Write for developers building real bots.
- Prefer direct explanation over marketing language.
- Use second person only when giving actionable guidance.
- Keep examples small and runnable.
- Prefer describing actual behavior from `src`, not aspirational behavior.
- Call out limitations or incomplete DX when they exist.

## Content boundaries

- Document only public or effectively public framework behavior.
- Do not invent APIs that do not exist in `src`.
- If a guide depends on a known limitation or workaround, say so explicitly.
