## Introduction

"Ruby-tailgate" is a layout manager, event handler and widget library for creating innovative and elegant text-based UIs and applications with multiple windows.

It is written in Ruby, it is text/terminal/console/TUI/CUI/CLI-based and it aims to compete with Node.js 'blessed' and 'blessed-contrib' libraries.

### Goals:

* Be extremely quick/efficient/convenient for the user
* Be versatile like blessed and blessed-contrib for Node.js
* Do not reinvent core ideas; use established principles from Qt, STFL, etc.
* Be better than existing Ruby solutions, which are lagging behind

## Features

* Layout manager with automatic placement (like e.g. Qt), configurable widget expansion, and configurable alignment/sticking to borders
* Layout manager is separate from drawing (you can use layout manager only, for calculating positions and sizes)
* Window resizing support
* Keyboard and mouse support
* Configurable focusing order
* Completely object-oriented
* High-level (no manual Curses or ANSI drawing or coloring)
* Callbacks support (no need for manual updates)
* Solid widget library
* Wide-character support

### Missing items:

Of the above list, the following items do not work yet and are in development:

* Keyboard and mouse support (there is no event loop yet, and no handling of any keyboard or mouse events)
* Configurable focusing order - focusing does not exist yet
* Callbacks support - no callbacks implemented yet
* Solid widget library - no comprehensive widget set yet

### Execution priorities:

* Implement table-based layout (in addition to existing box-based horizontal and vertical layouts)
* Implement callbacks
* Implement basic event loop / keyboard support
* Implement focusing
* Improve LineEdit and Checkbox widgets
* Improve rendering, like in border/end of box/window conditions
* Implement List, Textedit and Textview widgets
* Implement mouse support
* Make it all work solid, then move onto more advanced topics

## Other Projects

There are other projects marginally related to this one.
I am listing them here simply for comprehensiveness, not because they necessarily even serve the same purpose.

* In Ruby (for curses or colors): ruby-curses, IO.console, rainbow, colorize, paint
* In Ruby (for text tables): text_layout, text-table, pretty_table, terminal-table
* In Ruby (for CSS-like terminal layout engine): terminal-layout
* In Ruby (for various helpers): pazdera's catpix, tco and word_wrap (article: http://radek.io/2015/06/29/catpix/)
* In Ruby (for graphics): rmagick
* In other languages: STFL, Curses::UI, urwid
* For layouts in Tmux: https://changelog.com/teamocil-ruby-yaml-tmux-layouts/
* For CSS parsing and matching: css_parser
