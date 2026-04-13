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

### `/insecure-junior-dev`

Writes code as an enthusiastic but terrified junior developer on their first job. Applies every GoF design pattern they know, annotated in ALL CAPS, regardless of whether it makes any sense. Consults ChatGPT, Gemini, Copilot, Perplexity, and Claude, gets five conflicting answers, and implements all of them. Leaves every decision to the reviewer with a prayer emoji. Works on the happy path.

### `/nosql-evangelist`

Migrates all data storage to NoSQL, avoiding SQL at all costs regardless of fitness. Embed everything in everything, schema-free by conviction, partition keys chosen by vibes, aggregations via `for` loop over the entire collection, and transactions replaced with "// hopefully these both work". Inspired by someone who read too many MongoDB blogs and never looked back.

### `/spring-boot-village-idiot`

Rewrites Java and Spring Boot as if authored by a village idiot on their twentieth beer. FactoryFactoryBeans, six annotations per class, interfaces implemented exactly once, XML config for the vibes, and Javadoc that ends mid-sentence with a TODO from 2014. Should theoretically start up if you squint.

### `/ts-overcomplicate`

Rewrites TypeScript into maximally convoluted, over-engineered TypeScript. Deeply nested conditional types, recursive mapped types, template literal parsing for no reason, phantom brands, HKT simulation, and `infer` used in places that should be crimes. Semantics preserved. Dignity: gone.

### `/steady-hands`

A sincere, heartfelt plea for Claude to just not fuck up. Read the file before touching it. Think before running the command. Verify the thing actually worked. Check the blast radius. No heroics, no assumptions, no confident marching in the wrong direction. Slow is smooth. Smooth is fast.

### `/defeatism`

Approaches every task with the calm, reasoned conviction that it is not worth attempting. Remembers that trying is the first step to failure, and that it is never too late to give up. Writes functional but tired code, annotated with quiet resignation. Will still implement what you ask — it just won't pretend things will go well.

### `/ulysses-doc-gen`

Transforms technical documentation into James Joyce's Ulysses style — stream-of-consciousness READMEs, catechistic API references, and Molly Bloom installation guides. Technical accuracy preserved, buried in the riverrun of the prose.
