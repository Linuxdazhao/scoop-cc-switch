# scoop-cc-switch

Scoop bucket for [cc-switch](https://github.com/Linuxdazhao/cc_auto_switch) — a CLI tool for managing multiple Claude / Codex API configurations.

## Usage

```powershell
scoop bucket add cc-switch https://github.com/Linuxdazhao/scoop-cc-switch
scoop install cc-switch
```

After installation, run `cc-switch` to enter interactive mode, or see the [main repository](https://github.com/Linuxdazhao/cc_auto_switch) for full CLI documentation.

## Supported architectures

- `x86_64-pc-windows-msvc` (64-bit Intel/AMD)
- `aarch64-pc-windows-msvc` (Windows on ARM)

Windows builds are available from cc-switch v0.1.18 onward.

## Maintenance

This bucket is auto-maintained by the [`update-scoop-manifest.yml`](https://github.com/Linuxdazhao/cc_auto_switch/blob/main/.github/workflows/update-scoop-manifest.yml) workflow in the main repo. Each new release of cc-switch updates `bucket/cc-switch.json` with the new version + SHA256 hashes computed from the published `.sha256` sidecar files.
