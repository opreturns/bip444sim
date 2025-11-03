# bip444sim

Bitcoin BIP-444 Fork Scenario Simulator

## Overview

An interactive single-page visualization tool that demonstrates the economic impact and blockchain dynamics of Bitcoin's BIP-444 enforcement scenarios.

## Features

- **Interactive Pool Configuration**: Toggle major mining pools between compliant and defector status
- **Real-time Block Visualization**: Watch blocks being mined and see orphaned blocks in real-time
- **Economic Impact Analysis**: Live calculations of revenue and losses for compliant vs defector pools
- **Multiple Scenarios**: Explore different fork scenarios by toggling pool compliance

## Usage

Simply open `index.html` in your browser. The simulation auto-starts and shows:

- Compliant pools earning rewards on the main chain
- Defector pools mining orphaned blocks that are rejected by BIP-444 nodes
- Economic analysis showing revenue differences in BTC and USD

## Default Scenario

By default, F2Pool and Luxor are configured as defectors (~22% hashrate), while other major pools maintain BIP-444 compliance (~78% hashrate).

## License

MIT
