Get Repo
---------------------------------------

    mkdir ~/bin
    PATH=~/bin:$PATH
    curl http://commondatastorage.googleapis.com/git-repo-downloads/repo > ~/bin/repo
    chmod a+x ~/bin/repo

Syncing the DU Source
---------------------------------------

    mkdir ~/dirtyunicorns
    cd ~/dirtyunicorns
    repo init -u https://github.com/DU-Final/manifest.git -b du43
    repo sync -f -j 4 | 8 | 16 | 24 | 32

