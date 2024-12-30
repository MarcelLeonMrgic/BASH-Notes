==How to declare and call a variable  ==
Declaring a variable is the fucking most easiest thing you can ever im agine! It goes like this:
```varaiblename=value```
To derefenciate a variable you have to put ```$```in front of it. 
```
#!/bin/bash

var="leon"
echo "$var"

```

the output will look like this:
```leon```

==How to put the output of a bash command into a variable===
So just declaring a variable and echo-ing it is pretty boring. Something more interisting is to save the output of a bash variable into a variable.
``` files=$(ls)```

so when we ```echo files``` it will echo everything ```ls``` would have printed out at the moment of execution. so if we save the output of ls in a variable it will run in the background and then save the output in files.

==Pre declared variables== 
Some variables exist without that we declared them. Those are the default system variables for example ```$USER``` which has the user as a string stored in it.
Those variables are 99% of the time declared in uppercase so it is a good habit to declare your own variables in lowercase.