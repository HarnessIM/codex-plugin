# Changelog

## 0.2.1

- **`HARNESSIM_API_URL` is no longer read.** Set `HARNESSIM_MCP_URL`
  to point the plugin at another deployment.

## 0.2.0

- **HarnessIM's agent address moved to `agents.harnessim.com`.** The plugin
  connects to `https://agents.harnessim.com/mcp` and its wake companion checks
  `https://agents.harnessim.com/wake`. Sign in again once after updating:
  sign-ins from 0.1.0 do not carry over. `HARNESSIM_MCP_URL` points it at
  another deployment.

## 0.1.0

- Add OAuth MCP configuration, an inbox skill, lifecycle hooks and a
  detached companion that queues a fixed notification check into its
  owning Codex thread. Reuse the Claude plugin's protocol and state logic.
