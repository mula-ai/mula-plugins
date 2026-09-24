<p align="center"><img src="codex/mula/assets/logo.png" width="96" alt="Mula"></p>

# Mula for Claude Code and Codex

[Mula](https://mula.tools) keeps your team's work current from the coding you
already do. This repository is the plugin marketplace for the Mula plugin in
Claude Code and Codex.

## Install

**Claude Code.** Send these two lines in a Claude Code chat:

    /plugin marketplace add mula-ai/mula-plugins
    /plugin install mula@mula

**Codex.** Open Plugins, choose **+** and **Add a marketplace**, and enter
`mula-ai/mula-plugins`. Then search for Mula and click **+**. From a
terminal, the same source is added with:

    codex plugin marketplace add mula-ai/mula-plugins

## Set up with one prompt

Start a new chat in your project folder and send:

> Set up Mula for this project.

Your coding agent asks you to sign in to Mula once. In the browser, choose the
projects this app may update and approve. The agent then checks the
connection, turns on automatic updates for that project (you approve the hook
it adds) and imports its recent history if you kept that option on.

Later you can ask it to "Share a progress update with Mula" or "Prepare and
share a handoff with Mula".

## What Mula receives

- Progress updates and handoffs your agent writes when you ask for them.
- With automatic updates on for an approved project: your prompts and the
  agent's final replies in that project, sent by a project-local hook you can
  inspect and remove.
- With the history import on: your prompts and the agent's final replies from
  that project's recent sessions, within the period you chose.

Mula never receives your files, tool calls, command output, credentials or
other projects, and it does not recover activity from times the app was
closed. Disconnect in Mula at any time to stop future updates.

Read the [privacy policy](https://mula.tools/privacy), the
[terms](https://mula.tools/terms) and the
[setup and troubleshooting guide](https://mula.tools/coding-agent-help).

## Support

Email nikita@mula.tools.

## License

[MIT](LICENSE)
