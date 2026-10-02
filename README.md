# Scoop bucket

A [Scoop](https://scoop.sh) bucket for [Derbent](https://github.com/tunahanaliozturk/derbent), one
guarded pass for all your coding agents.

```powershell
scoop bucket add derbent https://github.com/tunahanaliozturk/scoop-bucket
scoop install derbent
derbent version
```

The manifest installs the prebuilt Windows binary from the matching Derbent release, amd64 or arm64,
and checks it against the hash in that release's `SHA256SUMS`. Every Derbent release can be rebuilt byte
for byte from its tag; [Install and set up](https://github.com/tunahanaliozturk/derbent/blob/main/docs/install.md)
says how.

The manifests here are licensed under Apache-2.0, like Derbent itself.
