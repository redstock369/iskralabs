# iskralabs

iskralabs is a remote support application (remote control, file transfer, chat,
unattended access) with an English and Serbian interface.

It is a rebranded build of **RustDesk** (https://github.com/rustdesk/rustdesk),
imported from upstream commit a7f2260, and is distributed under the same
**GNU Affero General Public License v3.0** (see `LICENCE`). Changes from upstream:

- application name `iskralabs` (`libs/hbb_common/src/config.rs`), Windows metadata and icons
- language menu limited to English and Serbian (`src/lang.rs`)
- CI reduced to a Windows x64 build (`.github/workflows/iskralabs-windows.yml`)

Connections currently use the public RustDesk rendezvous/relay servers.
