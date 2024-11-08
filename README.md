# scoop-bucket

[![Tests](https://github.com/<username>/<bucketname>/actions/workflows/ci.yml/badge.svg)](https://github.com/<username>/<bucketname>/actions/workflows/ci.yml) [![Excavator](https://github.com/<username>/<bucketname>/actions/workflows/excavator.yml/badge.svg)](https://github.com/<username>/<bucketname>/actions/workflows/excavator.yml)

My [Scoop](https://scoop.sh) bucket.

## How do I install these manifests?

After manifests have been committed and pushed, run the following:

```pwsh
scoop bucket add pbar1 https://github.com/pbar1/scoop-bucket
scoop install pbar1/<manifestname>
```
