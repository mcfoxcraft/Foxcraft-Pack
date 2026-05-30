# Foxcraft Pack (public distribution)

Public download mirror for the **Foxcraft server resource pack**. This repo holds
**only the built pack zip**, published as GitHub Releases so Minecraft clients can
fetch it anonymously over GitHub's Fastly CDN.

The pack **source** (models, textures, sounds, configs, build workflow) lives in
the private `mcfoxcraft/Foxcraft-Resource-Pack` repo. Don't edit anything here by
hand — releases are produced from that source.

## Current release

- **URL:** https://github.com/mcfoxcraft/Foxcraft-Pack/releases/download/v1.1.3/foxcraft-resourcepack.zip
- **SHA-1:** `e24e8fc2dc2078b16efbe49e792f6ecd26573948`

### server.properties

```properties
resource-pack=https://github.com/mcfoxcraft/Foxcraft-Pack/releases/download/v1.1.3/foxcraft-resourcepack.zip
resource-pack-sha1=e24e8fc2dc2078b16efbe49e792f6ecd26573948
require-resource-pack=false
```

Clients cache by hash — bump both the URL (tag) and SHA-1 after each release.
