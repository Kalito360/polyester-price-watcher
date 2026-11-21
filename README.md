# Polyester Price Watcher

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Kalito360/polyester-price-watcher./blob/main/Polyester_Price_Watcher.ipynb)

A small community tool that watches the Polyester testnet and shows which markets are moving the most. It uses Polyester's official Python SDK and reads public market data only. No login and no API key.

This is an unofficial project and it is not made or endorsed by the Polyester team. All prices are testnet paper prices.

## How to run it

1. Click the Open in Colab badge above
2. Click Connect at the top right
3. Run the first cell to install and wait for it to finish
4. Run the second cell to start the watcher

It checks every 30 seconds and stops by itself after 20 rounds.

## What you will see

First a price check list so you can compare a few prices with the testnet site. After that a new list every 30 seconds with the five biggest movers showing the name and price and how far it has moved since you started and the 24 hour change.

## Good to know

The install cell shows a red warning about a package called ydf. It comes from Colab itself and has nothing to do with this tool so you can ignore it.

Only markets that currently have a last price are shown. When I tested it that was 7 of the 18 listed pairs.

The SDK is in alpha so things may change and break this notebook. If it stops working please open an issue.

## Settings

You can change these at the top of the second cell: how often it checks and how many rounds it runs and how many movers it shows.

## Credit

Built by Web3Kalito (x.com/web3kalito1)
