# Lib-x
![GitHub Issues or Pull Requests](https://img.shields.io/github/issues/Benex254/FastAnime)
![GitHub License](https://img.shields.io/github/license/Benex254/lib-x)
![GitHub file size in bytes](https://img.shields.io/github/size/Benex254/lib-x/lib-x)
![GitHub Release](https://img.shields.io/github/v/release/Benex254/lib-x)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/Benex254/lib-x)

A TUI wrapper over the calibredb

[lib-x-all.webm](https://github.com/user-attachments/assets/58690f9f-b239-4c84-9175-f17b8c6d2293)


# Installation
![Linux/BSD](https://img.shields.io/badge/-Linux/BSD-red.svg?style=for-the-badge&logo=linux)
![Arch Linux](https://img.shields.io/badge/-Arch_Linux-black.svg?style=for-the-badge&logo=archlinux)
![MacOS](https://img.shields.io/badge/-MacOS-lightblue.svg?style=for-the-badge&logo=apple)


```bash
curl -sL https://raw.githubusercontent.com/Benex254/lib-x/refs/heads/master/lib-x -o ~/.local/bin/lib-x && chmod +x ~/.local/bin/lib-x
```

# Dependencies

**Required:**

- calibre - for obvious reasons
- jq - to pass the  json data
- fzf - for the main ui
  
**optional:**

- glow - rendering the markdown for the descriptions
- gum - for an even better ui

# Usage

```bash
# launch the ui
lib-x 

# edit your config
lib-x -e

# search for a specific book with calibre search syntax
lib-x --search tag:programming
```
