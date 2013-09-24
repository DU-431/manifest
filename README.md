Get Repo
---------------------------------------

    mkdir ~/bin
    export PATH=~/bin:$PATH
    curl https://dl-ssl.google.com/dl/googlesource/git-repo/repo > ~/bin/repo
    chmod a+x ~/bin/repo

Syncing the DU Source
---------------------------------------

    mkdir ~/dirtyunicorns
    cd ~/dirtyunicorns
    repo init -u https://github.com/DU-Final/manifest.git -b du43
    repo sync -j 4 | 8 | 16 | 24 | 32

