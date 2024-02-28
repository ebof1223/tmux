#Bindings
prefix + ..
& close window
% horizonal split
z toggle zoom on current pane
! pane > window
x kill pane
s active sessions 

tmux a, attach to last session

name session tmux new -s my-session
tmux kill-session -t <session_number>
source ~tmux.conf dir
