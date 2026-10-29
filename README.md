# CollabX: team chat for Revit

**CollabX** puts your project team's conversation inside Autodesk Revit. It's an add-in by [X+1 Studio](https://xplus-studio.com).

- **Chat:** channels, @mentions, private direct messages and pop-up notifications.
- **Shared views:** share 3D views, plans, sections and sheets. Each comes with a snapshot, markup and 3D pins, and teammates jump to the same spot with one click.
- **Issues:** track issues as open or resolved.
- **Request Sync:** ask colleagues to sync and relinquish the elements you need. They answer with one click.
- **Model Log:** a team timeline of who added, modified or deleted what, and when.
- **Chat storage:** choose per project between a shared network folder, a small CollabX server, or inside the Revit model.

This repository hosts the **releases**. The installed add-in checks here once a day and updates itself.

## Install (Revit 2024)
1. Download **`CollabX-<version>-Revit2024.msi`** from the [latest release](https://github.com/XplusLab/CollabX/releases/latest).
2. Close Revit, then run the MSI. It installs for your Windows user only, with no admin rights needed.
3. Start Revit 2024 and click **Always Load** when asked about CollabX.

If your PC blocks MSI files, download the `.zip` instead, extract it, and double-click `Install-CollabX.cmd`.

## Updates
CollabX ▸ **Updates** shows the installed and latest versions.
- **Update** downloads the new MSI, checks it against the published `.sha256` checksum, and installs it when you close Revit.
- You can switch on fully automatic updates in the same window.

## Real-time server (optional)
Only needed for the "CollabX server" chat storage option. Download `CollabX.Server-<version>-win-x64.zip`, which runs without installing .NET, and follow its `README-SERVER.txt`.

## Support
info@xplus-studio.com · https://xplus-studio.com

## License
CollabX is licensed under the [Apache License 2.0](LICENSE). See [NOTICE](NOTICE) for attribution.
The X+1 Studio name and logo are trademarks of X+1 Studio and are not covered by the license.

© 2026 X+1 Studio
