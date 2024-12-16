# linux_setup

## Files needed to setup a new linux box

I use Ubuntu and Raspberry Pi and need to setup similar stuff on my various devices:

- python
- jupyter
- latex
- vim
- syncthing
- obsidian
- ...

This repo is used to help me setup a new machine with as little pain as possible.



### Syncthing

- copy `syncthing.service` to `~/.config/systemd/user` and then enable and start the service based on this page:

[https://docs.syncthing.net/users/autostart.html#linux](https://docs.syncthing.net/users/autostart.html#linux)

**Note:** In my experience, syncthing does not like to run as root, so start it as a user service
