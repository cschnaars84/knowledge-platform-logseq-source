# Logseq DB QS corresponding source

This repository hosts the source release for the modified Logseq DB service
used in the personal, synthetic QS evaluation. The runtime image is the
private OCI digest
`sha256:cc493d0d9c2d510b1063374a8fede94c85ba61fb096d8379ff0e514a541614a1`.

**Download the source:** [QS rc3 source release](https://github.com/cschnaars84/knowledge-platform-logseq-source/releases/tag/qs-rc3-cc493d0).
The release asset `logseq-rc3-corresponding-source-v2.tar.gz` has SHA-256
`cbe17174aeb866da65164f31ff6a8fba66a6252efb566d4cee8f6a55ce2af070`.
Its companion checksum file and the archive's `README.md` describe the pinned
Logseq and mldoc source, patches, build scripts, dependencies, provenance,
SBOM and license notices. The source is available without charge or login.

The pinned `mldoc@1.5.9` source has conflicting license metadata: its npm/JS
manifest says ISC, while its source tree contains an AGPL-3.0 license text and
an LGPL file notice. This release preserves the source and all observed
notices without relabeling upstream code. It does not claim that the license
interpretation or later customer deployment has received legal sign-off.

Keep this exact source release available for as long as the corresponding
modified rc3 service is offered to network users.
