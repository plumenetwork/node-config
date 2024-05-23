# Plume Testnet Node Config

This repo is set up to easily run replica nodes for the Plume Testnet. Simply run `docker-compose up` to bring a replica node up locally.

The docker image for Plume Testnet is hosted in a public docker repo: `public.ecr.aws/i6b2w2n6/nitro-node:plume-v2.3.2`

The nodeConfig file is prepopulated with Plume Testnet parameters. The current setup uses a public RPC url for the Ethereum mainnet RPC and stores node data in the Docker volume.
