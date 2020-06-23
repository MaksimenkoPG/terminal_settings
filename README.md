# Terminal settings
Profile for Mac OS Terminal &amp; bash prompt settings

# Bash
`echo "source $(pwd)/.bash_prompt_settings" >> $HOME/.bash_profile`

# ZSH
`echo "source $(pwd)/.zsh_prompt_settings" >> $HOME/.zshrc`
`echo "autoload -U select-word-style" >> $HOME/.zshrc`
`echo "select-word-style bash" >> $HOME/.zshrc`