### Setting up your Mac

1. Update macOS to the latest version through system preferences
2. [Generate a new public and private SSH key](https://docs.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) by running:

   ```zsh
   curl https://raw.githubusercontent.com/tuannda/dotfiles/HEAD/ssh.sh | sh -s "tuannda123@gmail.com"
   ```

3. Clone this repo to `~/.dotfiles` with:

   ```zsh
   git clone --recursive git@github.com:tuannda/dotfiles.git ~/.dotfiles
   ```

4. Run the installation with:

   ```zsh
   cd ~/.dotfiles && ./fresh.sh
   ```

5. After mackup is synced with your cloud storage, restore preferences by running `mackup restore`
6. Restart your computer to finalize the process

## Your Own Dotfiles

```zsh
brew install mackup
mackup backup
```
