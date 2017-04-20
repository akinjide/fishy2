### fishy2

#### A ZSH theme


#### Screenshots

![Screenshot 1](images/Screen%20Shot%202017-04-20%20at%2010.46.49%20AM.png)


#### How To Install

#### [oh-my-zsh](http://ohmyz.sh/)

1. [Download](https://github.com/akinjide/fishy2/archive/master.zip) || Clone the URL
2. Copy **themes** folder that contains `fishy2.zsh-theme`
3. Open Terminal, enter `defaults write com.apple.finder AppleShowAllFiles YES` to show hidden files and folders
4. Go to your home directory and find `.oh-my-zsh` folder, right click and open in new tab, enter the custom folder
5. Paste the **themes** folder you copied into the custom folder and close finder
6. Enter your oh-my-zsh configuration file by entering `vi ~/.zshrc`, and press **i** key to enter edit mode
7. Change your current theme `ZSH_THEME="robbyrussell"` to `ZSH_THEME="fishy2"`, and press **esc** key to leave edit mode
8. Press `:wq` to leave **Vi** mode
9. Enter `source ~/.zshrc` to save the configuration
10. Done, Enjoy your new theme!!

#### [zgen](https://github.com/tarjoilija/zgen)

1. Add `zgen load akinjide/fishy2 themes` to your `.zshrc` with your other `zgen load` commands
2. `zgen save` to create a new `init.zsh`
3. start a new iTerm window to load the new configuration.