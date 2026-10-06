# PostPerfection

Free, open-source DCP and IMF tools for cinema and streaming deliveries. No dongles, no subscriptions, no watermarks. Windows, macOS, and Linux.

**Full site with downloads and docs: [postperfection.github.io](https://postperfection.github.io/)**

## The apps

- **[DCP Wizard](https://postperfection.github.io/dcpwizard/)**: make DCPs. SMPTE and Interop, 2K and 4K, subtitles and closed captions, encryption with KDMs, verified copies to cinema drives. [Download](https://github.com/PostPerfection/dcpwizard/releases/latest)
- **[DCP Doctor](https://postperfection.github.io/dcpdoctor/)**: check DCPs and IMF packages. Structure, hashes, subtitles, audio, HDR, encryption, and compatibility checks for Dolby, Barco, Christie, GDC, and IMAX servers. [Download](https://github.com/PostPerfection/dcpdoctor/releases/latest)
- **[IMF Wizard](https://postperfection.github.io/imfwizard/)**: deliver to streamers. Netflix, Amazon, and Dolby presets, Dolby Vision, HDR10+, Atmos, supplemental packages, IMF to DCP conversion. [Download](https://github.com/PostPerfection/imfwizard/releases/latest)

You can also [check a DCP in your browser](https://postperfection.github.io/dcpdoctor/validate/) without installing anything. Files are never uploaded.

## For developers

The apps are built in Rust on shared libraries: [postkit](https://github.com/PostPerfection/postkit) (encoding, packaging, QC building blocks), [guikit](https://github.com/PostPerfection/guikit) (the desktop apps' shared preview player and panels), [asdcplib-rs](https://github.com/PostPerfection/asdcplib-rs) (safe Rust bindings for AS-DCP/AS-02 MXF), and [dci-ctp](https://github.com/PostPerfection/dci-ctp) (a DCI compliance test suite).

---

© 2026 Grok Image Compression Inc. · Licensed under the [GNU AGPL-3.0](https://www.gnu.org/licenses/agpl-3.0.html)
