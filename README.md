# jstris-multilang

## Adding a new language
If you want to add your language to the game, clone this repository, copy the `en` directory and name the new directory according the [Language code reference](http://www.lingoes.net/en/translator/langcode.htm) ([lookup app](https://r12a.github.io/app-subtags/)), translate the files inside the new directory and issue a pull request. You may also send the files directly, if you don't want to use git.

## Modifying an existing language
Copy and translate the untranslated files from `en` or modify the current files in the directory of the language you want to modify.

## Translation files description
`game.php` - every language must have this file, covers most of the game interface

`frontend.php` - *(optional)* strings used only by the javascript game fronted

`web.php` - *(optional)* all other strings used on the website (user profiles, leaderboards, statistics, replays, etc.)
