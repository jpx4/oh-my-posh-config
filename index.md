# [OhMyPosh](https://ohmyposh.dev) Config
[OMP: Change your prompt](https://ohmyposh.dev/docs/installation/prompt) but with the my config
|bash|pwsh|
|--|--|
| `vi .bashrc` | `New-Item -Path $PROFILE -Type File -Force` |
| Add line: `eval "$(oh-my-posh init bash --config 'https://jpx4.github.io/oh-my-posh-config/oh-my-posh/themeconfig')"` | `echo oh-my-posh init pwsh --config "https://jpx4.github.io/oh-my-posh-config/oh-my-posh/themeconfig" >> $PROFILE` |
| `exec bash` | Reload powershell|

