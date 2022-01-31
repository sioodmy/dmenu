# dmenu

Dmenu is a fast and lightweight application launcher. How lightweight is it? Rofi is currently around 1093172 lines of code, while my dmenu fork is only 1848!

# usage

* **As an application launcher**
Of course you can use dmenu as an application launcher just like rofi, to do so you can use `dmenu_run` however following script will also display non-gui apps. Thats why I recomend using [j4-dmenu-desktop](https://github.com/enkore/j4-dmenu-desktop) (available as an AUR packages)

tldr `j4-dmenu-desktop`

* **As a menu for your shell script**
Example: 
```
food.txt
---
banana
orange
apple
pierogi
```

```
$ cat food.txt | dmenu
orange
```
As you can see dmenu reads arbitrary text from stdin, and creates a menu with one item for each line

# installation
just clone the repo and run `make clean install` as root
