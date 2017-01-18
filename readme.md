# LyricFool

A command-line tool from finding lyrics.

## Installing

```
$ pip install lyricfool
```

## Usage
```
lyricfool --help
usage: lyricfool [-h] [-a ADAPTER] artist title

Gets lyrics from Genius, MetroLyrics, or LyricsWikia. Default: Genius. Add
'metro' or 'wikia' to your command to change adapters.

positional arguments:
  artist                Basic text / string value
  title                 Basic text / string value

optional arguments:
  -h, --help            show this help message and exit
  -a ADAPTER, --adapter ADAPTER
                        Basic text / string value
```

```
$ lyricfool "simon and garfunkel" "the boxer"

[Produced by Roy Halee, Paul Simon, Art Garfunkel]

[Verse 1]
I am just a poor boy though my story's seldom told
I have squandered my resistance for a pocketful of mumbles, such are promises
All lies and jest, still a man hears what he wants to hear
And disregards the rest, hmmmm

[Verse 2]
When I left my home and my family, I's no more than a boy
In the company of strangers
In the quiet of the railway station, runnin' scared, laying low
Seeking out the poorer quarters, where the ragged people go
Looking for the places only they would know

... you get the point it prints lyrics.
```

## Sources

By default it gets the lyrics from [Genius](https://genius.com). If you would prefer something else then adapters from MetroLyrics and LyricsWikia are available.
