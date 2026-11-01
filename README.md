# Para1LaX updates

Public update channel for the Para1LaX manager.

- Manifest: `stable/update.json`
- Signature: `stable/update.json.sig`
- Manifest URL: https://raw.githubusercontent.com/Para1Lax-Project/updates/main/stable/update.json
- Releases: APK artifacts are attached to GitHub Releases of this repository.

## Trust

The manifest is signed as raw UTF-8 bytes with an Ed25519 key held offline.
The client trusts only the public key embedded in the manager APK.

- Public key (raw 32 bytes, base64): `bI0tXmtzjdVLfyZn15nerdyo+reOfqNKhcbXKKNrEJ4=`
- Public key SHA-256: `e98dbec9015283d759f82c508ccd19cffd1d985a47787492789c8b56ff0f3b8f`

Only manifests signed by this key are accepted. This repository does not contain
source code; source lives in the private development repository.
