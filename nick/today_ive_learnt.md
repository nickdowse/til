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
