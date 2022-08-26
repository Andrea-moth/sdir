# sdir 

Created by [@Andrea-moth](https://github.com/Andrea-moth)

Discord: Ranni simp#2453

**This was coded for linux, the colour scheme will break on Windows or Mac**

---

Video preview to come later

## Index

- [Installation](https://github.com/Andrea-moth/sdir/edit/main/README.md#installation)

- [Usage](https://github.com/Andrea-moth/sdir/edit/main/README.md#usage)

- [Config](https://github.com/Andrea-moth/sdir/edit/main/README.md#config)

- [ToDo](https://github.com/Andrea-moth/sdir/edit/main/README.md#todo)

## Installation 

Use

```
sudo mv path-to-sdir /usr/bin
```

> If there is a better way of doing this please let me know

I would also recomend adding 

```
alias clear="clear; sdir" #run sdir whenever you clear the terminal
(sdir) #runs at terminal start up
```

To your terminal config file (Generally ~/.bashrc or ~/.zshrc)

## Usage

### Arguments

* Directory (Default: Current directory) ┃ The directory shown 

### Options

* --all/-a (Flag, Default: false) ┃ Whether or not files and folders begining with a . are shown
* --config/-c (Flag, Default: false) ┃ Allows you to customize the colours used 

## Config 

All configuration is done automatically, however if you are having trouble setting the colours try deleting

```
~/.config/sdir_colours.json 
```

and running the program again

Currently colour codes can only be hexadecimal values 

Default values 
```
{
   "folder": "#d787ff", #Colour of folders
   "file": "#123456", #Colour of files
   "title": "#af005f", #Colour of the title 
   "outline": "#afafaf" #Colour of the box outline
}
```

## ToDo 

- [ ] Add support for more type of colour values
