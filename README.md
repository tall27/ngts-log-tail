# NGTS Log Tail

A local tool that shows real-time Certificate Operations logs from Strata
Cloud Manager. Created with care by Tal Kushnirsky, and distributed as-is.

## Download

Grab the latest release for your platform below, verify the checksum against
`SHA256SUMS.txt`, and run it:

- **Windows**: unzip, then run `ngts-log-tail.exe`
- **macOS (Apple Silicon)**: extract the `darwin-arm64` tarball, then run `./ngts-log-tail`
- **macOS (Intel)**: extract the `darwin-amd64` tarball, then run `./ngts-log-tail`

The app opens your browser to a local page and tails activity logs directly
from your machine — no cloud endpoint stays running while you use it.

Usage reporting (tenant ID, IP, version -- never credentials) is on by
default; run with `-no-telemetry` to disable it. See `-help` for all options.

This repository holds release binaries only, not source.
