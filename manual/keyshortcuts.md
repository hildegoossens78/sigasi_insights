---
title: Keyboard Shortcuts
layout: page 
pager: true
---

As you become more experienced with Sigasi, you will find that there are a number of actions that you perform quite often. At some point, you may feel that the GUI-based approach becomes too slow for these actions. For that reason, Sigasi provides a number of keyboard shortcuts. They are a great way to boost your productivity. A printable cheat sheet with [all shortcuts on one page is available for download](resources/keyboard-shortcuts.pdf).

[![A printable cheat sheet with all shortcuts](images/keyboard-shortcuts.png)](resources/keyboard-shortcuts.pdf "A printable cheat sheet with all shortcuts")

In this chapter, we describe the available keyboard shortcuts.

Top keyboard shortcuts
----------------------

In this section, we list the most important shortcuts.

1. *Open Resource* (**Shift+Ctrl+R**):  
   **Shift+Ctrl+R** opens a dialog that allows you to swiftly open an
editor on any file in the workspace.
2. *Open Declaration* (**F3**):  
   Use **F3** to navigate to the declaration of the selected identifier.
3. Backward History (**Alt+Left**):  
   Often, when you navigate to a declaration you want to go back to where you came from; just press **Alt+Left**.
4. Content Assist (**Ctrl+Space**):  
   With content assist (autocomplete) you can really speed up coding VHDL. Just press **Ctrl+Space** to get a suggestion of possible autocompletes in the current context.
5. Go to next marker (**Ctrl+.**)  
    Does your file contain warnings or errors? Quickly navigate to the next problem by pressing **Ctrl+.** (**Ctrl+,** jumps to the previous problem).
6. Quick Fix (**Ctrl+1**):  
   To fix problems even quicker, navigate to the problem with the previous shortcut. Press **Ctrl+1** to activate the quickfix, select the fix with the **UP** or **DOWN** keys and execute the quickfix with **Enter**.
7. Go to Line (**Ctrl+L**)  
   You can directly jump to a certain line with this shortcut. You can display the line numbers by right-clicking on on the gray bar on the left side of the editor view and clicking on **Show Line Numbers**.
8. Search references (**Shift+Ctrl+G**)  
   To search for all occurrences of a given identifier, just select the identifier and press **Shift+Ctrl+G**. The search view is displayed, with a match for each occurrence (possibly in multiple files)
9. Rename Refactoring (**Shift+Alt+R**)  
   Once you get used to the rename refactoring you will be using it all the time. Use **Shift+Alt+R** to run it even quicker.
10. Toggle Block Selection (**Shift+Alt+A**)  
   Switch between regular and block selection mode.
