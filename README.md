## Introduction

"Ruby-tailgate" is a layout manager, event handler and widget library for creating innovative and elegant text-based UIs and applications with multiple windows.

It is written in Ruby, it is text/terminal/console/TUI/CUI/CLI-based and it aims to compete with Node.js 'blessed' and 'blessed-contrib'.

### Goals:

* Be extremely quick/efficient/convenient for the user
* Be versatile such as blessed and blessed-contrib for Node.js
* Do not reinvent core ideas; use established principles from Qt, STFL, etc.
* Be better than existing Ruby solutions, which are lagging behind

## Features

* Layout manager with automatic placement (like e.g. Qt), configurable widget expansion and sticking to borders
* Layout manager is separate from drawing (you can use layout manager only, for calculating positions)
* Window resizing support
* Keyboard and mouse support
* Completely object-oriented
* High-level (no manual Curses or ANSI drawing or coloring)
* Callbacks support (no need for manual updates)
* Solid widget library
* Wide-character support

## Other Projects

There are other projects marginally related to this one.
I am listing them here simply for comprehensiveness, not because they necessarily even serve the same purpose.

* In Ruby (for curses or colors): ruby-curses
* In Ruby (for text tables): text_layout, text-table, pretty_table, terminal-table
* In Ruby (for CSS-like terminal layout engine): terminal-layout
* In other languages: STFL, Curses::UI, urwid
* For layouts in Tmux: https://changelog.com/teamocil-ruby-yaml-tmux-layouts/
* For CSS parsing and matching: css_parser
