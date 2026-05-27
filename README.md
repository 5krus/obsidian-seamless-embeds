# Seamless Embeds

An Obsidian plugin that makes embedded (transcluded) notes visually indistinguishable from the surrounding text.

When you use `![[Note Name]]` to embed a note, Obsidian normally renders it with a border, indentation, and link icon. Seamless Embeds removes all of that so the embedded content flows naturally as part of the document — readers can't tell where one note ends and another begins.

## What it does

- Removes borders, padding, and margins from embeds
- Hides the embed title and link icon
- Makes divider lines (`---`) inside embeds match full document width
- Works with nested embeds (embeds within embeds)
- Works in both Reading mode and Live Preview

## Installation

### From the Community Plugin Store

1. Open **Settings → Community plugins → Browse**
2. Search for **Seamless Embeds**
3. Click **Install**, then **Enable**

### Manual Installation

1. Download `main.js`, `styles.css`, and `manifest.json` from the [latest release](https://github.com/5krus/obsidian-seamless-embeds/releases/latest)
2. Create a folder at `<your-vault>/.obsidian/plugins/seamless-embeds/`
3. Place the three files inside that folder
4. Restart Obsidian and enable the plugin in **Settings → Community plugins**

## Usage

Just install and enable — there are no settings. All `![[embeds]]` will render seamlessly.
