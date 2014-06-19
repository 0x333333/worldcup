worldcup
========

Forked from [simoami/worldcup](https://github.com/simoami/worldcup).

Inspired from the python version of [worldcup](https://github.com/fatiherikli/worldcup).

The hacker's way to get worldcup scores!

![pic](https://dl.dropboxusercontent.com/u/107773577/Blog%20pics/Screen%20Shot%202014-06-19%20at%2012.51.54%20PM.png)

### Installation

[Node.js](http://nodejs.org/) and [NPM](https://www.npmjs.org) are required in order to install the woldcup command.

```bash
npm install nodeworldcup -g
```

The flag `-g` ensures that the worldcup command is installed and accessible globally.


### Command usage

```bash
$ nodeworldcup -h

  Usage: nodeworldcup [current] [today] [tommorow]

  Options:

    -h, --help     output usage information
    -V, --version  output the version number
```

```bash
$ nodeworldcup current

Current match:

Uruguay                    1 - 0                    England
-----------------------------------o-----------------------
⚽  Being played now: an hour gone
```

```bash
$ nodeworldcup today

Today's matches:

Colombia                   2 - 1                Ivory Coast
-----------------------------------------------------------
⚽  Played Today at 9:00 AM. Colombia won

Japan                      0 - 0                     Greece
-----------------------------------------------------------
⚽  Will be played Today at 3:00 PM

Uruguay                    1 - 0                    England
----------------------------------o------------------------
⚽  Being played now: an hour gone
```

```bash
$ nodeworldcup tomorrow

Tomorrow's matches:

Italy                      0 - 0                 Costa Rica
-----------------------------------------------------------
⚽  Will be played Tomorrow at 9:00 AM

Switzerland                0 - 0                     France
-----------------------------------------------------------
⚽  Will be played Tomorrow at 12:00 PM

Honduras                   0 - 0                    Ecuador
-----------------------------------------------------------
⚽  Will be played Tomorrow at 3:00 PM
```

LICENSE

[MIT](https://github.com/jesusjzp/worldcup/blob/master/LICENSE) License.
