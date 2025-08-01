# winget

> Windows Package Manager.
> More information: <https://learn.microsoft.com/windows/package-manager/winget>.

- Install a package:

`winget {{[add|install]}} {{package}}`

- Remove a package (Note: `remove` can also be used instead of `uninstall`):

`winget {{[rm|uninstall]}} {{package}}`

- Display information about a package:

`winget show {{package}}`

- Search for a package:

`winget search {{package}}`

- Upgrade all packages to the latest versions:

`winget upgrade {{[-r|--all]}}`

- List all packages installed that can be managed with `winget`:

`winget {{[ls|list]}} {{[-s|--source]}} winget`

- Import packages from a file, or export installed packages to a file:

`winget {{import|export}} {{--import-file|--output}} {{path/to/file}}`

- Validate manifests before submitting a PR to the winget-pkgs repository:

`winget validate {{path/to/manifest}}`
