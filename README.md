# Partage de fichiers sous Windows


# Partage SMB
Quête WCS partage de fichier sous Windows Server 2022


## 1) Création des répertoires de partage sur le serveur

![SMB](https://github.com/Hebus79/Partage_fichiers_SMB/blob/main/images/Creation_repertoires.png)



## 2) Création des utilisateurs et des groupes dans l'AD

![SMB](https://github.com/Hebus79/Partage_fichiers_SMB/blob/main/images/Creation_utilisateurs_et_groupes_dans_AD.png)


## 3) Configuration du partage dans le gestionnaire de serveur


![SMB](https://github.com/Hebus79/Partage_fichiers_SMB/blob/main/images/Gestionnaire_serveur_partages.png)

![SMB](https://github.com/Hebus79/Partage_fichiers_SMB/blob/main/images/Partage_SMB.png)



## 4) Liste des partages sur le serveur avec la commande Powershell Get-Smbshare

![SMB](https://github.com/Hebus79/Partage_fichiers_SMB/blob/main/images/get-smbshare.png)


## 5) Réglage des droits d'accès

![SMB](https://github.com/Hebus79/Partage_fichiers_SMB/blob/main/images/.png)
![SMB](https://github.com/Hebus79/Partage_fichiers_SMB/blob/main/images/.png)

## 5) Montage d'un disque réseau sur un client sous Windows avec la commande Powershell New-PSDrive


![SMB](https://github.com/Hebus79/Partage_fichiers_SMB/blob/main/images/Montage_disque_reseau_powershell.png)

## 6) Test des accès depuis le poste client avec différents comptes utilisateurs

Possible d'écrie dans le repertoire Direction avec le compte WilderDirection
![SMB](https://github.com/Hebus79/Partage_fichiers_SMB/blob/main/images/Possible_d'ecrire_dans_direction.png)
Impossible d'écrire dans le reprtoire RH avec le compte WilderDirection
![SMB](https://github.com/Hebus79/Partage_fichiers_SMB/blob/main/images/Impossible_d'ecrire_dans_direction.png)



## 7) XXXX


![SMB](https://github.com/Hebus79/Partage_fichiers_SMB/blob/main/images/.png)


## 8) XXXXX

![SMB](https://github.com/Hebus79/Partage_fichiers_SMB/blob/main/images/.png)




## 8) Vérifier que la GPO s'applique bien en se connectant avec un client Windows au domaine "Wilders.lan" et avec un utilisateur appartenant au groupe "Students"
