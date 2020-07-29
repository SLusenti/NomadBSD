### About

FreeBox want to port NomadBSD openbox environment on FreeBSD.

tested on freebsd 12-release and freebsd 13-current

### install

make sure if you run as gust to install first the required drivers

if you use intel embedded graphic than
```bash
pkg install graphics/drm-kmod
kldload i915kms
echo 'kld_list="i915kms"' >> /etc/rc.conf
```

to install FreeBox

```bash
# install requirements
pkg install xorg bash rsync

# than run install.sh
cd FreeBox
./install.sh
``` 


### Screenshots
![](http://nomadbsd.org/screenshots/nomadbsd-1.3-RC1-ss1.png)
