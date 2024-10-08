# zsh
```
sudo apt update
sudo apt install zsh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```
# zsh plugins
```
sudo apt update

# zsh-syntax-highlighting
sudo apt install zsh-syntax-highlighting
echo "source /usr/share/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh" >> ${ZDOTDIR:-$HOME}/.zshrc

# zsh-autosuggestions
sudo apt install zsh-autosuggestions
echo "source /usr/share/zsh-autosuggestions/zsh-autosuggestions.zsh" >> ${ZDOTDIR:-$HOME}/.zshrc

# zsh-completions
sudo apt install zsh-completions
echo "source /usr/share/zsh-completions/zsh-completions.zsh" >> ${ZDOTDIR:-$HOME}/.zshrc
```