# MagicMtn

MagicMtn provides managed compute for AI agents. It provisions isolated cloud sandboxes, scales compute as agents need it, and connects them to models, repositories, and tools. Coding agents can keep running after you disconnect, so you can return to the same workspace to check progress and pick up where you left off.

## Developing with MagicMtn

Start a sandbox from the `magic` CLI or launch a cloud coding session from Pi or OpenCode. Use a machine template to give new sandboxes a consistent starting point with the GitHub repositories you’ve authorized. For inference, choose a model from the managed catalog or connect your own provider.

Managed [Model Context Protocol (MCP)](https://modelcontextprotocol.io/) integrations let agents work with services such as Linear, Sentry, and Notion. The MagicMtn gateway checks access when forwarding tool calls and keeps connected service credentials outside the sandbox.

## What you can run

- **Background coding sessions.** Run a test suite or work through a code change in a cloud workspace, then reconnect when you’re ready to review the result.
- **Issue investigations.** Give an agent access to the relevant repository and tools so it can trace a Sentry error back to the code or gather context for a Linear issue.
- **Tasks from Slack.** Start an agent with an `@magic` mention and steer it from the same thread.

## Get started

Install the MagicMtn CLI and sign in.

```sh
curl -fsSL https://magicmtn.ai/install.sh | sh
magic login
```

- [Website](https://magicmtn.ai/)
- [Documentation](https://magicmtn.ai/docs/)
- [Discord](https://discord.gg/2fDyqE7BV)
