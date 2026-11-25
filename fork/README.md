# Fork backup

`themes/migrated-theme.json` is the active widget theme of this fork, kept here as a backup. It is not built into the app.

It differs from the built-in Classic theme in two ways:

- The Claude and Fable values use `usage_line_hm`, so the remaining time shows hours with minutes and days with hours (`46% · 2h50`, `72% · 1d03`).
- The Claude text layers are 8 px wider and the Fable column 10 px wider, so the widest text (`Fable 100% · 23h59`) fits.

To restore it, close the widget, copy the file to `%APPDATA%\ClaudeCodeUsageMonitor\themes\`, start the widget and choose **Migrated Theme** under **Settings > Appearance > Active theme**.
