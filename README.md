# Athena101

Athena101 is a UCI-compatible chess-engine development project for local analysis, testing, and online play.

## Build on macOS

Download the required neural-network file:

    make -C src net

Build for Apple Silicon:

    make -C src -j4 build ARCH=apple-silicon

For an Intel Mac, use `ARCH=native` instead.

## Source and licensing

This repository includes third-party software. Preserve applicable source notices and license files. See `THIRD_PARTY_NOTICES.md`, `AUTHORS`, and `Copying.txt`.
