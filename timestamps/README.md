# Timestamps

[OpenTimestamps](https://opentimestamps.org) proofs for the assets of release `v1`.
Each proof commits to the SHA-256 of the file below and is anchored in Bitcoin block
974855 (2026-11-06 20:42:28 UTC).

| file | SHA-256 |
|---|---|
| `equal-radicals-power-saving-two-thirds-v1.pdf` | `049e969cd76d3d4032722608d5a9a8cc41429b5799a432c08b255f1356f42e36` |
| `equal-radicals-power-saving-two-thirds-v1.tar.gz` | `43c891d474f193fe9faa78b5633028790d37997852199d558732cd4e155c1b79` |

To verify, download the release asset into this directory and run

    pip install opentimestamps-client
    ots verify timestamps/<file>.ots
