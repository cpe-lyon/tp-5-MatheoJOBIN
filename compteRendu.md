# Exercice 1

1. 
2. La commande `fdisk -l /dev/sd*` permet de voir les disques et les partitions ainsi que leur format de partition 
3. 
4. `mkfs` est dépréciée, il faut donc utiliser `mkfs.format_de_partition /dev/sdx` pour formater la partition avec le format de fichier
5. La commande `df -T` ne fonctionne pas sur le disque b car il n'est pas encore monté
6. Il faut modifier le fichier /etc/fstab pour rajouter les disques à monter au démarrage 
7. 
8. 
9. 

# Exercice 2

1. `umount /dev/sdx` permet de démonter les disques ou partitions spécifiées
2. 
3. Il faut installer le paquet lvm2 pour pouvoir utiliser `pvcreate /dev/sdb1`
4. `vgcreate vg01 /dev/sdb1` permet de créer le groupe de volume vg01
5. 
6. 
7. 
8. 
9. 