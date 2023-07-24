# folodyos-repo
repo for folodyos
# how to add repo to arch linux?
add this line to `/etc/pacman.conf`
```
[folodyos-repo]
SigLevel = Optional TrustAll
Server = https://folodyos.github.io/$repo/$arch
```
