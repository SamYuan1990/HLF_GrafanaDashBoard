# HLF_GrafanaDashBoard
Grafana Dash board for hyperledger fabric(ref [Metrics](https://hyperledger-fabric.readthedocs.io/en/release-2.2/metrics_reference.html?highlight=Metrics))

## How to use
1. Set up Prometheus + Grafana + Hyperledger
1. You are able to import three dash boards from json files.
1. Have fine with it.

## Introduce to dashboards.
### Common
1. Basic panel: Basic infor for HF nodes.
1. Blocks panel: Block related Metrics
1. GRPC Connection panel: GRPC connection related Metrics
1. Logging panel: Logging Metrics.

### Peer
1. Peer General: Peer related Metrics.
1. Chaincode: Chaincode related Metrics.
1. Endorsement: Endorsement related Metrics.
1. Ledger: Ledger related Metrics.
1. Gossip: Gossip related Metrics.

### Orderer
1. Orderer related Metrics.

## To Do List
1. Variable in Grafana to switch host, channel etc.
1. Change and understanding each metrics to have a good display and UX.
1. Customer defined metrics(basing on Fabric Metics doing sum/avg... etc)
1. General Alert

## How to develop
1. [video in chinese](https://www.bilibili.com/video/bv1LU4y1h7sB)