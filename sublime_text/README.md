# Personal Setting

## Package List

This is my list of useful Sublime Text packages that I currently use to optimize my coding experience:

- [A File Icon](https://packagecontrol.io/packages/A%20File%20Icon) - File-Specific Icons for Improved Visual Grepping
- [All Autocomplete](https://packagecontrol.io/packages/All%20Autocomplete) - Extend autocompletion to find matches in all open files of the current window
- [AutoFileName](https://packagecontrol.io/packages/AutoFileName) - Autocompletes filenames
- [AutoPEP8](https://packagecontrol.io/packages/AutoPEP8) - Automatically formats Python code to conform to the PEP 8 style guide
- [BracketHighlighter](https://packagecontrol.io/packages/BracketHighlighter) - Bracket and tag highlighter for Sublime Text 
- [Emmet](https://packagecontrol.io/packages/Emmet) - The essential toolkit for web-developers
- [Git](https://packagecontrol.io/packages/Git) - Add git integration for Sublime Text
- [GitGutter](https://packagecontrol.io/packages/GitGutter) - See git diff in gutter
- [MarkdownEditing](https://packagecontrol.io/packages/MarkdownEditing) - Markdown package with better syntax understanding and good color schemes
- [MarkdownPreview](https://packagecontrol.io/packages/MarkdownPreview) - Markdown preview and build plugin
- [SideBarEnhancements](https://packagecontrol.io/packages/SideBarEnhancements) - Provides enhancements to the operations on Sidebar of Files and Folders
- [Terminus](https://packagecontrol.io/packages/Terminus) - Bring a real terminal to Sublime Text
- [Theme - Monokai Pro](https://packagecontrol.io/packages/Theme%20-%20Monokai%20Pro) - Professional theme and matching icons

## Installation

1. Open Sublime Text
2. Go to Preferences -> Package Control -> Package Control: Advanced Install Package
3. Copy and paste the following comma-separated list:

```
A File Icon,All Autocomplete,AutoFileName,AutoPEP8,BracketHighlighter,Emmet,Git,GitGutter,MarkdownEditing,MarkdownPreview,SideBarEnhancements,Terminus,Theme - Monokai Pro
```

4. Restart Sublime Text after all packages has finished installing
5. Go to Preferences -> Settings
6. Copy and paste the following setting:

```
{
    "theme": "Monokai Classic.sublime-theme",
    "color_scheme": "Monokai Classic.sublime-color-scheme",
    "font_size": 13,
    "word_wrap": true,
    "tab_completion": true,
    "auto_complete_commit_on_tab": true,
    "highlight_modified_tabs": true,
    "translate_tabs_to_spaces": true,
    "remember_full_screen": true,
    "ignored_packages": ["Vintage"],
}
```
