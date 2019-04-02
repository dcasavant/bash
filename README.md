# Custom Bash

These are personal bash configurations, aliases, and other tweaks.  You are welcome to use and extend them as you see fit.

## Using custom bash

To use this bash configuration, copy `bash_ext` to your home directory (add a '.' in front) and add the following line to the bottom of your `~/.bash_profile`:

    . ~/.bash_ext || echo "***  Unable to load bash ext. Profile settings are offline."

The next time your bash profile is loaded (such as opening a new terminal session or logging in), the bash profile changes should be applied.
