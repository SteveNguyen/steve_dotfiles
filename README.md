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
- gnu global (sudo apt-get instal global)

required packages (M-x package-install):

- jedi (then M-x jedi:install-server, then create simlink .emacs.d/elpa/jedi ->.emacs.d/elpa/jedi-xxxxx)
- sphinx-doc
- iregister
- cheatsheet
- string-inflection
- *auto-complete
- *auto-complete-c-headers
- iedit
- ace-jump-mode
- multiple-cursors
- sublimity
- expand-region
- calfw
- calfw-org
- epc
- browse-kill-ring+
- py-autopep8 (python-autopep8)
- aggressive-indent
- clang-format
- *helm-gtags (requires gnu global)
- helm-rtags
- powerline (https://github.com/powerline/fonts)
- neotree
- which-key
- volatile-highlight
- all-the-icons
- doom-themes
- molokai-themes
- rainbow-delimiter
- smart-mode-line
- smart-mode-line-theme
- highlight-indent-guides
- *yasnippet
- org-bullets
- flycheck-pyflakes (pip install pyflakes)
- flycheck-grammalecte
- company-irony (launch M-x irony-install-server)
- company-irony-c-headers
- company-auctex
- company-bibtex
- *company-c-header
- irony-eldoc
- rtags
- flycheck-irony
- string-inflection
- visual-regexp
- tabbar-ruller
- cmake-ide (rtags, flycheck, autocomplete-clang, company-clang, irony, needs clang, libclang, libclang-dev) see: https://github.com/atilaneves/cmake-ide
  (use clang-3.6 libllvm3.8?)
  infos about rtags integration: https://syamajala.github.io/c-ide.html
  	      	    		 https://github.com/Andersbakken/rtags
				 https://vxlabs.com/2016/04/11/step-by-step-guide-to-c-navigation-and-completion-with-emacs-and-the-clang-based-rtags/

TODO: helm (helm-swoop)
      use-package
      lsp-mode?

#zsh

- curl -L https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh | sh
- install fasd: https://github.com/clvv/fasd.git
