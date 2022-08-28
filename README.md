# sdir 

Created by [@Andrea-moth](https://github.com/Andrea-moth)

Discord: Ranni simp#2453

**This was coded for linux, the colour scheme will break on Windows**

---

![preview](https://imgur.com/8s1Udli)

> For some reason I can't display this as a gif in the readme
> 
> Please send help

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

> This will not work on windows, please let me know if you find anything simmilar

You can then delete the rest of the files, please check the [non personal usage section](https://github.com/Andrea-moth/sdir/edit/main/README.md#non-personal-usage) to see if it applies to you

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

- [ ] Add more options (--about/etc)

## Non personal usage 

If you use sdir in anything other than a personal useage (i.e. Installing on any computer that isn't your own) please also use

```
sudo mv path-to-readme /usr/bin/sdir
```
