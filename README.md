# ravkit-releases

Public downloads and update files for Ravkit Desktop, the free video, audio, image and PDF tools that run on your own computer.

- Website: https://ravkit.theonefolio.com/desktop/
- Latest download: https://github.com/Theonefolio/ravkit-releases/releases/latest

## Installing from a package manager

The Windows installer is not code signed yet, so downloading it by hand makes SmartScreen show a warning
(choose More info, then Run anyway). Package managers check the file against a fixed fingerprint instead.

**Scoop**

```
scoop bucket add ravkit https://github.com/Theonefolio/ravkit-releases
scoop install ravkit
```

Scoop updates (`scoop update ravkit`) are picked up from this bucket. The app also updates itself.

Every file in each release is built by GitHub Actions from the source of the Ravkit project and the installer's
SHA-256 is listed in the package manifests.
