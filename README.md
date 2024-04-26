# Nyxt Browser Reference Card

| Keybinding | Command | Description |
|------------|---------|-------------|
| `Ctrl+g` | `escape` | Cancel current action or command. |
| `Ctrl+l` | `set-url` | Prompt to set the URL of the current buffer. |
| `Ctrl+t` | `make-buffer` | Create a new buffer. |
| `Ctrl+w` | `delete-buffer` | Close the current buffer. |
| `Ctrl+r` | `reload-current-buffer` | Reload the page in the current buffer. |
| `Ctrl+space` | `execute-command` | Execute any command by name. |
| `Ctrl+j`, `Ctrl+k` | `scroll-down`, `scroll-up` | Scroll the page up and down. |
| `Alt+left`, `Alt+right` | `history-backwards`, `history-forwards` | Navigate backward and forward in history. |
| `Ctrl+x b` | `switch-buffer` | Switch between open buffers. |
| `Ctrl+x C-b` | `list-buffers` | Display a list of all open buffers. |
| `Ctrl+i` | `autofill` | Fill in a field with a value from a saved list. |
| `Ctrl+f` | `search-buffer` | Search incrementally on the current buffer. |
| `Alt+f` | `remove-search-marks` | Remove all search marks. |
| `Ctrl+J` | `follow-hint-new-buffer` | Like `follow-hint`, but open the selected hints in new buffers (no focus). |
| `Ctrl+j` | `follow-hint` | Prompt for element hints and open them in the current buffer. |
| `Ctrl+Alt+j` | `follow-hint-nosave-buffer-focus` | Like `follow-hint-nosave-buffer`, but with focus. |
| `Alt+c h` | `copy-hint-url` | Prompt for element hints and save its corresponding URLs to clipboard. |
| `Ctrl+u Ctrl+j` | `follow-hint-new-buffer-focus` | Like `follow-hint-new-buffer`, but with focus. |
| `Ctrl++` | `zoom-page` | Zoom in the current page. |
| `Ctrl+0` | `reset-page-zoom` | Reset the zoom to the default ratio. |
| `Ctrl+R` | `reload-with-modes` | Reload the buffer with the queried modes. |
| `Ctrl+Z` | `redo` | Redo the last editing action. |
| `Ctrl+a` | `select-all` | Select all the text in the text field. |
| `Ctrl+c` | `copy` | Copy selected text to clipboard. |
| `Ctrl+h` | `jump-to-heading` | Jump to a particular heading, of type h1 to h6. |
| `Ctrl+p` | `print-buffer` | Print the current buffer. |
| `Ctrl+v` | `paste` | Paste from clipboard into active element. |
| `Ctrl+x` | `cut` | Cut the selected text. |
| `Ctrl+z` | `undo` | Undo the last editing action. |
| `Alt+.` | `headings-panel` | Display a list of headings for jumping. |
| `Alt+{`, `Alt+}` | `previous-heading`, `next-heading` | Scroll to the previous or next heading. |
| `End` | `maybe-scroll-to-bottom` | Scroll to bottom if no input element is active. |
| `Home` | `maybe-scroll-to-top` | Scroll to top if no input element is active. |
| `Ctrl+Alt+Z` | `passthrough-mode` | Toggle `passthrough-mode`. |
| `Ctrl+Alt+c` | `open-inspector` | Open the inspector to inspect and change the buffer's content. |
| `Ctrl+Alt+h` | `jump-to-heading-buffers` | Jump to a particular heading across a set of buffers. |
| `Ctrl+b` | `list-bookmarks` | List all bookmarks in a new buffer. |
| `Ctrl+d` | `bookmark-current-url` | Bookmark the URL of the current buffer. |
| `Ctrl+m g` | `bookmark-hint` | Prompt for element hints and bookmark them. |
| `Ctrl+m k` | `delete-bookmark` | Delete bookmarks matching chosen URLs or entries. |
| `Ctrl+m l` | `bookmark-url` | Prompt for a URL to bookmark. |
| `Ctrl+m o` | `set-url-from-bookmark` | Set the URL for the current buffer from a bookmark. |
| `Ctrl+o` | `open-file` | Open a file from the filesystem. |
| `Ctrl+q` | `quit` | Quit Nyxt. |
| `Ctrl+n` | `make-window` | Create a new window. |
| `Alt+r` | `reload-buffers` | Prompt for BUFFERS to be reloaded. |
| `Alt+w` | `delete-window` | Delete the queried window(s). |
| `f11` | `toggle-fullscreen` | Fullscreen WINDOW, or the current window, when omitted. |
| `f1 a` | `describe-any` | Inspect anything and show it in a help buffer. |
| `f1 b` | `describe-bindings` | Show a list of all available keybindings in the current buffer. |
| `f1 c` | `describe-command` | Inspect a command and show it in a help buffer. |
| `f1 f` | `describe-function` | Inspect a function and show it in a help buffer. |
| `f1 k` | `describe-key` | Display binding of user-inputted keys. |
| `f1 p` | `describe-package` | Inspect a package and show it in a help buffer. |
| `f1 r` | `manual` | Display Nyxt manual. |
| `f1 s` | `describe-slot` | Inspect a slot and show it in a help buffer. |
| `f1 t` | `tutorial` | Display Nyxt tutorial. |
| `f1 v` | `describe-variable` | Inspect a variable and show it in a help buffer. |
| `Shift+f4` | `delete-all-panel-buffers` | Delete all the open panel buffers in WINDOW. |
| `Ctrl+Shift+Y` | `list-downloads` | Display a buffer listing all downloads. |
