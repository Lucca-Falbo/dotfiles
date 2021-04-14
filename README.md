# dotfiles
This is a evolving documetantion process of how I create my dotfiles folder and all the steps I need to set up my configs

---

# First steps
After installing manjaro with i3wm I need some key software **google-chrome, vscode**.

## Instaling Zsh and Oh-My-Zsh

Zsh already comes with manjaro, but you need to make it the default shell before instaling Oh-My-Zsh. To do this run `chsh -s $(which zsh)` after this run `echo $SHELL` to test.  Expected result: `/bin/zsh` or similar.

the install with `	sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`

---

# Not sure yet
I also need to config my git github and SSH key (not sure how to config this).

I need to better understand how to import my dotfiles from my github repo to my local machine. This links can help me with it [writen tutorial](https://www.atlassian.com/git/tutorials/dotfiles) and [youtube video](https://www.youtube.com/watch?v=tBoLDpTWVOM)




