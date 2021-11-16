# US-BR

This is a fork of the US-intl layout that comes with standard X11. It's aimed at portuguese speaking programmers.

## Differences from US-intl

- ~, ` and ^ are now dead keys: Portuguese heavily relies on those two characters for accentuation, so it's easier to use them for that purpose mainly.

- ' and " are still dead keys: Most programming languages use both of these characters for strings. Portuguese layouts use them for accentuation (á and ü for example), but US-intl provides us this functionality through Alt+Letter (Alt+A == á), which is more ergonomic in my opinion.

## How to use this

1. Clone this repository somewhere (or just download the us-br file)
2. Run `xmodmap /path/to/us-br` (preferably through an init script)
