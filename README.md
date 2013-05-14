vimperatorrc
============

My personal Vimperator RC file.

The colorscheme is based on vimPgray.vimp ( https://github.com/ronin13/seed/blob/master/.vimperator/colors/vimPgray.vimp ).

Things and stuff:
- Unbinds many of the default Firefox keys, such as ^t, ^T, ^w, etc.
- Remaps d to ^d
- Unmaps ^d
- Remaps u to ^u
- Unmaps ^u
- Remaps x to tabclose -select left
- Remaps X to undo
- Remaps ^x to tabclose -select right
- Remaps <A-x> to tablcose -select lastactive
- Unmaps ^i and ^o
- Maps ^[ to history previous
- Maps ^] to history forward
- Adds calculate command: passes arguments to Wolfram Alpha (you'll have to use URL encoding for math symbols).
- Adds translate command: passes arguments to Google Translate (from Japanese to English; I can't really figure out a fancier way to parse the input to determine source/destination languages).
- Adds tb command: toggles the tab bar on/off. This is deprecated, and actually needs to be removed.

-- Griffinhart

