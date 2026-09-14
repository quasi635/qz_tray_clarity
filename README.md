# QZ Tray

[![Build Status](https://github.com/qzind/tray/actions/workflows/build.yaml/badge.svg)](../../actions) [![Downloads](https://img.shields.io/github/downloads/qzind/tray/latest/total.svg)](../../releases) [![Issues](https://img.shields.io/github/issues/qzind/tray.svg)](../../issues) [![Commits](https://img.shields.io/github/commit-activity/m/qzind/tray.svg)](../../commits)

Browser plugin for sending documents and raw commands to a printer or attached device

## Getting Started

- Download here https://qz.io/download/
- See our [Getting Started](../../wiki/getting-started) guide.
- Visit our home page https://qz.io.

## Support

- File a bug via our [issue tracker](../../issues)
- Ask the community via our [community support page](https://qz.io/support/)
- Ask the developers via [premium support](https://qz.io/contact/) (fees may apply)

## Changelog

- See our [most recent releases](../../releases)

## Java Developer Resources

- [Install dependencies](../../wiki/install-dependencies)
- [Compile, Package](../../wiki/compiling)

## Build

### Mac (ARM)

```
ant pkgbuild -Dtarget.arch=aarch64 -Dauthcert.use="clarity_certs/cert.pem"
```

### Mac (Intel)

```
ant pkgbuild -Dauthcert.use="clarity_certs/cert.pem" -Dtarget.arch=x86_64
```

### Windows (x86)

```
ant nsis -Dtarget.arch=x86_64 -Dauthcert.use="clarity_certs/cert.pem"
```

### Windows (ARM)

```
ant nsis -Dtarget.arch=aarch64 -Dauthcert.use="clarity_certs/cert.pem"
```
