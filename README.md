# Intro

This is my custom cook book based on [xcookybooky](https://www.ctan.org/pkg/xcookybooky). Beware, the main language is czech, therefore I'd recommend leaving this repo unless you want to deal with this weird-ass language.

Use with caution...

## Build instructions

A common problem is missing `lmodern.sty`. This can be solved by finding and installing the missing package: `sudo pacman -Fy lmodern.sty`. If this does not solve the issue, try also including package `lm`: `\usepackage{lm}`.

The ctan package [xcookybooky](https://www.ctan.org/pkg/xcookybooky) is kinda fucked up so the compilation throws at you some errors. Nevertheless the .pdf is output properly...
