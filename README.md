# Nebula Photos — Update Channel

Version 1.0

Signed update manifests and encrypted code packages for Nebula Photos appliances.

- `manifest.json` — tested Immich image digests + code package pins, signed by the vendor (`manifest.json.minisig`)
- `nebula-code.tar.gz.enc` — encrypted appliance code package

Appliances verify the signature against their factory-installed public key and refuse anything unsigned, tampered, or older than what they run.
