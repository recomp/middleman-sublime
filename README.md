middleman-sublime-build
=================

middleman-sublime-build

Sublime Text Build Systems for middleman

this plugin is the same as write in console:

        $cd my_project
        $bundle exec middleman build

### install
copy Middleman.sublime-build file into user packages directory

 ~/.config/{sublime-text-path}/Packages/User

or open **Tools** -> **Build System** -> **New build system**

!(img.jpg)

and paste:
```
{
  "shell_cmd": "middleman build",
  "working_dir": "$file_path"
}
```
### How to use

to start, select **Tools** -> **Build System** -> **Middleman**
and press:
```
Ctrl + b
```