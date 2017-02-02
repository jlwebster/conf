- TPM added as a submodule 
- Update submodules
`git submodule update --init`
- In tmux hit prefix + I to load plugins
- Use iTerm2 so that mouse selection works. Hold down option key while drag selecting. Copy happens without having to press Cmd-C
- Fix C-h in terminal with neovim https://github.com/neovim/neovim/issues/2048#issuecomment-78045837
`infocmp $TERM | sed 's/kbs=^[hH]/kbs=\\177/' > $TERM.ti`
`tic $TERM.ti`
