## [中文](./README_TC.md)

# Hentaium

Hentaium is a browser based on Chromium.

It's designed to play web games without pain.

This means the browser will no longer throttle background tabs,    
even if you switch to another tab or minimize the window,
the game will continue to run smoothly in the background.

So you no longer need to change Chrome/Firefox settings 
to avoid background throttling!

## Features

1. No background throttling
2. Manifest V2 extensions

**Cause Hentaium does not support the Chrome sync feature, 
so you must import your bookmarks manually.**

## Version

Hentaium currently uses Chromium M138 LTS as its base.

## Compiling

The workflow is the same as described in the Chromium build docs, 
but you need to apply custom patches with `git am` or `git apply`.

### Predecessor

[Just a game browser](https://github.com/c0re100/just_a_game_browser)