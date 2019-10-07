# Ethereum Mainnet

Extract data from the Ethereum Mainnet using [Infura](https://infura.io). The code of the flow engine can be imported from [this file](flow-engine.json).

The code makes a network request each second to retrieve block info including all transactions. Transactions are saved to an ontology to be analyzed in the next steps.

## Ontology schema

To make `flow-engine.json` work, first, you need to create an ontology and call it `eth_mainnet_tx`. See schema in [this file](ontology-schema.json):

## How it looks like?

<p align="center">
  <a src='https://www.onesaitplatform.com/'>
    <img src='diagram.png'/>
  </a>
</p>
