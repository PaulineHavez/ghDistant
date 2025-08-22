Ce projet contient le hook pre-commit qui permet d'enregistrer la date et l'heure d'un commit. 

Afin de pouvoir utiliser ce hook, copier le contenu du fichier hooks-shared/pre-commit dans un fichier nommé 'pre-commit', du dossier .git/hooks.

Afin de rendre le hook exécutable, exécuter la commande : chmod +x .git/hooks/pre-commit

Lorsque vous commiterez, si vous souhaitez sauvegarder la date et l'heure du commit, répondre "y" à la question posée lorsque que vous aurez exécuté une commande git commit -m.