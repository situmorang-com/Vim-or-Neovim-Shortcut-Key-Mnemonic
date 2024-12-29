# Vim-or-Neovim-Shortcut-Key-Mnemonic
Below is a list of commonly used Neovim shortcuts and their logical or mnemonic reasoning for the choice of the shortcut letters. These shortcuts are consistent with both Vim and Neovim, and their design reflects intuitive mappings or historical conventions.

## **Modes in Neovim**

- **Normal Mode**: Default mode for navigation and commands.
- **Insert Mode**: Editing text.
- **Visual Mode**: Selecting text.
- **Command-Line Mode**: Running commands (`:`).

---

### **1. Navigation**

|**Shortcut**|**Action**|**Mnemonic/Logic**|
|---|---|---|
|`h`|Move left|Think of **h** as the **leftmost** letter in "hjk".|
|`j`|Move down|Resembles a **downward stroke** visually.|
|`k`|Move up|Resembles an **upward stroke** visually.|
|`l`|Move right|Think of **l** as the **rightmost** letter in "hjk".|
|`gg`|Go to the beginning of file|Mnemonic for "**go to the beginning**".|
|`G`|Go to the end of file|Mnemonic for "**go to the bottom**".|
|`w`|Move to the start of a word|Mnemonic for "**word**".|
|`e`|Move to the end of a word|Mnemonic for "**end of word**".|
|`b`|Move to the beginning of word|Mnemonic for "**backward word**".|
|`%`|Jump to matching `()` `{}` `[]`|Symbol-based logic for matching brackets.|
|`H`|Go to the top of the screen|Mnemonic for "**high**" position.|
|`M`|Go to the middle of the screen|Mnemonic for "**middle**".|
|`L`|Go to the bottom of the screen|Mnemonic for "**low**" position.|

---

### **2. Editing**

|**Shortcut**|**Action**|**Mnemonic/Logic**|
|---|---|---|
|`i`|Enter Insert mode at cursor|Mnemonic for "**insert**".|
|`a`|Enter Insert mode after cursor|Mnemonic for "**append**".|
|`o`|Open a new line below|Mnemonic for "**open** line".|
|`O`|Open a new line above|Capitalized for **above**.|
|`x`|Delete character under cursor|Mnemonic for "**x-out**" or delete.|
|`r`|Replace character under cursor|Mnemonic for "**replace**".|
|`u`|Undo last change|Mnemonic for "**undo**".|
|`Ctrl-r`|Redo last undone change|Mnemonic for "**redo**".|
|`y`|Yank (copy)|Mnemonic for "**yank**" (a term for copying text in Vim).|
|`p`|Paste after the cursor|Mnemonic for "**put**".|
|`P`|Paste before the cursor|Capitalized for position **before**.|
|`d`|Delete|Mnemonic for "**delete**".|
|`c`|Change|Mnemonic for "**change**".|

---

### **3. Visual Mode**

|**Shortcut**|**Action**|**Mnemonic/Logic**|
|---|---|---|
|`v`|Start visual mode|Mnemonic for "**visual**".|
|`V`|Start visual line mode|Capitalized for **line-based** visual mode.|
|`Ctrl-v`|Start block visual mode|Mnemonic for "**visual block**".|
|`y`|Yank (copy) in visual mode|Works consistently with **y** for yank.|
|`d`|Delete selection in visual mode|Works consistently with **d** for delete.|
|`>`|Indent selection|Symbol-based logic for **increasing** indentation.|
|`<`|Dedent selection|Symbol-based logic for **decreasing** indentation.|

---

### **4. Command-Line Mode**

|**Shortcut**|**Action**|**Mnemonic/Logic**|
|---|---|---|
|`:`|Enter command-line mode|Universal symbol for commands.|
|`/`|Search forward|Symbol for **searching**.|
|`?`|Search backward|Symbol for questioning or **searching backward**.|
|`q:`|Open command history|Mnemonic for "**query** command history".|
|`Ctrl-d`|Show possible completions|Mnemonic for "**display options**".|

---

### **5. Window and Tab Management**

|**Shortcut**|**Action**|**Mnemonic/Logic**|
|---|---|---|
|`Ctrl-w s`|Split window horizontally|Mnemonic for "**split**".|
|`Ctrl-w v`|Split window vertically|Mnemonic for "**vertical** split".|
|`Ctrl-w q`|Quit current window|Mnemonic for "**quit**".|
|`:tabnew`|Open a new tab|Mnemonic for "**tab** new".|
|`:tabclose`|Close current tab|Mnemonic for "**tab close**".|
|`gt`|Go to next tab|Mnemonic for "**go tab** next".|
|`gT`|Go to previous tab|Mnemonic for "**go tab** previous".|

---

### **6. Searching and Replacing**

|**Shortcut**|**Action**|**Mnemonic/Logic**|
|---|---|---|
|`/pattern`|Search for `pattern`|Slash `/` is the symbol for search.|
|`n`|Repeat the last search forward|Mnemonic for "**next** match".|
|`N`|Repeat the last search backward|Capitalized for **backward direction**.|
|`:%s/foo/bar/g`|Replace `foo` with `bar` globally|Mnemonic: **s** for substitute.|

---

### **7. Marks and Jumps**

|**Shortcut**|**Action**|**Mnemonic/Logic**|
|---|---|---|
|`m{letter}`|Set a mark|Mnemonic for "**mark**".|
|`'{letter}`|Jump to a mark|Mnemonic for "**'** goes to marked position".|
||Jump to the previous location|Double backticks for **jumping back**.|

---

## **Mnemonics in Vim/Neovim**

- **Single-letter commands**: Often correspond to the first letter of the action (e.g., `d` for delete, `y` for yank, `p` for paste).
- **Symbols**: Frequently used for their intuitive visual or functional associations (e.g., `/` for search, `%` for matching brackets).
- **Capitalization**: Adds variations (e.g., `P` for paste before, `G` for the end of the file).
- **Consistency**: Many commands share the same letter across different modes, preserving muscle memory (e.g., `y` in normal and visual modes). 

