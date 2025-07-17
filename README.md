# Scoop Bucket Template

<!-- Uncomment the following line after replacing placeholders -->
[![Tests](https://github.com/choonyoong/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/choonyoong/scoop-bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/choonyoong/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/choonyoong/scoop-bucket/actions/workflows/excavator.yml)

Personal bucket for [Scoop](https://scoop.sh), the Windows command-line installer.


## How do I install these manifests?

After manifests have been committed and pushed, run the following:

```pwsh
scoop bucket add scoop-bucket https://github.com/choonyoong/scoop-bucket
scoop install scoop-bucket/<manifestname>
```
