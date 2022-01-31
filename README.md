# zsh-config
My Zsh Config

## Installation
* download & install plugins
    ```CMD=
    # install zsh & oh-my-zsh
    sudo apt-get install zsh
    sh -c "$(wget https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"
    
    # change shell 2 zsh
    chsh -s /bin/zsh

    # download powerlevel10k
    git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k

    # download auto-jump
    git clone git://github.com/joelthelion/autojump.git
    cd autojump
    python3 install.py

    # download auto-suggestion
    git clone git://github.com/zsh-users/zsh-autosuggestions $ZSH_CUSTOM/plugins/zsh-autosuggestions

    # download syntax-highlighting
    git clone git://github.com/zsh-users/zsh-syntax-highlighting $ZSH_CUSTOM/plugins/zsh-syntax-highlighting
    ```
* config my zsh
    ```CMD=
    git clone https://github.com/wubinary/zsh-config.git
    cd zsh-config

    cp .p10k.zsh .zshrc ~/
    ```
