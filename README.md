# pear - tmux helper for pair programming sessions

Pear is a very simple wrapper for having pair programming sessions on a server.
Kind of like wemux ultra light.

## Installation

Clone it somewhere into your home directory:

```
git clone git@github.com:effkay/pear.git ~/.pear
```

Source it in your init scripts like zshrc, bashrc or similar:

```
echo "source $HOMEDIR/.pear/pear" >> ~/.bashrc && reload
```

## Usage

```
start_session <session_name>  # starts a session
join_session <session_name>   # joins a session
list_sessions                 # lists running sessions
```

## Issues

Right now the chgrp-ing of the socket file does not work, this needs to be
fixed.
