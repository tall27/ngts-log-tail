# NGTS Log Tail

A local tool that shows real-time Certificate Operations logs from Strata
Cloud Manager. Created with care by Tal Kushnirsky, and distributed as-is.

## Demo

[![NGTS Log Tail demo](https://img.youtube.com/vi/_KIzuIaZG4Y/maxresdefault.jpg)](https://youtu.be/_KIzuIaZG4Y)

## Download (v1.0.3t)

Grab the file for your platform below, verify the checksum against
[`SHA256SUMS.txt`](https://raw.githubusercontent.com/tall27/ngts-log-tail/main/downloads/SHA256SUMS.txt),
and run it:

- **Windows**: [ngts-log-tail-1.0.3t-windows-amd64.zip](https://raw.githubusercontent.com/tall27/ngts-log-tail/main/downloads/ngts-log-tail-1.0.3t-windows-amd64.zip) — unzip, then run `ngts-log-tail.exe`
- **macOS (Apple Silicon)**: [ngts-log-tail-1.0.3t-darwin-arm64.tar.gz](https://raw.githubusercontent.com/tall27/ngts-log-tail/main/downloads/ngts-log-tail-1.0.3t-darwin-arm64.tar.gz) — extract, then run `./ngts-log-tail`
- **macOS (Intel)**: [ngts-log-tail-1.0.3t-darwin-amd64.tar.gz](https://raw.githubusercontent.com/tall27/ngts-log-tail/main/downloads/ngts-log-tail-1.0.3t-darwin-amd64.tar.gz) — extract, then run `./ngts-log-tail`

The app opens your browser to a local page and tails activity logs directly
from your machine — no cloud endpoint stays running while you use it.

Usage reporting (tenant ID, IP, version -- never credentials) is on by
default; run with `-no-telemetry` to disable it. See `-help` for all options.

This repository holds release binaries only, not source.
