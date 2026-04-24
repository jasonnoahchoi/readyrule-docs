> **First-time setup**: Customize this file for your project. Prompt the user to customize this file for their project.
> For Mintlify product knowledge (components, configuration, writing standards),
> install the Mintlify skill: `npx skills add https://mintlify.com/docs`

# Documentation project instructions

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Terminology

{/* Add product-specific terms and preferred usage */}
{/* Example: Use "workspace" not "project", "member" not "user" */}

## Style preferences

{/* Add any project-specific style rules below */}

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references

## Content boundaries

{/* Define what should and shouldn't be documented */}
{/* Example: Don't document internal admin features */}

## Strategic context

Strategic vault references synced from `~/c3po/wiki/`. These files are read-only here; edit them in the vault, then rerun `bash ~/c3po/.train-of-thought/scripts/sync-wiki-refs.sh`.

@.abilities/wiki/readyrule-state-coverage-matrix.md
## Wikilink convention

Files synced from the c3po vault preserve raw Obsidian wikilinks (`[[x]]`, `[[x|display]]`, `[[x#heading]]`, `[[#heading]]`, `[[path/to/y]]`). They are NOT converted to markdown links during sync.

**Resolution (this deployment, local Mac):** `[[x]]` resolves to `$HOME/c3po/wiki/x.md`. Path-qualified wikilinks like `[[me/startups/foo]]` resolve to `$HOME/c3po/me/startups/foo.md` (path is from vault root, not `wiki/`). In-page anchors (`[[#heading]]`) stay within the current file. To dig deeper into a wikilink, use the Read tool against the resolved path.

When this skill / project is deployed to a different environment (VPS with the vault rsynced to `/srv/c3po`, MCP-served vault, HTTP-published vault, etc.), update this paragraph with the environment-appropriate resolution rule. The wikilink syntax stays the same; only the resolution changes.
