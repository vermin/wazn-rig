# Algorithms

WAZNRig uses a different way to specify algorithms if compared to other miners.

Algorithm selection is split in 2 sections:

 * Global base algorithm per miner or proxy instance, `algo` option. Possible values: `cryptonight-wazn`, `cryptonight-lite`, `cryptonight-heavy`.
 * Algorithm variant specified separately for each pool, `variant` option.
 * [Full table for supported algorithm and variants.](https://github.com/xmrig/xmrig-proxy/blob/master/doc/STRATUM_EXT.md#14-algorithm-names-and-variants)

#### Example
```json
{
  "algo": "cryptonight",
  ...
  "pools": [
    {
      "url": "...",
      "variant": 1,
      ...
    }
 ],
 ...
}
```

## Mining algorithm negotiation
If your pool support [mining algorithm negotiation](https://github.com/xmrig/xmrig-proxy/issues/168) miner will choice proper variant automatically and if you choice wrong base algorithm you will see error message.
