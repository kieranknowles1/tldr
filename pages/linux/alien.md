# alien

> Convert different installation packages to other formats.
> See also: `debtap`, for `.deb` conversion on Arch Linux.
> More information: <https://manned.org/alien>.

- Convert a specific installation file to Debian format (`.deb` extension):

`sudo alien {{[-d|--to-deb]}} {{path/to/file}}`

- Convert a specific installation file to Red Hat format (`.rpm` extension):

`sudo alien {{[-r|--to-rpm]}} {{path/to/file}}`

- Convert a specific installation file to a Slackware installation file (`.tgz` extension):

`sudo alien {{[-t|--to-tgz]}} {{path/to/file}}`

- Convert a specific installation file to Debian format and install on the system:

`sudo alien {{[-d|--to-deb]}} {{[-i|--install]}} {{path/to/file}}`
