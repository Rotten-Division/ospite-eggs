<img src=".github/assets/banner.svg" alt="OspiteHosting" width="320">

# ospite-eggs

The egg catalogue shipped by [OspiteHosting](https://ospitehosting.com). Vendored copies of the Pelican eggs we run, plus a few we maintain ourselves.

## Requesting a game

Want a game added to OspiteHosting? Open an issue on this repo with the game name and a link to the upstream egg if you know one. We will take a look.

## Channels

- `canary` rebuilds on every push to `main`.
- `release` is cut from tags shaped like `release-v*`.

The manifest at `manifest.json` carries both channels. Consumers point at one or the other.

## License

[MIT](LICENSE). Vendored eggs carry the same license from `pelican-eggs/*`.
