# My Scoop Bucket

[![Tests](https://github.com/rfnash/scoop/actions/workflows/ci.yml/badge.svg)](https://github.com/rfnash/scoop/actions/workflows/ci.yml) [![Excavator](https://github.com/rfnash/scoop/actions/workflows/excavator.yml/badge.svg)](https://github.com/rfnash/scoop/actions/workflows/excavator.yml)

My [bucket](https://github.com/lukesampson/scoop/wiki/Buckets) for [Scoop](https://scoop.sh), the Windows command-line installer.

## How do I install these manifests?

After manifests have been committed and pushed, run the following:

```pwsh
scoop bucket add rfnash https://github.com/rfnash/scoop
scoop install rfnash/<manifestname>
```

## How do I contribute new manifests?

To make a new manifest contribution, please read the [Contributing
Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md)
and [App Manifests](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests)
wiki page.
