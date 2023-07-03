# TAI5-MAG

## Sommaire 

* Histoire de Linux
* Les grandes familles

## Histoire de Linux

* Créé par Linus Torvalds au début des années 1990
* Portage d'Unix vers les ordinateurs de bureau
* Linux= **noyau**, GNU/LINUX= **OS**
*  Explosion à la fin des années 1990

### Distribution Linux

* Une distribution est composée :
* du noyau Linux
* des applications de base GNU
* d'un ensemble d'autres applications choisies par le **mainteneur** ( éditeur) de la distribution

  Les commandes de base sont donc communes à toutes les distributions


### Les Familles

Une famille des distribution est l'ensemble de distributions qui partagent un socle commun.

* Debian: distribution libre gérée par une fondation à but non lucratif, hyper stable
*  Ubuntu: distribution commerciale gérée par l'entreprise Canonical
*  Mint:
*  Red Hat:
*  RHEL: red hat entreprise Linuxv-distribution commerciale payante
*  CentOS: version communautaire de la RHEL

### La manipulation des fichiers et des répertoires

* où suis-je ? `pwd`
* Afficher le contenu d'un dossier? `ls`
* Changer de répertoire courant? `cd` + le répertoire `cd/tmp`
   * `cd` sans argument ramène dans le répertoire personnel
   * `cd -` revient au dossier précédent
   * créer un fichier vide `touch`
   * éditer un fichier `nano` + le nom de fichier
   * compresser un fichier/dossier `tar cvf` + nom de l'archive d'un fichier/dossier à compresser
   *  sans compression : `tar cvf archive.tar /home/barth/projets`
   *     *  avec compression : `tar czvf archive.tar.gz /home/barth/projets`
  * extraire une archive tar : `tar xzvf glpi.tar.gz`
  *  Afficher le contenu d'un fichier : `cat`+ chemin vers le fichier
  *  compter le nombre de lignes dans un fichier `wc -l` + chemin vers le fichier
  *  afficher la fin d'un fichier `tail`+ chemin vers le fichier
  *  afficher en temps réel la fin d'un fichier `tail -f`+ chemin vers le fichier
  *  afficher les lignes du fichier /etc/passwd qui contiennent le mot barth `grep barth /etc/passwd`
  *  créer un utilisateur `useradd thierry`
  *  commande complète : `useradd -m -d /home/thierry -s /bin/bash thierry`
 
* Pour créer le groupe apprenants:
*  `usermod -aG apprenants thierry`

*  Pour vérifier la liste des groupes de l'utilisateur thierry:
*  `groups thierry`

*  
