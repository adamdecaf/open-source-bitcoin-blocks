# open-source-bitcoin-blocks

A list of Bitcoin blocks mined from bedrooms, offices, garages with open source hardware you can build and trust.

## Usage

There is a JSON file `blocks.json` for download. The file is an array of JSON objects like:

```javascript
[
  {
    "height": 913272,
    "hash": "0000000000000000000094e66964da28a35c67a2d9ba1bcb46a190fb1ffb73ac",
    "link": "https://mempool.space/block/0000000000000000000094e66964da28a35c67a2d9ba1bcb46a190fb1ffb73ac",
    "miner": "nerdqaxe++",
    "details": "Mined on Ocean." // optional, can be missing
  }
]
```

## History

The [bitaxe](https://bitaxe.org/) project restarted open-source bitcoin mining by leveraging existing ASIC chips with
fully open source mining firmware and control. To further that effort the [256 Foundation](https://github.com/256foundation)
hosted hashathons to raise funds to sponsor open source developers. Those sponsorships have fostered multiple projects
to reestablish open source as the future of bitcoin mining.

## Projects using this data

- [Hardest Blocks](https://hardestblocks.org/) - a leaderboard of the most mathematically difficult bitcoin blocks

## License

This is released into the public domain.
