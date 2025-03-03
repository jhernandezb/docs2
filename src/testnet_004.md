# Testnet 004

## Basic info

- Chain ID: `nois-testnet-004`
- Demon: `unois`

## Genesis

- Time: March 21st 15:00 UTC
- URL: https://raw.githubusercontent.com/noislabs/networks/nois-testnet-004.final.2/nois-testnet-004/genesis.json
- Checksum (sha256): `371b29ef51a0f50f882621f3631e7210f78208635f4a1c6877fa6e75366a4d55`

## Binary

- Build `noisd` from https://github.com/noislabs/noisd
- Tag: v0.6.0
- `noisd version` should show 0.6.0

## p2p

Seed nodes

- `ade4d8bc8cbe014af6ebdf3cb7b1e9ad36f412c0@testnet-seeds.polkachu.com:17356`
- `babc3f3f7804933265ec9c40ad94f4da8e9e0017@testnet-seed.rhinostake.com:17356`

## Contracts

#### nois-drand

```yaml
- Name: nois-drand
  Address: nois16peq3sftghumkja7nu32ztjy0ew4vsnshxfhcv6sxq573ta08gwsgldepm
  Code ID: "11"
  Git Asset Name: nois_drand
  Instantiation Message: '{"incentive_point_price":"25000","incentive_denom":"unois","min_round":,"manager":"nois1p9tw323xdjp5q3yzuecfahmgrpufmm89z93wpk"}'
  URL: "https://github.com/noislabs/nois-contracts"
  Version: v0.10.0
```

#### nois-gateway

```yaml
- Name: nois-gateway
  Address: nois1ze9qajd25ucqnvn2u865uhdtjd6qm5awm3tpl93ure72wgs4d7qsptqc0u
  Code ID: "12"
  Git Asset Name: nois_gateway
  Instantiation Message: "{}"
  URL: "https://github.com/noislabs/nois-contracts"
  Version: v0.10.0
```

#### nois-icecube

```yaml
- Name: nois-icecube
  Address: nois1mdjzz7y7crnjgfkdld4x9ravqymh22jy2c7jpukqnkghhzv5s9ys2a9hu7
  Code ID: "14"
  Git Asset Name: nois_icecube
  Instantiation Message: '{"manager":"nois1p9tw323xdjp5q3yzuecfahmgrpufmm89z93wpk"}'
  URL: "https://github.com/noislabs/nois-contracts"
  Version: v0.10.0
```

#### nois-sink

```yaml
- Name: nois-sink
  Address: nois16rpxzry8jf06j8htjphf0lnmylh28enwm4xwkfpn3699wvyys2yqgcev3h
  Code ID: "13"
  Git Asset Name: nois_sink
  Instantiation Message: "{}"
  URL: "https://github.com/noislabs/nois-contracts"
  Version: v0.10.0
```
