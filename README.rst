powerline-config
================

Installation
------------

Start by installing powerline using these docs:

http://powerline.readthedocs.org/en/master/installation.html

Install powerline-gitstatus (do not use
the provided config files):

https://github.com/jaspernbrouwer/powerline-gitstatus#installation

A `.config` direction for powerline should have been created, if it
wasn't for some reason create the powerline directory inside your `.config`
directory.

Once you've created the powerline directory copy the contents from my repo
in the powerline directory to your powerline directory:

https://github.com/gravyboat/powerline-config/powerline

The key file that no one seems to mention is the `config.json`. This will
force the actual changes to take effect, and without this file you'll still
be using the default configuration. While that may work I prefer everything
aligned on the left side of the screen.

Once this is complete check to make sure the linting is fine with
`powerline-lint` and if everything looks fine restart the daemon with
`powerline-daemon --replace`. You should now see the status of the git repo
on the powerline prompt when you're in a repo directory.
