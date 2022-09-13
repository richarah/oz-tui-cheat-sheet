# Oz TUI Cheat Sheet

It's dangerous to go alone. Here, take this.

# A note on {Browse} and graphical commands on Dorothy TUI
Due to X11 and its dependencies being omitted from the TUI version of Dorothy (Oz + Mozart OPI in Docker), code that utilises graphics libraries or makes use of a window manager may exhibit unexpected behaviour.
Thus, instead of e.g. `{Browse}`, it is strongly recommended to use alternatives such as {Show} whenever possible.

# Emacs

### Emacs Tutorial
Menu Bar > Help > Emacs Tutorial or `Ctrl-h t`

### Emacs Psychotherapist (ELIZA, is that you?)
Menu Bar > Help > Emacs Psychotherapist

# General

### Text Menu
`ESC-x`

### Menu Bar
`ESC-x`, type `menu-bar-open` and hit Enter.
Use arrow keys to navigate between sub-menus and Enter to select.

# Oz

### Feed Buffer
Menu Bar > Oz > Feed Buffer or `Ctrl-. Ctrl-b`

### Feed Line
Menu Bar > Oz > Feed Line or `Ctrl-. Ctrl-l`

### Toggle Compiler/Emulator
Menu Bar > Oz > Show/Hide... > Compiler/Emulator or:
**Compiler:** `Ctrl-. c`
**Emulator:** `Ctrl-. e`
