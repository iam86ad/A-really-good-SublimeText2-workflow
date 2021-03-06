A-really-good-SublimeText2-workflow
===================================

My settings and packages in sublime text that save alot of time

# Sublime Text 2 Personal Wiki

Anthony Daniel II

UX Designer and Frontend Developer

Dribbble: www.dribbble.com/86ad

Twitter: www.twitter.com/iam86ad


### Favorite Packages
1. Emmett
2. Sidebar Enchancements
3. Auto Semi-colon
4. Alignment
5. Sublime Linter
6. jQuery
7. HTML5
8. SVN
9. Gist
10. Git
11. PHPCS
12. Advanced New File
13. SCSS
14. AutoFileName
15. Wordpress
16. Wordpress Dev
17. Search Wordpress Codex
18. JS Format
19. Sublime Code Intel
20. Tag
21. Bracket Highlighter
22. Search Stack Overflow
23. JSLint
24. GitGutter
25. Editor Config
26. Modific
27. 


### My Settings Workflow
```
{


    "theme": "Soda Light.sublime-theme",

    "auto_complete_commit_on_tab": true,
    "bold_folder_labels": true,
    "detect_indentation": false,
    "indent_subsequent_lines": true,
    "draw_indent_guides": true,
    "indent_guide_options": [
    "draw_active",
    "draw_normal"
    ],
    "draw_white_space": "selection",
    "ensure_newline_at_eof_on_save": true,
    "find_selected_text": true,
    "caret_style": "solid",
    "folder_exclude_patterns":
    [
        ".svn",
        ".git",
        ".hg",
        "CVS",
        "_build",
        "dist",
        "build",
        "site",
        ".DS_Store",
        "*.scssc"
    ],
    "font_face": "Ubuntu mono",
    "font_options":
    [
        "no_bold",
        "subpixel_antialias"
    ],
    "font_size": 11.0,
    "highlight_line": true,
    "highlight_modified_tabs": true,
    "ignored_packages":
    [
        "Vintage"
    ],
    "line_padding_bottom": 2,
    "line_padding_top": 2,
    "open_files_in_new_window": false,
    "tab_size": 4,
    "trailing_spaces_include_current_line": false,
    "translate_tabs_to_spaces": true,
    "trim_trailing_white_space_on_save": true,
    "use_tab_stops": true,
    "word_separators": "./\\()\"'-:,.;<>~!@#$%^&#038;*|+=[]{}`~?",
    "word_wrap": false,

    "match_brackets": true,
    "match_brackets_angle": true,
    "match_brackets_braces": true,
    "match_brackets_content": true,
    "match_brackets_square": true,

    "scroll_past_end": true,
    "scroll_speed": 2,

    "remember_open_files": true,
    "remember_open_folders": true,
    "show_full_path": true,

    "detect_slow_plugins": false,
    "save_on_focus_lost": false,
    "fade_fold_buttons": true,
    "auto_match_enabled": true,
    "match_tags": true,
    "auto_complete_delay": 50
}

```

### Sublime Linter User Settings
```
{
    "sublimelinter_mark_style": "none",
    "sublimelinter_gutter_marks": true,

   		CSS Lint Options
        "csslint_options": {
        "adjoining-classes": false,
        "box-model": false,
        "box-sizing": false,
        "compatible-vendor-prefixes": "warning",
        "display-property-grouping": true,
        "duplicate-background-images": false,
        "duplicate-properties": true,
        "empty-rules": true,
        "errors": true,
        "fallback-colors": "warning",
        "floats": false,
        "font-faces": false,
        "font-sizes": false,
        "gradients": "warning",
        "ids": false,
        "import": "warning",
        "important": "warning",
        "known-properties": true,
        "outline-none": false,
        "overqualified-elements": "warning",
        "qualified-headings": false,
        "regex-selectors": "warning",
        "rules-count": "warning",
        "shorthand": "warning",
        "star-property-hack": "warning",
        "text-indent": "warning",
        "underscore-property-hack": "warning",
        "unique-headings": false,
        "universal-selector": "warning",
        "vendor-prefix": true,
        "zero-units": "warning"
        }
}

```
