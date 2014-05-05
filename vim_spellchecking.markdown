Spell Checking
==============

  :set spell!     toggle highlighting misspelled word
	<leader> s
  ]s [s           move to next and previous mistakes

  z=              enter list of options
  1z=             change directly to first suggestion

  :windo set spelllang=en_uk      set language for window
  :bufdo set spelllang=en_uk      set language for buffer

  zg              add word to spell file
  zw              add bad word to spell file
  zuw             restore as good word
  zug             restore as bad word
  :runtime spell/cleanadd.vim     clean the word list
