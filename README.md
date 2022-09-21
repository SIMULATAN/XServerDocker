# XServerDocker
This docker image allows you to run a X server with VNC within docker.
Based on Debian Bullseye (Slim)

## Usage
When you first start the `docker-compose` file and you successfully connect via VNC, you'll see a black screen.
This is because that is how a minimal X server setup without any DE, WM or Window looks like.
This image is a bare minimum setup, you'll have to provide the WM yourself.
An example with DWM and ST can be found [here](https://github.com/SIMULATAN/XServerDocker-dwm-st).

If you have any questions, just raise an issue and I'll respond as soon as I can.

## Credits
This repo is strongly based on [suchja/x11server](https://github.com/suchja/x11server), thanks for the original version!
