# useless-skills

A collection of stupid and nonsensical Claude Code skills.

## Installation

Clone this repo and copy the skills you want into your project's `.claude/skills/` directory, or into `~/.claude/skills/` to make them available globally.

```sh
# Project-level (one project only)
cp -r .claude/skills/<skill-name> /your/project/.claude/skills/

# Global (all projects)
cp -r .claude/skills/<skill-name> ~/.claude/skills/
```

Restart Claude Code and the skill will appear in the `/` command menu.

## Usage

Invoke any skill by typing its name as a slash command in Claude Code:

```
/ulysses-doc-gen
```

## Skills

### `/ulysses-doc-gen`

Transforms technical documentation into James Joyce's Ulysses style — stream-of-consciousness READMEs, catechistic API references, and Molly Bloom installation guides. Technical accuracy preserved, buried in the riverrun of the prose.
