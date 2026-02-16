# Tailscale Docker Sidecar Configuration

This repo contains all the Docker containers that I run in my homelab, served on my [Tailscale](https://tailscale.com/) tailnet. This is not (completely) indicative of my actual setup, as I don't want to reveal any sensitive information. As such, this repo serves as an example for anyone wanting to setup these Docker containers on their Tailscale tailnets.

Most info I have pulled to make these configurations came from the Tailscale Development Community repo, [ScaleTail](https://github.com/tailscale-dev/ScaleTail).

For now, assume that each container dir contains a `ts-state/` dir.
