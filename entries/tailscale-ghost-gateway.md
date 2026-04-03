# Ghost Gateway for OpenClaw

### Remote Browser Automation with Tandem + Tailscale

> **Hook:** SSH forwarding, Tailscale, and Ghost JSON were enough to bend the architecture.

This is the Tailscale / transport entry point for the Ghost Gateway experiment.

- SSH local forwarding creates the fake local gateway
- Tailscale connects the two machines cleanly
- Ghost JSON completes the illusion
- the remote runtime stays real while the local endpoint stays believable

**Read the full article:** [../articles/ghost-gateway-for-openclaw.md](../articles/ghost-gateway-for-openclaw.md)
