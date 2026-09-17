# 🦊 Fox ACP Client

> A privacy-preserving, local-first VSCode extension acting as the companion UI for **Fox Code CLI** over the Agent Client Protocol (ACP).

## Overview

Fox ACP Client brings local AI agent capabilities directly into VSCode:
- **Streaming Chat UI**: Preact-based panel with collapsible `<think>` reasoning blocks and tool lifecycle tracking.
- **Interactive Diff Review**: Side-by-side file review before applying agent modifications to disk.
- **Dynamic MCP Forwarding**: Automatic injection of workspace MCP tools into agent sessions.
- **Zero Telemetry**: Air-gapped, offline operation with zero remote telemetry.

## Documentation

Full architectural specifications and implementation roadmap are maintained in the root `fox` repository:
- Specs: `docs/fox-acp-client/specs/`
- Plan: `docs/fox-acp-client/plans/acp-client-implementation-plan.md`
