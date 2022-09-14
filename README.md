# Oz TUI Cheat Sheet

A collection of essential commands for operating the Emacs-based text user interface of the Mozart OPI (Oz Programming Interface)

# Before proceeding

#### {Browse} and graphical commands on Dorothy TUI
Due to X11 and its dependencies being omitted from the TUI version of Dorothy (Oz + Mozart OPI in Docker), code that utilises graphics libraries or makes use of a window manager may exhibit unexpected behaviour.
Thus, instead of e.g. `{Browse}`, users are strongly recommended to use alternatives such as {Show} whenever possible.

#### Command abbreviations
Commands in Emacs and other text user interfaces generally use the Ctrl key or Meta key (labeled Win, Alt, Edit or Super depending on your layout).

However, instead of writing this each time, it's common to use the following abbreviations:

`C-<character>`: Hold Ctrl while typing <character>.
`M-<character>`: Hold Ctrl while typing <character>.
*Note: For users without a Meta key, the same effect can be achieved by pressing and releasing Esc and then typing the character.*

# General

#### Text Menu
`M-x`

#### Menu Bar
`M-x`, type `menu-bar-open` and hit Enter.
Use arrow keys to navigate between sub-menus and Enter to select.

#### Exit
`C-x C-c` or Menu Bar > File > Quit

# Emacs

#### Emacs Tutorial
Menu Bar > Help > Emacs Tutorial or `C-h t`

#### If all else fails
Menu Bar > Help > Emacs Psychotherapist or `M-x doctor`

# Oz

#### Feed Buffer
Menu Bar > Oz > Feed Buffer or `C-. C-b`

#### Feed Line
Menu Bar > Oz > Feed Line or `C-. C-l`

#### Toggle Compiler/Emulator
Menu Bar > Oz > Show/Hide... > Compiler/Emulator or:
**Compiler:** `C-. c`
**Emulator:** `C-. e`
