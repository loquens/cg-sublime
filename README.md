# cg-sublime

This is the original source code for cg-sublime project by [Chris Guilbeau](https://forum.sublimetext.com/u/chrisguilbeau) and (with high probability [chrisguilbeau](https://github.com/chrisguilbeau)), which was stored at [bitbucket](https://bitbucket.org/chrisguilbeau/cg-sublime), but is unavailable now.

Additional info could be found in [this post](https://forum.sublimetext.com/t/cg-sublime-commands-and-plugins/3120) at [Sublime forum](https://forum.sublimetext.com/).

Below goes text from original README.txt

---

**This content is released under the MIT License.**

## Current functions and keybindings

    status_info.py

This adds a little dirty/clean indicator along with telling you the files current encoding and line ending style

    super+alt+shift+left  : prev_group
    super+alt+shift+right : next_group

This works like the similar view commands, but allows you to navigate your layout with your keyboard

    super+down : forward_paragraph
    super+up   : backward_paragraph

These move you to the nearest end or beginning of a block of text

    super+alt+shift+c : clone_to_new_window

This opens the active file again in a new window

    super+o : prompt_open_file_path

This replaces "open_file" with an emacs like prompt where you can type the path, it also has tab completion

    super+shift+o : prompt_change_view

Lists all open "buffers" and when you select one, moves it front and center to your current group

    shift+f5 : sort_paragraphs

Works like sort_lines but with paragraphs (blocks of text)
