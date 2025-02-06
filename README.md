https://www.atlassian.com/git/tutorials/dotfiles

```
sudo setup-timezone Asia/Kuala_Lumpur
```

as root:
```
echo "shortname" > /etc/hostname

hostname -F /etc/hostname
```


flatpak:
```
cd /var/lib/flatpak/repo/
mkdir refs
sudo mkdir refs
cd refs/
sudo mkdir remotes
sudo mkdir heads
```
