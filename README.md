# free360viewer plugin for Claude Code

Look at 360° photos and panoramas in an interactive viewer without leaving Claude, and put a 360° photo on a web page with the free viewer script. No account, nothing to pay, and no photo is stored.

The plugin brings two things:

- **The free360viewer connector** (`https://mcp.free360viewer.com/mcp`): a public MCP server with one tool, *View 360 photos*. It needs no sign-in.
- **The free360viewer skill**: tells Claude to open 360° photos in the viewer, and to use the [@orbix360/viewer](https://www.npmjs.com/package/@orbix360/viewer) script when it writes a web page with a 360° photo.

## Install

```text
/plugin marketplace add orbix360/free360viewer-plugin
/plugin install free360viewer@free360viewer
```

Then start a new session and ask, for example, "show me this in 360: https://example.com/lobby.jpg".

In the Claude app, download the skill from https://free360viewer.com/guides/view-360-photos-in-claude-or-chatgpt and add the connector by its address instead.

## Privacy

The connector stores no photo and no conversation: https://free360viewer.com/legal/ai-connector-privacy

## About this repository

Generated from the Orbix360 repository on every production release; changes made here are overwritten. MIT licence.
