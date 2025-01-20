##### .xinitrc 
redshift -P -O 4500
./.sbar.sh &
xset r rate 300 50
~/.fehbg &
setxkbmap -option caps:escape
exec dwm

##### alias
alias ls='ls --color=auto'
alias grep='grep --color=auto'
alias p='sudo pacman'
alias vi='nvim'
alias x='startx'
alias svi='sudo nvim'
alias cam='ffplay /dev/video0'
alias open='setsid -f xdg-open'

##### prompt
PROMPT='%1d%F{cyan}%#%f '
