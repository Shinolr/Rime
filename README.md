# Rime setup and multi-device synchronization
1 Install Squirrel via [Homwbrew](https://github.com/Homebrew)  
`brew cask install squriiel`

2 (**OPTIONAL**)Install [Plum](https://github.com/rime/plum) in Squirrel's user direcotry(recommend)  
`curl -fsSL https://git.io/rime-install | bash`

3 (**OPTIONAL**)Install input methods in Squirrels's user directroy(doubou-pinyin eg:)  
`plum/rime-install doubou-pinyin`

4 (**OPTIONAL**)Extend dictionaries mannuly  
[see](https://github.com/rime-aca/dictionaries)

5 (**OPTIONAL**)Clone previos basic input method configuration from this repo  
`git clone git@github.com:Shinolr/Rime.git`

*Either 234 or 5*

6 Sync and backup  
  * sync nonsensitive yaml with git like this repo
  * sync personal words db with dropbox by edit **installation.yaml**(ingored by git)
  * backup yaml to dropbox
