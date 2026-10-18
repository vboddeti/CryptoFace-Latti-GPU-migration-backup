# Backend runtime sources

The native runtime evaluates the CryptoFace model with LattiSense on
CKKS ciphertexts. Model configuration is in `config.yml`; cryptographic
parameters are in `latti/model/client/ckks_parameter.json` and
`latti/model/server/ckks_parameter.json`.
