# 4/3/2016

Bash if statements require a statement in the 'if' rather than just the else:

This will work:
``` 
if test -n "$(bundle exec spring status | grep 'Spring is running:')"
then
  echo "Spring is running!"
else
  bundle exec spring start
fi
```

This won't work:

``` 
if test -n "$(bundle exec spring status | grep 'Spring is running:')"
then
else
  bundle exec spring start
fi
```


# 5/3/2016

You can use `0` to get to the start of the line in vim

# 6/3/2016

How to setup ZSH, the `$LESS` variable on unix. 

# 7/3/2016

How to install plugins in Vim, how to create a theme in ZSH, how to install, uninstall, and reinstall MySQL. RVM (or Rbenv) has to be installed before bundler and other gems.

# 8/3/2016

How to create a moving video background for a homepage hero. Requires three videos, all formatted differently, and a cover image.

# 9/3/2016

How to move files with Ruby, move folders, and how to run a spec that is inside an app inside a gem that references and uses the gem that contains it.

# 10/3/2016

jQuery's hover function takes in two functions which it executes, one on hover in and one on hover out, if you only provide one function it will execute it twice.

Foundation has a Box-Grid class
