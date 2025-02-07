# Pretty Localhost is Pretty

I never liked the default styling of localhost (does anyone?), so I redesign it!

## Before

![Localhost Before](before.png)

## After

![Localhost After](after.png)

## Installing

1. Download the repository and move the .dot files to your localhost directory – on OS X, that will be the `Sites` folder.
2. Done!

To toggle visibility of .dot's files, do this on Terminal:

    defaults write com.apple.finder AppleShowAllFiles -bool TRUE && killall Finder

To get back to the default behavior, just change `TRUE` to `FALSE`.

## Features

- **Such pixels!**
- Responsive
- Sort by name or modification date
- Show/hide hidden files
- Favicons

## Collaborating

If you have any suggestions, please create an [issue](https://github.com/edmundojr/localhost/issues) or fork the project and submit your pull request.

## Acknowledge

Code heavily taken from [this post](https://css-tricks.com/snippets/php/display-styled-directory-contents/) on CSS-Tricks. So hats off to [Chris Coyier](https://twitter.com/chriscoyier)!