# [Plugin name]

**Track:** [accounting / finance / marketing / HR]
**What it does:** [One or two sentences: the procedure, its input, and its output.]
**Who it's for:** [The Cosmic Crunch role that would run it.]

## Install

Drag the plugin ZIP into your Codespace's Explorer and unzip it into a folder of its own. In the terminal:

```
unzip [plugin-zip-name].zip -d [folder-name]
```

Then in Claude Code:

```
/plugin marketplace add ./[folder-name]
/plugin install [plugin-name]@[marketplace-name]
```

`[marketplace-name]` is the `name` in the ZIP's `.claude-plugin/marketplace.json`.

## Use

[The command to run, or what to ask Claude, and what files it expects.]

## Test cases

| # | Input | Expected result | Result | Notes |
|---|---|---|---|---|
| 1 | | | | |
| 2 | | | | |
| 3 | | | | |
| 4 | | | | |
| 5 (edge case) | | | | |

## Known limits

[What it doesn't handle yet, and what a user should check by hand.]
