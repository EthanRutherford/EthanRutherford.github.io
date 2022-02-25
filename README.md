# Ethan Rutherford's projects

## npm packages

### [fast-fuzzy](https://github.com/EthanRutherford/fast-fuzzy)
`fast-fuzzy` is an npm library implementing levenshtein-based fuzzy string
matching for large candidate sets. I've gradually improved the performance over the years, and currently it is capable searching
candidate sets of 10s of thousands of strings and return results in tens of milliseconds.

The motivating use case for this library was client-side autocomplete, and it has been put to good use to build user mention searchboxes
and emoji pickers, as well as a variety of other applications such as searching a set for groups of near-identical strings.

### [emoji](https://github.com/EthanRutherford/emoji)
This small repo contains code which fetches data from both github's api and the official unicode CLDR datasets to provide
a list of emoji with shortnames, official categories, official keywords, and fitzpatrick skin tone metadata. The result is then published to npm.

I created this in order to build a full featured emoji picker, after discovering that there was no official source of shortnames, and the
existing libraries out there had names and keywords (if they even had them) that were created mostly by the author, and many did not provide
all the metadata that I wanted. I decided to use github's list of emoji shortnames for their familiarity.

Utilizing fast-fuzzy for the search, the picker featured a popup with emoji grouped by category, which could be searched by name or keyword,
and supported customizing the skin tone of emoji which support fitzpatrick modifiers.

## Games

### [sudoku](https://github.com/EthanRutherford/sudoku)
A PWA sudoku webapp, with a puzzle generator, difficulty ranking system, and fastest time tracking. I was unhappy with the solitaire apps on
various appstores, as they were generally chock-full of ads and I felt their ranking systems were wildly inconsistent.

### [jigsaw](https://github.com/EthanRutherford/jigsaw)
A PWA app for creating and putting together jigsaw puzzles. Given any input image and desired piece count, will generate a set of
puzzle pieces that can be dragged and rotated, and will connect into groups when neighboring pieces are placed together correctly.

It also includes a multiplayer mode, where multiple users can work on the same puzzle together.

### [solitaire](https://github.com/EthanRutherford/solitaire)
Another PWA app, this time for playing various solitaire games. Microsoft's solitaire games were once a great way to kill some time for free,
but have in recent years become infested with unskippable video ads and pointless "experience points" and leveling, and has the audacity to
request a *monthly subscription* to play without ads!

At time of writing, solitaire is still a work in progress, which I am actively developing. However, it is live and playable, and contains multiple
different solitaire games.

## Other projects
[Click here](https://github.com/EthanRutherford?tab=repositories) to view the full list of repositories on my github page, such as boxjs, a 2D
physics engine in javascript, or 2d-gl, an attempt at making a 2D focused rendering engine using webgl.

There are also a number of other games which never came to fruition.
