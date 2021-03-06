# pycharm-config

Config for PyCharm4.

You can just import [settings.jar](https://github.com/dianchang/pycharm-config/raw/master/settings.jar), or config as follows:

* LESS file watcher `Editor -> Tools -> File Watcher` (Install `less` via npm first)
* Show line numbers `Editor -> General -> Appearance`
* Set project interpreter `Project -> Project Interpreter`
* Set project structure `Project -> Project Structure`
  * Set `application` as Resources
  * Set `application/templates` as Templates
* Set template as Jinja2 `Languages & Framework -> Python Template Language`
* Change reformat code keymap
  * Add `Option + F` to `Keymap -> Main menu -> Code -> Reformat Code`
* Change navigate file keymap 
  * Add `Option + G` to `Keymap -> Main menu -> Navigate -> File`
* Change rename keymap
  * Remove `Option + R` from `Keymap -> Tools -> Run manage.py Task`
  * Add `Option + R` to `Keymap -> Main menu -> Refactor -> Rename`
