# Scoop Bucket Template

<!-- Uncomment the following line after replacing placeholders -->
[![Tests](https://github.com/calefrey/scoop-apps/actions/workflows/ci.yml/badge.svg)](https://github.com/calefrey/scoop-apps/actions/workflows/ci.yml)
[![Excavator](https://github.com/calefrey/scoop-apps/actions/workflows/excavator.yml/badge.svg)](https://github.com/calefrey/scoop-apps/actions/workflows/excavator.yml)

My personal scoop bucket for apps that either didn't have a manifest or didn't have functional auto-updates.
## How do I install these manifests?

After manifests have been committed and pushed, run the following:

```pwsh
scoop bucket add calefrey https://github.com/calefrey/scoop-apps
scoop install calefrey/sonarr
```

## How do I contribute new manifests?

To make a new manifest contribution, please read the [Contributing
Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md)
and [App Manifests](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests)
wiki page.
