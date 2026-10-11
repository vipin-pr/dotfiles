# tmux Keybindings Reference

**Prefix:** `Ctrl-b`

## Window Management

| Keybinding | Action |
|---|---|
| `Prefix` + `w` | Open window chooser |
| `Prefix` + `r` | Rename current window |
| `Prefix` + `e` | Confirm and close current window |
| `Prefix` + `v` | Run window naming script |
| `Ctrl-Shift-Left` (No prefix) | Move window left |
| `Ctrl-Shift-Right` (No prefix) | Move window right |

## Pane Management

| Keybinding | Action |
|---|---|
| `Prefix` + `h` | Move to left pane |
| `Prefix` + `j` | Move to pane below |
| `Prefix` + `k` | Move to pane above |
| `Prefix` + `l` | Move to right pane |
| `Prefix` + `-` | Split horizontally (top/bottom) |
| `Prefix` + `\|` | Split vertically (left/right) |
| `Prefix` + `y` | Toggle synchronized panes |

## Copy Mode & Scrolling

| Keybinding | Action |
|---|---|
| `Prefix` + `[` | Enter copy mode |
| `v` (Copy mode) | Begin text selection |
| `y` (Copy mode) | Copy selection and exit copy mode |

## Configuration

| Keybinding | Action |
|---|---|
| `Prefix` + `o` | Reload `~/.tmux.conf` |

## Appearance & Settings

| Setting | Description |
|---|---|
| Terminal | `xterm-256color` |
| Scrollback history | 40,000 lines per pane |
| Mouse support | Enabled |
| Clipboard | tmux clipboard integration enabled |
| Copy mode | Vim-style keybindings |
| Status bar | Bottom of terminal |
| Status refresh | Every 2 seconds |
| Window alignment | Centered |
| Status left | Current Git branch |
| Status right | Weekday, date and time |
| Active window | Black text on green background |