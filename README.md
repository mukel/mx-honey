This plugin provides completions for [mx](https://github.com/graalvm/mx); a command-line tool used for the development of Graal projects.
It's meant to improve the usual workflow `build unittest benchmark ...` ease discovery and provide handy aliases.

# Features 
  - [X] [mx aliases](./mx.plugin.zsh)
  - [X] sub-command completion
  - [ ] [WIP] `mx benchmmark` completions

# Manual install
```bash
git clone --depth 1 https://github.com/mukel/mx-honey.git ~/.oh-my-zsh/plugins/mx
```
Then add `mx` to your `~/.zshrc`:
```bash
plugins(git sudo archlinux mx)
```
