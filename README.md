# hoMyZsh_theme

append this PS1 to >> ~/.zshrc : 

PS1='%{$fg[green]%}[$?]%{$reset_color%} %{$fg[cyan]%}[$PWD]%{$reset_color%} $(git_prompt_info) %{$fg[red]%}[`uname -a | tr " " "\n" | grep "e*r*p" | tr "." "\n" | grep "e*r*p"`]%{$reset_color%} %{$fg[yellow]%}$(printf "\n  ➜ ") %{$reset_color%}'
