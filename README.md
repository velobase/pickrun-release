# PickRun Desktop releases

This public repository contains the official PickRun Desktop installers,
checksums, software bills of materials (SBOMs), and release notes. The PickRun
application source remains in its private development repository.

## Download

Use the official download page:

**https://pickrun.ai/download**

The website selects the correct installer for your platform and links to assets
published in this repository. You can also inspect the
[latest release](https://github.com/velobase/pickrun-release/releases/latest).

## Verify a download

Every public release includes `SHA256SUMS.txt`. Compare the checksum of your
installer before opening it:

```text
shasum -a 256 <downloaded-file>
```

Signing and notarization status is stated in each release. Preview builds that
are not signed are labeled explicitly and must not be presented as stable
releases.

## Support

For product help, installation instructions, and security guidance, use
https://pickrun.ai/support.
