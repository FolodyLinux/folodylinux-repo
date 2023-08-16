# folodylinux-repo
repo for folodyos
# how to add repo to arch linux?
add this line to `/etc/pacman.conf`
```
[folodylinux-repo]
SigLevel = Optional TrustAll
Server = https://folodyos.github.io/$repo/$arch
```
or type this on terminal
```
printf "[folodylinux-repo]\nSigLevel = Optional TrustAll\nServer = https://folodyos.github.io/$repo/$arch"
```
