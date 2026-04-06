# rngames
a directory of web-based RNG, gacha, and incremental games

https://auth1ery.github.io/rngames/

# what belongs here?

specifically "web-games" where randomness is a core mechanic, such as RNG Pulls, gacha systems, clickers, prestige loops and anything in-between.

# submitting a game

we don't bite with PRs!

edit the file thats in: `data/games.json` as follows:

when making a new game, copy and paste the code as follows:

```
  {
    "name": "YOUR_GAME_NAME",
    "url": "YOUR_LINK",
    "description": "YOUR_DESCRIPTION",
    "author": "YOUR_NAME",
    "tags": ["TAG"],
    "openSource": FALSE_OR_TRUE
  }
```
- `"name"` is the name of your game.
- `"url"` is the URL of your game. NOT the repo link, the playable game link.
- `"description"` is how you would describe the game.
- `"author"` is your name or alias you come by
- `"tags"` choose a tag or use them all: rng, incremental, gacha, or idle
- `"openSource"` is when if your site is open source or not. choose between `true` and `false`.

after you insert the JSON block and fill out the gaps, make sure to put an `,` on the game before your game, preferably after the last `}`.

like so:

```
{
    "name": "Cool Game",
    "url": "https://coolgame.com",
    "description": "A game about stuff.",
    "author": "coolperson",
    "tags": ["rng", "idle"],
    "openSource": true
  }, <-- ADD A COMMA!
  {
    "name": "YOUR_GAME_NAME",
    "url": "YOUR_LINK",
    ...
  }
```
> don't copy paste this exact by the way. this is just an example

then submit a pull request! the commit name can be anything, it could be "quackadoodle" or you can boringly make it "added my game"

# other info

data (`games.json`) is [CC0](https://creativecommons.org/publicdomain/zero/1.0/), and site code is [GPL-3.0 license](https://www.gnu.org/licenses/gpl-3.0.html).
