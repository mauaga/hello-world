    cd dotfile/
    git clone https://github.com/mauaga/dotfile
    git config user.name 'Anonymous'
    git config user.email '<>'
    git remote -v
    ssh-keygen -t rsa
    cd .ssh/
    vi id_rsa.pub + copy in github.com settings add ssh key
    git remote set-url origin git+ssh://git@github.com/mauaga/dotfile.git
    git remote -v
    vi README.md   
    git add .
    git commit -m"Modificato README.md con commento di test"
    git push -u -f origin main
