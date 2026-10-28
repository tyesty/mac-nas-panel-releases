# mac-nas-panel releases

Installer packages for mac-nas-panel, a web interface that
turns a Mac into a file server: shares, users, NFS exports, services, backups and shared links.

## Installing

1. Open the [latest release](../../releases/latest) and download `mac-nas-panel-<version>.pkg`.
2. Double-click it and follow the Installer.
3. When it is done, allow the helper Full Disk Access as the last page explains.

Requires macOS 14 Sonoma or later.

Until the packages are signed by Apple, macOS refuses to open a downloaded package at first
("unidentified developer"). Open it anyway once: on macOS 14 by right-clicking it and choosing
Open, on macOS 15 and later under System Settings › Privacy & Security › Open Anyway.

## Updates

Installed copies find new versions here by themselves: the menu bar app and the admin
interface offer them with one click. Every release carries an `update.json` signed with the
project's key; a package that does not match it is never installed.

## Licence

[PolyForm Noncommercial 1.0.0](https://polyformproject.org/licenses/noncommercial/1.0.0) – free to
use, but not to make money with.
