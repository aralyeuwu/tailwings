# Tailwings

> ✈️ Wings for Tailscale to Fly

## About

Inspired by [patte/fly-tailscale-exit](https://github.com/patte/fly-tailscale-exit), with a much simpler configuration.

This repo enables to run Tailscale on Fly.io, specifically to run exit nodes.

> [!warning]
> In September 2023, [Tailscale and Mullvad announced to partner up](https://tailscale.com/mullvad).
> This is recommend to use instead of the setup described here.

## Getting Started

1. Fork the repo
2. Enable GitHub Actions on the fork
3. Setup GitHub Actions secrets
  * `TAILSCALE_AUTHKEY`
  * `FLY_API_TOKEN`
4. Run **Tailwings > Deploy** workflow

## License

MIT © [Léo Colombaro](https://colombaro.fr)
