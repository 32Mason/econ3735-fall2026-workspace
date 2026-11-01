# ECON/BUS 3735 workspace

This is your workspace for Modules 3 to 7. It runs in a GitHub Codespace, a temporary computer in the
cloud that you use through your browser. You open this template straight into a Codespace, so you don't
need to create a GitHub repository.

Claude in your browser is fine for quick, short-lived tasks, such as making a test file or asking a
question. Projects that build up files over several sessions, such as a skill, a plugin, or a workbook,
belong in Claude Code here, where the Explorer panel shows every file the agent creates or changes.

**Your Codespace is temporary. Download everything you want to keep.** GitHub can automatically
delete an inactive Codespace, along with everything in it. The default retention period is 30 days of
inactivity, but settings can shorten it. Saving a file or stopping the Codespace does not create a
backup. Download your coursework after each assignment and make a complete backup before the course
ends on December 6. Do not leave your only copy in Codespaces.
See [GitHub's automatic deletion policy](https://docs.github.com/en/codespaces/setting-your-user-preferences/configuring-automatic-deletion-of-your-codespaces).

## First time (Module 3)

1. Sign in to GitHub and open the [course template](https://github.com/jpalYSU/econ3735-fall2026-workspace).
2. Choose **Use this template → Open in a codespace**. Wait for the container to finish building; it
   installs Claude Code and the spreadsheet tools.
3. In the terminal, type `claude` and press Enter. Choose your Claude account login and follow the
   browser prompt. Use your Claude Pro subscription rather than an API billing account.
4. Ask Claude: `What skills do you have available?` It should list **steering-log**.
5. Confirm `data/`, `templates/`, and `.claude/skills/steering-log/` are present.

If the template is unavailable, Blackboard's Codespaces Setup page includes the same workspace as
a ZIP, with browser-only setup steps. If you're reading this inside your Codespace, start at step 3.

## Every session

- Go to [github.com/codespaces](https://github.com/codespaces) and open your existing codespace. Don't
  create a new one each time, and don't delete it until you've downloaded everything.
- Start Claude Code with `claude` in the terminal.
- Export the assignment's chat history and download your files and steering log. Use different
  filenames for each assignment so a new export doesn't overwrite an earlier one.
- Stop your Codespace when you finish so it doesn't use hours while idle: on github.com/codespaces,
  choose **...** next to it, then **Stop codespace**. Stopping it does not prevent later automatic
  deletion.

## Download a complete backup

1. Save all open files. In Claude Code, use `/export assignment-chat.txt` to save the current
   conversation in your course folder; replace the filename with one that identifies the assignment.
   Export each conversation you need to keep, and save its steering log too. Claude Code keeps its own
   record of each conversation outside your course folder, so a conversation you don't export won't be
   in your backup.
2. Ask Claude to create a dated ZIP of **all your coursework**: skills, plugins, scripts, datasets,
   reports, spreadsheets, images, decks, web pages, recordings, test results, exported chat histories,
   and steering logs. Include hidden folders such as `.claude/skills`. Exclude
   passwords, API keys, installed software, and older backup ZIPs. Keep the backup private.
3. Find the ZIP in the Codespace's **Explorer**, right-click it, and choose **Download**. Save it on
   your own computer and keep another copy in OneDrive or another location you control.
4. Unzip the downloaded copy and open several files, including a plugin or skill, a spreadsheet or
   report, and a chat export. Check that the files are present and readable before relying on it.

## What's here

| Folder | What it's for |
|---|---|
| `.claude/skills/steering-log/` | The course steering log skill. Ask for a steering log at the end of a session, and name it after the assignment, for example `steering-log-first-skill.md`. |
| `templates/skill-template/` | A starting point for your First Skill (Module 3). Copy it into `.claude/skills/your-skill-name/` and keep your version snapshots in a `versions/` folder inside it. Put your test files in a `test-inputs/` folder at the top level. |
| `templates/plugin-template/` | A starting point for your Plugin Build (Module 4). |
| `.claude-plugin/marketplace.json` | Lists your plugin so a classmate can install it (Module 4). Change its `name` to use your own last name. |
| `data/` | Cosmic Crunch data files used in assignments. |

## Free hours

Verified students get extra free Codespaces hours through the GitHub Student Developer Pack. Stop
your codespace when you finish so it doesn't use hours idling.
