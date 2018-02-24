<div align="center">
    <img src="https://wontfix.club/limbo/logo.png">
    <h1>limbo</h1>
</div>

limbo `/ˈlɪmboʊ/` is a third-party repository for [Discord Selfbot]()
COGs (plugins).

This repository has been created as a solution to overcome the
problem with Discord Selfbot admins. They don't want to accept these plugins
into the official repositories so no fingers get pointed at them. <a href="https://github.com/LyricLy/ASCII/pull/103#issuecomment-362662934"><sup>Source</sup></a>

Limbo contains a patcher which allows access to this unofficial repository
containing these COGs which were sadly declined into the official repositories.

**Important:** This repository has been created as a home for declined plugins, including
abusive plugins that are not complaint with Discords Terms of Service. Use
this repository and any COGs in this repository at your own risk.

## Features

* Patched `cog_download.py` which allows downloading from both ASCII and Limbo repositories
* Alternative repository to ASCII
* Independent COG hosting from Appu and his repository
* Home for declined COGs
* Doesn't care about "getting fingers pointed at" - this repository allows COGs that are not complaint with the Discord ToS

## Installation

Limbo can be accessed using the patched `cog_download.py`.

```bash
$ cd Discord-Selfbot/cogs
$ rm -rf cog_download.py
$ wget https://raw.githubusercontent.com/Marc3842h/limbo/master/limbo/cog_download.py
# Restart your selfbot
```

## Usage

After Limbo's patched `cog_download.py` has been installed, all COGs from the ASCII
and from this Limbo repository can be accessed using the normal `cog` command.

Default: `>cog list`

## Contributing

All contributions are welcomed and appreciated.

#### Bug Reports

Please use the [issue tracker](https://github.com/Marc3842h/limbo/issues) to report any bugs or file feature requests.

#### Developing

Pull Requests are welcome.

#### Donations

Donations are appreciated. Feel free to become a Patreon on my [Patreon](https://www.patreon.com/marc3842h).

## License

Limbo is licensed under the [MIT license](https://github.com/Marc3842h/limbo/blob/master/LICENSE.txt).
The logo on top of this document was made by Freepik from Flaticon and licensed under CC 3.0 BY.
The original `cog_download.py` was made by Appu licensed under GPL-3.0.
All the cogs belong to their original authors.
