## DESCRIPTION
This is an alpha-stage native GUI for lldb. It is currently about ~10% of the way towards usable.

The basic goal is to provide vim/emacs users with a lightweight, cross-platform, easy-to-compile likeness of what you would see in a full-featured IDE debugger interface.

### TODO
#### Short Term
- [x] file explorer pane
- [x] cache open files in memory and display in tabs
- [x] display full stack trace with file name, line, column
- [x] display file contents
- [x] show local variables for each stack frame
- [x] lldb console
- [x] viewable log messages
- [X] syntax highlighting
- [X] show breakpoint list
- [ ] show program status: running or stopped (with stop reason)
- [ ] clickable tree view of local variables with children
- [ ] highlight breakpoints in file contents with markers
- [ ] show watchpoint list
- [ ] show registers
- [ ] right click to add breakpoint at specific line of viewed file
- [ ] mouse scroll file contents window
- [ ] adjustable splitters between each main UI element
- [ ] adjustable font family
- [ ] adjustable font size
- [ ] automatically scale based on DPI of display
- [ ] add color themes
- [ ] local config file for specifying font family/size, color theme, etc
- [ ] toggle inline assembly view
- [ ] command line arguments to set working directory, initial executable and arguments
- [ ] start/pause/stop buttons
- [ ] button to change working directory
- [ ] button to select different executable to debug
- [ ] keyboard shortcut to focus to console keyboard input
- [ ] colored log output
- [ ] menu option to output log to file
- [ ] menu option to enable/disable logging (disabled by default)
- [ ] command line argument to turn on logging at start


### screenshot
![alt text](https://raw.githubusercontent.com/zmeadows/lldbg/master/screenshot.png)
