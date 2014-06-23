worldcup
========

Forked from [simoami/worldcup](https://github.com/simoami/worldcup).

Inspired from the python version of [worldcup](https://github.com/fatiherikli/worldcup).

Thanks for the API provided by [Software for good](http://softwareforgood.com/soccer-good/).

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

  Usage: nodeworldcup [current] [today] [tommorow] [groups]

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

```bash
$ nodeworldcup groups

W  :Wins
D  :draws
L  :losses
GF :Goals for
GA :Goals against
KO :Knocked out

GROUP A
Teams                          W   D   L   GF   GA   KO
-----------------------------------------------------------
Brazil                         1   1   0   3    1    false
Mexico                         1   1   0   1    0    false
Croatia                        1   0   1   5    3    false
Cameroon                       0   0   2   0    5    false

GROUP B
Teams                          W   D   L   GF   GA   KO
-----------------------------------------------------------
Chile                          2   0   0   5    1    false
Netherlands                    2   0   0   8    3    false
Australia                      0   0   2   3    6    false
Spain                          0   0   2   1    7    false

...
```

### LICENSE

[MIT](https://github.com/jesusjzp/worldcup/blob/master/LICENSE) License.
