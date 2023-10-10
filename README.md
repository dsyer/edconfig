```
$ sudo mount -t cifs //alien/Users/david /mnt/alien -o user,username=david_syer@hotmail.com,password=<pwd>,uid=1000,gid=1000
```

Fetch updates:

```
$ cp /mnt/alien/AppData/Local/Frontier\ Developments/Elite\ Dangerous/Options/Bindings/Custom.4.0.binds /mnt/alien/Documents/ed/Bindings/
```

Apply changes:

```
$ cp /mnt/alien/Documents/ed/Bindings/Custom.4.0.binds /mnt/alien/AppData/Local/Frontier\ Developments/Elite\ Dangerous/Options/Bindings/
```

Enable [SSHD](https://shendrick.net/Gaming/2022/05/30/sshonsteamdeck.html) on Steam Deck:

```
$ sudo systemctl enable sshd
```

(or just `start` and `stop` manually).

Sync from Deck:

```
rsync -r "steamdeck:/home/deck/.steam/steam/steamapps/compatdata/359320/pfx/drive_c/users/steamuser/Saved Games/Frontier Developments/Elite Dangerous/" ~/Documents/journals/
```