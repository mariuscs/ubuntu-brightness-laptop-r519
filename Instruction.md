#Installation instruction

# Quick start #

This solution doesn't require you to recompile kernel, this is only SINGLE(ONE) script. Just follow installation bellow.


# INSTALLATION #

You need Python 2.3 for this script to work.

# Just copy this file to /usr/local/bin/brightness and make it executable.

```
 chmod a+x /usr/local/bin/brightness
```

This script requires root access, so you should enable visudo to not asking you for password every time you execute this script.
To achieve this you should :

**Type: visudo** Edit file so there's 2 lines like this.

```
%admin ALL=(ALL) NOPASSWD:ALL

%sudo   ALL=(ALL:ALL) NOPASSWD:ALL
```

Now check if script runs fine. Execute this from normal account:

```

brightness up
brightness down

```

It should not ask you for password. The brightness should slightly change. Repeat command to change more.


## GUI Installation / Hardware keys ##


You can bind hardware keys for this script in GUI. In UNITY desktop GUI find System Settings -> Keyboard Shortcuts. Add 2 new entries:

```

brightness_up
pointing to /usr/local/bin/brightness up

```


```

brightness_down
pointing to /usr/local/bin/brightness down
```


It should look like this:

http://ubuntuone.com/p/wFi/"
http://ubuntuone.com/p/wFj/"
http://ubuntuone.com/p/wFk/"

That's it. Type FN->Brightness up and down to see how it works.