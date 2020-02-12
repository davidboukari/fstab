# fstab

* See: https://www.linuxtricks.fr/wiki/fstab-explications-sur-le-fichier-et-sa-structure

```bash
blkid
UUID="xxxxxx"

Edit /etc/fstab (uuid, mount_point, fs_type, option, ?, fsck check priority [0-2] (for / => 0, for another 2) 
```
UUID="xxxxxx"  /mypath  xfs rw,nosuid,nodev,noexec,relatime,attr2,inode64,noquota,user 0 2
```
