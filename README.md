# How to initialize Git

Refer below
https://www.lainyzine.com/ko/article/creating-ssh-key-for-github/


1. install git
2. make directory on windows
3. excute bash ssh on the directory
4. configure ssh settings
    cd ~/.ssh
    ssh-keygen -t ed25519 -C "nuega2833@gmail.com"
    cat id_ed25519.pub
    clip < ~/.ssh/id_ed25519.pub
    vi ~/.ssh/config
    ssh -T git@github.com
    git clone git@github.com:gwanwoonam/docs.git
    cd docs/
    ls -l