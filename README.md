My Sublime Text 3 Setup
==========

My curated list of Sublime Text plugins I use on a daily-basis. The number one plugin I could not live without is [Package Control](https://github.com/wbond/sublime_package_control) - it is by far the best package manager if you use Sublime Text.

### My Package Control `installed_packages` list

This list is available at `Preferences > Package Settings > Package Control > Settings – User`

```js
{
  "installed_packages":
  [
    "AlignTab",
    "All Autocomplete",
    "ApplySyntax",
    "Auto Semi-Colon",
    "Autoprefixer",
    "Better CoffeeScript",
    "BracketHighlighter",
    "CoffeeComplete Plus (Autocompletion)",
    "CSS Snippets",
    "DeleteBlankLines",
    "Django Manage Commands",
    "DocBlockr",
    "Doctypes",
    "EditorConfig",
    "Emmet",
    "Emmet Css Snippets",
    "Filter Lines",
    "GhostText",
    "Gist",
    "Git",
    "GitGutter-Edge",
    "GoldenRatio",
    "Gutter Color",
    "Handlebars",
    "HTML Snippets",
    "HTML-CSS-JS Prettify",
    "HTML5",
    "HTMLAttributes",
    "Inc-Dec-Value",
    "Jinja2",
    "LESS",
    "Markdown Preview",
    "MarkdownEditing",
    "Minify",
    "Package Control",
    "Pretty JSON",
    "Python Flake8 Lint",
    "Sass",
    "Seti_UI",
    "SideBarEnhancements",
    "SideBarGit",
    "Siteleaf Liquid Syntax",
    "StringEncode",
    "SublimeCodeIntel",
    "SublimeLinter",
    "SublimeLinter-csslint",
    "SublimeLinter-jscs",
    "SublimeREPL",
    "Tag",
    "Unsplash",
    "View In Browser"
  ]
}
```

Here is my settings as well:

```js
{
    "auto_complete_selector": "source, text",
    "bold_folder_labels": true,
    "caret_extra_width": 2,
    "color_scheme": "Packages/User/Seti_orig (SL) (Flake8Lint).tmTheme",
    "create_window_at_startup": false,
    "detect_indentation": false,
    "draw_white_space": "selection",
    "enable_tab_scrolling": false,
    "ensure_newline_at_eof_on_save": true,
    "fade_fold_buttons": true,
    "file_exclude_patterns":
    [
        "._*",
        ".DS_Store",
        ".git*",
        "*.pyc",
        "*.rdb",
        "sftp*",
        ".dropbox",
        "Icon*",
        ".sublime-*"
    ],
    "fold_buttons": true,
    "folder_exclude_patterns":
    [
        ".git",
        "env",
        "tmp",
        "node_modules",
        ".bower-*",
        ".codekit-*",
        ".sass-cache"
    ],
    "font_face": "Droid Sans Mono",
    "font_options":
    [
        "subpixel_antialias"
    ],
    "font_size": 14.0,
    "highlight_line": true,
    "highlight_modified_tabs": true,
    "ignored_packages":
    [
        "Markdown",
        "Vintage"
    ],
    "show_full_path": true,
    "spell_check": false,
    "tab_size": 2,
    "theme": "Seti.sublime-theme",
    "trailing_spaces_include_current_line": false,
    "translate_tabs_to_spaces": true,
    "trim_trailing_white_space_on_save": true,
    "uglifyjs_command": "/usr/local/bin/uglifyjs",
    "word_wrap": false
}
```


### Other

0. [Golden Ratio](https://sublime.wbond.net/packages/GoldenRatio)
