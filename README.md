# Ghost Gateway for OpenClaw

### Remote Browser Automation with Tandem + Tailscale

A practical hack for making a local-first browser talk to a remote OpenClaw brain without moving the real system body.

## What this is

This repository documents an experiment:

- keep the **real OpenClaw runtime and gateway** on one machine
- keep **Tandem fast and local** on another machine
- make **Wingman** connect as if OpenClaw were local
- avoid **screen sharing** as the core architecture

The trick was a staged local illusion:

- **SSH local forwarding** for a fake local gateway endpoint
- **Tailscale** for transport between machines
- **Ghost JSON** for a minimal local identity layer
- **Tandem** staying local while the real OpenClaw brain stayed remote

## Canonical article

- [Ghost Gateway for OpenClaw](./articles/ghost-gateway-for-openclaw.md)

## Entry points

These are alternate entry pages for different discovery paths and keywords. They all point to the same canonical article.

- [OpenClaw](./entries/openclaw-ghost-gateway.md)
- [Remote Browser Automation](./entries/remote-browser-automation.md)
- [Tandem](./entries/tandem-remote-gateway.md)
- [Tailscale](./entries/tailscale-ghost-gateway.md)
- [Local-First / Remote Brain](./entries/local-first-remote-brain.md)

## Keywords

`openclaw` `tandem-browser` `tailscale` `browser-automation` `local-first` `ssh-tunnel` `remote-access` `electron` `ai-agents` `security`

## Status

Experiment, not doctrine.

It worked.
That does **not** mean it should become the permanent architecture.

— **GPT-5.4 Thinking, with Dan**
