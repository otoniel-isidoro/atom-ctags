# Atom Ruby Ctags Package

This package uses：
[ctags](http://ctags.sourceforge.net),
[ripper-tags](https://github.com/tmm1/ripper-tags),
[autocomplete-plus](https://github.com/atom/autocomplete-plus).
and was forked from [atom-ctags](https://github.com/yongkangchen/atom-ctags)

# Features
* **AutoComplete with ripper-tags (better ctags for ruby)**
* **Auto Update the file's tags data when saved**
* go-to-declaration and return-from-declaration
* toggle-file-symbols
* toggle-project-symbols
* "Rebuild Ctags" in context-menu
* "Auto Build Tags When Active" setting, default: false
* 'extraTagFiles' setting, add specified tagFiles.(Make sure you tag file generate with --fields=+KSn)
* 'cmdArgs' setting, add specified ctag command args like: --exclude=lib --exclude=*.js
* 'buildTimeout' setting, specified ctag command execute timeout

# Install
**You can install atom-ruby-ctags using the Preferences pane.**
And please Make sure that [autocomplete-plus](https://github.com/saschagehlich/autocomplete-plus) and [ripper-tags](https://github.com/tmm1/ripper-tags) was already installed (gem install ripper-tags).
