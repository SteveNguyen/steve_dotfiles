#Emacs stuffs:

 - git clone
 - git submodule init
 - git submodule update

Create symlinks:

- dot_emacs -> ~/.emacs
- dot\_emacs_d -> ~/.emacs.d
- dot\_emacs\_auto -> ~/.emacs_auto (you probably have to configure your email here)

required package:

- virtualenv (sudo pip install virtualenv)
- jedi (sudo pip install jedi)
- epc (sudo pip install epc)

required packages (M-x package-install):

- jedi (then M-x jedi:install-server, then create simlink .emacs.d/elpa/jedi ->.emacs.d/elpa/jedi-xxxxx)
- auto-complete
- epc
- browse-kill-ring+
- py-autopep8 (python-autopep8)


#zsh

- curl -L https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh | sh
- install fasd: https://github.com/clvv/fasd.git
