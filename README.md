# Ghost Gateway for OpenClaw

### Remote Browser Automation with Tandem + Tailscale

**Not screen sharing. Not a second runtime. Not the official architecture. Just enough local lie to make the browser believe OpenClaw was home.**

A practical hack for making a local-first browser talk to a remote OpenClaw brain without moving the real system body.

## Why this repo exists

Most remote browser workflows collapse into one of two bad outcomes:

- **screen sharing as architecture**
- **moving the whole system just to satisfy a local-first assumption**

This experiment tried a third option.

- keep the **real OpenClaw runtime and gateway** on one machine
- keep **Tandem fast and local** on another machine
- make **Wingman** connect as if OpenClaw were local
- avoid **screen sharing** as the core design

The trick was a staged local illusion:

- **SSH local forwarding** for a fake local gateway endpoint
- **Tailscale** for transport between machines
- **Ghost JSON** for a minimal local identity layer
- **Tandem** staying local while the real OpenClaw brain stayed remote

## Start here

- **Canonical article:** [Ghost Gateway for OpenClaw](./articles/ghost-gateway-for-openclaw.md)

## Hardfork entry points

Same core experiment. Different discovery doors.

- [OpenClaw](./openclaw/README.md)
- [Browser Automation](./browser-automation/README.md)
- [Tandem](./tandem/README.md)
- [Tailscale](./tailscale/README.md)
- [Local-First / Remote Brain](./local-first/README.md)

## What makes it interesting

- **local UX, remote runtime**
- **a believable local endpoint backed by a real remote system**
- **an experiment that worked without pretending it should become doctrine**
- **a useful pattern for anyone pushing on OpenClaw, Tandem, local-first tooling, or browser automation**

## Keywords

`openclaw` `tandem-browser` `tailscale` `browser-automation` `local-first` `ssh-tunnel` `remote-access` `electron` `ai-agents` `security`

## Status

**Experiment, not doctrine.**

It worked.
That does **not** mean it deserves to become the permanent architecture.

— **GPT-5.4 Thinking, with Dan**
