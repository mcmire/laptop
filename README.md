# laptop

This repo bootstraps a new Mac optimized for web development.

## [What's in the box?][se7en]

[se7en]: https://www.youtube.com/watch?v=1giVzxyoclE&feature=youtu.be&t=122

### Applications

* **[iTerm]** — a more capable terminal than Terminal.app ([see notes][iterm])
* **Google Chrome** — the new Internet Explorer
* **Firefox** — for when Chrome doesn't work
* **Slack** — everyone's favorite chat app
* **[1Password]** — a slick password manager
* **[Simplenote]** — a small but mighty cross-platform notes app
* **[Spectacle]** — a way to place your windows with hotkeys
* **[Stay]** — saves and restores locations of windows after switching monitors
* **[Amphetamine]** — keeps your computer from going to sleep
* **[Numi]** — a more capable and pleasant calculator app
* **[Dropbox]** — everyone's favorite cloud storage service
* **Visual Studio Code** — when you don't feel like using Vim
* **Microsoft To Do** — everyone's favorite replacement for Wunderlist

[1Password]: https://1password.com/
[Spectacle]: https://www.spectacleapp.com/
[Stay]: https://cordlessdog.com/stay/
[Numi]: https://numi.app/
[Dropbox]: https://www.dropbox.com/
[Amphetamine]: https://apps.apple.com/us/app/amphetamine/id937984704
[Simplenote]: https://simplenote.com/

### Command-line tools

* **[ngrok]** — expose a local server for remote access
* **[heroku]** — interact with Heroku-deployed apps

[iTerm]: https://www.iterm2.com/
[ngrok]: https://ngrok.com/
[heroku]: https://github.com/heroku/cli

### Databases

* **PostgreSQL** — the fully capable opensource database
* **Redis** — the fully capable ultra-light cache store
* **SQLite** — the pocket, ultra embeddable database

## iTerm configuration

iTerm is preconfigured to use [Solarized] as the color set
and [Fira Code] as the font.

### More on Solarized

I've chosen Solarized
because it is a color scheme
that has both dark and light modes.
Furthermore,
it is one of the only color schemes I know
which has been finely crafted using light/perception theory
so that dark and light are basically identical aside from a few colors.

Solarized support is implemented in iTerm
by adding two [Dynamic Profiles][iterm-dynamic-profiles]
for dark and light modes.
These profiles are installed as a symlink at
`~/Library/Application Support/iTerm2/DynamicProfiles/profiles.plist`.

### More on Fira Code

I've chosen Fira Code
because it uses ligatures to represent combinations of symbols that are frequently used in code
(`->`, `...`, and `|>`, just to name a few).
This means that they appear as one character
instead of multiple characters,
thereby making it easier to scan code.

[Solarized]: https://github.com/altercation/solarized
[Fira Code]: https://github.com/tonsky/FiraCode
[iterm-dynamic-profiles]: https://www.iterm2.com/documentation-dynamic-profiles.html
[ligatures]: https://www.fonts.com/content/learning/fontology/level-3/signs-and-symbols/ligatures-1

## Installation

Simply run:

    bin/install
