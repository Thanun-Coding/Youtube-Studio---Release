# Stable update feed

`stable.json` describes the published V1 installer: version `1.0.0`, its exact size/SHA-256 and an Ed25519 signature verified against the application's bundled public key. The release asset's server-recorded size/digest also matches the local installer.

V1 establishes the production baseline. A newer release is required to exercise a real two-version production update. Windows executable code signing is separate from metadata signing; the V1 executables are unsigned. See [V1 release notes](../RELEASE_NOTES_V1.md) for verification limits, including the incomplete linked-dependency source review.

Future manifests must refer to an existing versioned release asset and be signed again after any installer change. Never reuse a signature for a rebuilt file.
