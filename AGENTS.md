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


**Wikilink convention in `.abilities/wiki/` files.** These files are synced from the c3po vault via `$HOME/Library/Mobile Documents/iCloud~md~obsidian/Documents/c3po/.train-of-thought/scripts/sync-wiki-refs.sh`. Obsidian wikilinks `[[foo]]` are rewritten to `[foo]($HOME/c3po/wiki/foo.md)` at sync time, so `Read` tools can follow them through the `~/c3po -> <vault>` symlink. If you see a raw `[[foo]]` that survived conversion, the target is `$HOME/c3po/wiki/foo.md`.
