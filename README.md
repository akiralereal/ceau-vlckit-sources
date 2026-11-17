# Ceau Player — VLCKit corresponding sources

This repository distributes VideoLAN VLCKit/libVLC source materials and Ceau's dependency patches. VLCKit and libVLC are licensed under LGPL 2.1 or later; contributed libraries retain their own licenses. See COPYING.LIB and the license inventory inside each release asset.

## Status: covers Ceau Player 2.22.0 and earlier only

Ceau Player no longer contains VLCKit. From 3.0.0 on, playback runs on CeauKit, and the sources, patches and build scripts of the libraries it ships (FFmpeg, libass, FriBidi, FreeType, HarfBuzz, dav1d) are published at https://github.com/akiralereal/CeauKit-thirdparty.

This repository is archived and read-only. Its releases stay available for download, so anyone who received a Ceau version that contains VLCKit can still obtain the corresponding source.

## Ceau 2.22.0 (24): iOS, tvOS, macOS, visionOS and watchOS

The release `vlckit-2.22.0-24` covers the iOS, tvOS, universal macOS and visionOS frameworks (libVLC revision 36506) and the watchOS audio-only framework (revision 36502). It contains the pinned VLCKit 4.0.0a19 source, the base and patched libVLC source snapshots, all upstream and Ceau libVLC patches, build scripts and configuration recipes, contributed-library source archives, license inventories and SHA256SUMS. The release notes and the standalone manifest give the exact provenance and checksums.

https://github.com/akiralereal/ceau-vlckit-sources/releases/tag/vlckit-2.22.0-24

## Ceau 2.0.0 (11): native watchOS and visionOS

The release asset contains the exact VLCKit and patched libVLC source snapshots used for the watchOS and visionOS device frameworks, upstream and Ceau patches, build configurations, contributed-library/tool source archives, license texts, and SHA256SUMS. These frameworks are unchanged from the locally validated 1.5.1 (10) candidate; its directory name is retained inside the asset for traceability.

VLCKit tag: `4.0.0a19`; VLCKit commit: `5d8547e0689ea4a526dc08153dc7afe8de685969`.

- watchOS patched libVLC commit: `d966e69cf3e25dee8864b8f17df2f2e2f1985009`
- visionOS patched libVLC commit: `81fe88cb5c9ccfc2dc48a5c8645e756ab38d1dba`

Extract a platform's VLCKit source archive, apply its supplied working-tree patch, and use the recorded build commands/configurations. Both platform libVLC archives contain the same effective source files; their local patch-commit identifiers differ. Consult the archive's README and metadata for the exact reconstruction steps.

This asset covers the two named platforms. Corresponding sources for other distributed Ceau platforms can be requested through the product's open-source notices page: https://ceaule.com/open-source.html.

Upstream source: https://github.com/videolan/vlckit/tree/4.0.0a19

Ceau Player support: ceaulestudio@gmail.com
