Buffer, windows & tabs
======================

  :ls             list buffer

  :bn             view next and previous buffers
	:bp

  :bd!            force remove a bffer discarding change

  :sp[lit]        horizontal split
	ctrl-w s
	:sp name.txt  split and open a file in a new window

  :vs[p[lit]]     vertical split
	ctrl-w v
	:vs name.txt  split and open a file in a new vertical window

  :on[ly]         keep only that window

  ctrl-^          move to alternate buffer
  ctrl-w w        cycle through winoes
  ctrl-w h j k l  move to corresponding window

  ctrl-w + -      change height of current window by 1 line
  ctrl-w _ |      maximaze width of current window

  ctrl-w rR       rotate the windows
  ctrl-w x        swap a window with its neighbour
  ctrl-w HJKL     move current window to corresponding max place

  :tabe[dit]      edit in a new tab
  ctrl-w T        move current split into a new tab
  :tabc[lose]     close the current tab
  :tabo[nly]      same as :only but for tabs

  gt gT           move to previous and next tab
  #gt             move to tab number #

  :tabmove        puts current tab at the end
  :tabmove 0      puts current tab at beginning
  :tabmove 1      puts current tab after tab 1, the second

  g;              move backwards in the changelist
  g,              move forward in list of positions (changelist)
  :changes        displays the changelist

  ctrl-o          move backwards in the jumplist
  ctrl-i          move forwards in the jumplist
  :jumps          displays the jumplist
