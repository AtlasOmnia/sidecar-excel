# Sidecar for Excel — sidebar site

Static sidebar for **Sidecar for Excel** (Sidecar by Atlas Omnia), served at
https://atlasomnia.github.io/sidecar-excel/ — the plugin's default `addin_base`.

Built unchanged from [AtlasOmnia/sidecar@`cae879e0cddead4717ba381bc759e91552c9ee39`](https://github.com/AtlasOmnia/sidecar/tree/cae879e0cddead4717ba381bc759e91552c9ee39/excel) with:

```
cd excel && npm ci && npm run build:static -- --base https://atlasomnia.github.io/sidecar-excel/
```

Rebuild from that commit and compare against `SHA256SUMS`. Load `manifest.xml` into desktop Excel.
Source, issues and license: https://github.com/AtlasOmnia/sidecar (Apache-2.0). Not affiliated with Microsoft or Nous Research.
