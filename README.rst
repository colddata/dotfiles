Config files and such to drop in ~

(To be cool like clouserw and jbalogh)

::

    git clone to ~/dev/dotfiles
    cd ~/dev/dotfiles
    for f in .[a-z]*; do ln -s ~/dev/dotfiles/$f ~/$f; done
    
And then unlink ~/.git which will be a link to this repo.
TODO: one day rewrite the above into a fancy find command
with a proper -exclude flag for .git$
