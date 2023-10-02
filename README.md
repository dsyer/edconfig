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

