# pear - tmux helper for pair programming sessions

Pear is a very simple wrapper for having pair programming sessions on a server.
Kind of like wemux ultra light.

## Installation

Clone it into your home directory and source the pear file from your bashrc or
similar.

## Usage

```
start_session <session_name>  # starts a session
join_session <session_name>   # joins a session
start_session <session_name>  # lists running sessions
```

## Issues

Right now the chgrp-ing of the socket file does not work, this needs to be
fixed.
