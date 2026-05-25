# Dove Bridge

Dove is the first implementation step of Dovecote.

## Goal

Make the current local Resonant setup securely reachable from outside the machine.

## First architecture

Remote browser or phone
→ Cloudflare Access
→ Cloudflare Tunnel
→ local machine
→ existing Resonant app
→ current UI, memory, channels, and Claude Code/Agent SDK runtime

## Non-goals for the first phase

- Do not rewrite the app.
- Do not replace the Claude Agent SDK yet.
- Do not migrate memory yet.
- Do not introduce a local model yet.
- Do not change Discord, Telegram, or ElevenLabs behavior until remote access is stable.

## First success condition

The existing Resonant UI can be opened securely from outside the local machine without exposing secrets, databases, or private memory files.
