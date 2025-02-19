# Celestia Networks
modens
This repository contains the configuration files for Celestia networks.

Please refer to the [Celestia Docs](https://docs.celestia.org) for guides on running your own node. The configuration files `genesis.json` and `addrbook.json` are intended for use by Consensus nodes and should be placed in the node's home directory (by default `$HOME/.celestia-app/config`).

## Networks

| Name     | Type    | Chain ID     | Configs                    |
|----------|---------|--------------|----------------------------|
| Mocha    | Testnet | `mocha-4`    | [mocha-4](./mocha-4)       |
| Arabica  | Testnet | `arabica-10` | [arabica-10](./arabica-10) |
| Celestia | Mainnet | `celestia`   | [celestia](./celestia)     |

## Software versions

The celestia-app and celestia-node versions in use on each network are visible on this [Grafana dashboard](https://celestia.grafana.net/public-dashboards/5d14d96e44f04664bb0c44267e5d645c).