11. Structured Select (**Shift+Alt+Up/Down/Left/Right**)  
  Select VHDL or Verilog code, based on its *syntactic structure*. ([/manual/editor#Structured selection])  
12. <a name="quick-access"></a>Quick Access (**Ctrl+3**, <mark>This is the shortcut to use, when you forgot the shortcut you actually need.</mark>)  
  With Quick Access you can quickly find open editors, available perspectives, views, preferences, wizards, commands, etc. Simply start typing the name of the item you wish to invoke.

Keyboard shortcut reference
---------------------------

| Category               | Description                  | Keyboard shortcut            |
| ---------------------- | ---------------------------- | -----------------------------|
| *Basic Editing*        | Delete                       | **Delete**                   |
|                        | Copy                         | **Ctrl+C**, **Ctrl+Insert**  |
|                        | Paste                        | **Ctrl+V**, **Shift+Insert** |
|                        | Cut                          | **Ctrl+X**, **Shift+Delete** |
|                        | Undo                         | **Ctrl+Z**                   |
|                        | Redo                         | **Ctrl+Y**                   |
|                        | Select All                   | **Ctrl+A**                   |
|                        | Toggle Block Selection       | **Shift+Alt+A**              |
| *Quickfixes*           | Quick Fix                    | **Ctrl+1**                   |
| *Autocompletion*       | Content Assist               | **Ctrl+Space**               |
|                        | Word completion              | **Alt+/**                    |
| *Basic Search*         | Find and Replace             | **Ctrl+F**                   |
|                        | Find Next                    | **Ctrl+K**                   |
|                        | Find Previous                | **Shift+Ctrl+K**             |
|                        | Incremental Find             | **Ctrl+J**                   |
|                        | Incremental Find Reverse     | **Shift+Ctrl+J**             |
| *Files*                | Print                        | **Ctrl+P**                   |
|                        | New                          | **Ctrl+N** |
|                        | Rename                       | **F2** |
|                        | Close All           | **Shift+Ctrl+F4**, **Shift+Ctrl+W** |
|                        | Refresh | **F5** |
|                        | Close | **Ctrl+F4**, **Ctrl+W** |
|                        | Properties | **Alt+Enter** |
|                        | Save | **Ctrl+S** |
|                        | New menu | **Shift+Alt+N** |
|                        | Save All | **Shift+Ctrl+S** |
| *Navigation*           | Last Edit Location | **Ctrl+Q** | 
|                        | Open Resource | **Shift+Ctrl+R** |
|                        | Backward History | **Alt+Left** |
|                        | Show In… | **Shift+Alt+W** |
|                        | Go to Line | **Ctrl+L** |
|                        | Previous | **Ctrl*,** |
|                        | Next | **Ctrl*.** |
|                        | Collapse All | **Shift+Ctrl+Numpad\_Divide** |
|                        | Forward History | **Alt+Right** |
| *VHDL/Verilog specific*| Search references | **Shift+Ctrl+G** |
|                        | Rename - Refactoring | **Shift+Alt+R** |
|                        | Toggle Comment | **Ctrl+/** |
|                        | Comment | **Shift+Ctrl+/** |
|                        | Uncomment | **Shift+Ctrl+\*** |
|                        | Open Declaration | **F3** |
|                        | Open matching entity | **Shift+F3** |
|                        | Go to next problem | **Shift*.** |
|                        | Go to previous problem | **Shift*,** |
|                        | Expand structured selection | **Shift+Alt+Up** |
|                        | Contact structured selection | **Shift+Alt+Down** |
|                        | Expand structured selection left | **Shift+Alt+Left** |
|                        | Expand structured selection right | **Shift+Alt+Right** |
| *Advanced search*      | Find Text in Workspace | **Ctrl+Alt+G** |
|                        | Open Search Dialog | **Ctrl+H** |
|                        | Previous Word | **Ctrl+Left** |
| *Advanced editing*     | Insert Line Above Current Line | **Shift+Ctrl+Enter** |
|                        | Scroll Line Down | **Ctrl+Down** |
|                        | Delete Next Word | **Ctrl+Delete** |
|                        | Test Start | **Ctrl+Home** |
|                        | Toggle Overwrite | **Insert** |
|                        | Insert Line Below Current Line | **Shift+Enter** |
|                        | Delete Previous Word | **Ctrl+Backspace** |
|                        | Delete Line | **Ctrl+D** |
|                        | Copy Lines | **Ctrl+Alt+Down** |
|                        | Duplicate Lines | **Ctrl+Alt+Up** |
|                        | Move Lines Down | **Alt+Down** |
|                        | Delete to End of Line | **Shift+Ctrl+Delete** |
|                        | Select Next Word | **Shift+Ctrl+Right** |
|                        | Scroll Line Up | **Ctrl+Up** |
|                        | Select Line End | **Shift+End** |
|                        | Move Lines Up | **Alt+Up** |
|                        | Join Lines | **Ctrl+Alt+J** |
|                        | To Upper Case | **Shift+Ctrl+X** |
|                        | Select Line Start | **Shift+Home** |
|                        | To Lower Case | **Shift+Ctrl+Y** |
|                        | Select Previous Word | **Shift+Ctrl+Left** |
|                        | Next Word | **Ctrl+Right** |
|                        | Text End | **Ctrl+End** |
|                        | Line Start | **Home** |
|                        | Line End | **End** |
| *Views*                | Maximize Active View or Editor | **Ctrl+M** |
|                        | Next Editor | **Ctrl+F6** |
|                        | Next View | **Ctrl+F7** |
|                        | Show View Menu | **Ctrl+F10** |
|                        | Show Key Assist | **Shift+Ctrl+L** |
|                        | Show System Menu | **Alt+-** |
|                        | Show Ruler Context Menu | **Ctrl+F10** |
|                        | Previous Editor | **Shift+Ctrl+F6** |
|                        | Activate Editor | **F12** |
|                        | Switch to Editor | **Shift+Ctrl+E** |
|                        | Previous View | **Shift+Ctrl+F7** |
|                        | Quick Access | **Ctrl+3** |
|                        | Quick Switch Editor | **Ctrl+E** |
