# DEB Converter

## Introduction

DEB Converter is a powerful tool designed for converting `.deb` packages into formats suitable for Arch Linux (`.pkg.tar.zst`) and Red Hat Enterprise Linux (RHEL) distributions (`.rpm`). This utility simplifies the process of making Debian packages available to a broader range of Linux users, ensuring compatibility and ease of installation across different Linux environments..

## Features

- **Debian to Arch Conversion**: Convert `.deb` packages to Arch Linux's package format.
- **Debian to RHEL Conversion**: Transform `.deb` packages into RPM format for use in RHEL and its derivatives.
- **Automated Workflow**: Utilizes GitHub Actions to automate the conversion and packaging processes.
- **Checksum Generation**: Ensures integrity of the converted packages by generating MD5 checksums.

## Prerequisites

Before using DEB Converter, ensure that you have a `.deb` package file ready for conversion. and change the variables in the workflow

[real example (rust tauri)](https://github.com/don-cryptus/clippy)
