git-save
========
I kept forgetting that I had stashed code, and had a hard time tracking
which branch the stash belonged to. Got the idea of creating branches for
my uncommited code.

Publishing it at github in hope it can be useful for someone else.

```
knirch@traktor:~/source/external/git-save (master %)$ echo "# foo" >> git-save
knirch@traktor:~/source/external/git-save (master *%)$ git save
[save/master-feb65f3-20160123-201440 6cc604e] WIP on feb65f3: Initial commit
 1 file changed, 1 insertion(+)
knirch@traktor:~/source/external/git-save (master %)$ git branch 
* master
  save/master-feb65f3-20160123-201440
```


Acknowledgments
---------------
Implementation inspired by the 'save' alias at
https://codingkilledthecat.wordpress.com/2012/04/27/git-stash-pop-considered-harmful/

License
-------
git-save is public domain, see UNLICENSE or http://unlicense.org for more information.
