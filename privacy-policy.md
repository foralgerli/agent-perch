# Privacy Policy

Last updated: May 22, 2026

Agent Perch is a macOS developer utility for monitoring local AI coding agent
sessions. This policy explains what information the app handles, how it is
used, and what choices you have.

## Summary

Agent Perch is designed to work locally on your Mac. It does not require an
account, does not sell personal information, and does not use advertising
tracking.

Agent Perch does not send your prompts, responses, code, diffs, terminal output,
project paths, repository names, SSH targets, secrets, tokens, or API keys to
the developer.

## Information Processed Locally

To provide its core features, Agent Perch may process information on your Mac,
including:

- AI coding agent session status, events, prompts, responses, approvals,
  follow-up questions, errors, and completion notifications.
- Local session history and transcript files for supported tools when you enable
  the related integrations.
- Terminal, tmux, IDE, SSH, process, and session identifiers used to show the
  correct session and return focus to the related workspace.
- Configuration files for supported local tools, including Claude Code, Codex,
  Gemini CLI, Qwen Code, Kimi CLI, Hermes Agent, OpenClaw, OpenCode, Cursor,
  Qoder, CodeBuddy, WorkBuddy, GitHub Copilot, and compatible hook-driven tools.
- App preferences such as display mode, sounds, shortcuts, mascot settings,
  language, integration settings, and history/search settings.

This information is used to display session state, surface approval prompts and
questions, install or update local integrations you enable, route notifications,
restore context, and focus related terminal or IDE windows.

## Optional Telemetry

Agent Perch may offer optional product telemetry. Telemetry is not required for
the app to function, and you can disable it in Settings.

If telemetry is enabled, Agent Perch may send a limited set of product usage
events to help improve reliability and integration quality. These events may
include app launch events, integration installation results, client type
categories, coarse session lifecycle categories, error categories, and feature
usage counts.

Telemetry does not include prompts, responses, code, diffs, terminal output,
project paths, file paths, repository names, usernames, hostnames, SSH targets,
IP addresses, raw hook payloads, diagnostic files, secrets, tokens, API keys, or
the contents of local agent sessions.

If telemetry is enabled, Agent Perch may use Alibaba Cloud Simple Log Service to
store product usage events. See `docs/telemetry.md` in the project repository
for the current event and field allowlist.

## Permissions

Agent Perch may request macOS permissions needed for its features, including:

- File access for user-selected folders or local tool configuration locations.
- Accessibility or Automation access to focus terminal and IDE windows, return
  to related sessions, and support local workflow automation.
- Notifications to show local status, approvals, questions, and completion
  updates.
- Local network access for hook and bridge communication between supported local
  tools and the app.

You can manage these permissions in macOS System Settings.

## Remote SSH Features

If you enable remote SSH support, Agent Perch uses the SSH target information
you provide to connect to the selected host, install or remove the remote bridge
when requested, and forward session events back to the local Agent Perch app.

Remote SSH information and forwarded session events are used for this feature
and are not sent to the developer.

## Diagnostics

Agent Perch may let you export diagnostics for troubleshooting. Diagnostic
exports are user-initiated, saved to a location you choose, and intended to
redact sensitive values where possible. Review diagnostic files before sharing
them in a GitHub issue or support request.

## Third-Party Tools

Agent Perch works with third-party developer tools and services that you install
or configure separately. Those tools, AI providers, remote hosts, Apple services,
GitHub, and other services you choose to use have their own privacy practices.
This policy covers Agent Perch itself.

## Your Choices

You can:

- Disable optional telemetry in Settings.
- Remove local integrations from Settings or from the related tool
  configuration files.
- Revoke macOS permissions in System Settings.
- Delete Agent Perch settings and local data from your Mac.
- Contact support with privacy questions.

## Contact

For privacy questions or support, open an issue at:

https://github.com/foralgerli/agent-perch/issues

