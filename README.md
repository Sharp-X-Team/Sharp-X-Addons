# Sharp-X-Addons

Hello! This is the addon repository for the [LuaSTG Editor Sharp-X addon marketplace](https://github.com/Sharp-X-Team/LuaSTG-Editor-Sharp-X).
This repository only serves to store presets and custom nodes so they can be downloaded by Sharp-X directly.
If you have any questions, please come speak to us on the [Sharp-X discord server](https://discord.gg/bhM599npvd).

## Publishing your Preset/Node

// TODO

Please check that your addon doesn't contain folders. There should only be files inside your addon.

## Approval criteria

When the Sharp-X team checks the addons, they will check for the following:
- The `manifest.ini` format.
- The version is a whole number (example: 1, 2, 3, ...), we don't allow for decimal versions (example: 0.1, 1.4, 0.6).
- //TODO

## Submitting

- Fork this repository.
- In your fork, please create `Addons/<plugin name>/manifest.ini` using the following format:

  ```ini
  [<node/preset, depending on what you made>]
  Name = Example Addon
  Description = This is an example addon that does nothing.
  Owner = <Your name>
  Version = 1
  Icon = icon.png
  Changelog = Initial Release.
  ```

- If your addon doesn't have an icon, don't include the `Icon` tag.
- Create a PR.

## Updating your addon

Do the same as you would with the submitting process, but stay in the same folder.
(Please note that we won't merge your PR if you commited your existing addon in another folder.)