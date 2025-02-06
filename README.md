

Config version control:

https://www.atlassian.com/git/tutorials/dotfiles

Set timezone:

```
sudo setup-timezone Asia/Kuala_Lumpur
```

Set hostname (as root):
```
echo "shortname" > /etc/hostname

hostname -F /etc/hostname
```


Fix flatpak:
```
sudo apk add flatpak
cd /var/lib/flatpak/repo/
mkdir refs
sudo mkdir refs
cd refs/
sudo mkdir remotes
sudo mkdir heads
```

Bitwarden:
```
sudo apk add rbw
rbw register
rbw get api.github.com|wl-copy
```

