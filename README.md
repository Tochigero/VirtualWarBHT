#VirtualWarBHT


Dépôt git pour le projet **Virtual War** de la team **BHT**.

#Utiliser le repository
##Installer EGit

Nous utilisons le plugin **EGit** avec Eclipse.

D'abord,il faut ouvrir l'utilitaire d'installation des plugins :
> Help => Install new Software

Cliquer sur **Add**, entrez l'url : http://download.eclipse.org/egit/updates , et en nom "EGit".

Dérouler le menu *Eclipse Git Team Provider* et cocher *Eclipse Git Team Provider*.

*Eclipse Git Team Provider Source code*, *Task ...* et *JGit* doivent rester décoché.

Laisser les box du bas dans l'état ou elles sont (Normalement une décochée, le reste cochée), puis cliquer sur next.


Suivez les instructions pour installer, jusqu'à ce que Eclipse demande de redemarrer (obéisse lui !).


##Configurer EGit

> Window => Preferences => Git => Team => Default Repository Folder

Pour changer le dossier ou seront stockés les repository (dépôts), ça se passe ici ! Le dossier ne doit pas bouger par la suite, et ne doit pas être votre workspace eclipse.

Ensuite, dans le menu

> Git => Configuration

Cliquer sur "Add Entry"

> Clé : user.name / Value.Name : Ton Nom (Exemple : Alexandre Beaudet)

Puis encore une fois

> Clé : user.email / Value/Name : Ton email (Exemple : badeu.tibeuh@gmail.com)

La dernière étape étant d'activer la toolbar :

> Window => Customize perspective

Et dans les command groups, ajouter **Git** et **Git Navigation Actions**.

Enfin :

> Window => Show View => Other ... => Git => Git Staging

Git est donc configuré, il suffit maintenant d'ajouter le projet.

##Récuperer le dépôt

> File => Import => Git => Project from Git

> Url

Dans URL : *L'url du dépôt, dispo sur Git Hub*
Host : *Laisser par défaut (github.com*
Tout laisser par défaut, puis **next**.

Laisser tout cocher sur la page "Import projects from git, puis **next**.

Encore un **next**.

> Use the new project wizard

Créer le projet en ne donnant que le nom : **VirtualWar**.

Une fois le projet créé, clic droit dans le navigation view (tout à gauche)

> Team => Share => Git => Repository: VirtualWarBHT

Puis **Finish**.

Le projet projet est maintenant prêt à être utilisé avec Git !

##Utiliser le dépôt

A chaque fois que vous lancerez le projet (donc avant de commencer à coder) :

> Git => Pull (dans la toolbar)

Ensuite, une fois que les changements effectués en codant vous conviennent, ou qu'une nouvelle classe a été crée, sauvegarder comme d'habitude, puis :

> Git => Commit

Entrer dans la description vos actions effectuées (en anglais please), de manière concise et claire. Puis selectionnez les fichiers à envoyer en bas. (Normalement tous ceux proposés). Vérifiez que l'auteur et le committer soient bien renseignés, et cliquez sur **Commit**.

Enfin, avant de quitter Eclipse, il suffira d'utiliser
> Git => Push to upstream

Pour envoyer votre travail dans le dépôt, et que les autres puissent le récuperer avec un pull !

##Pourquoi utiliser Git ?

D'une part, comme dans google drive, cela permet de partager facilement le code entre nous. De plus, Git offre en arrière un gestionnaire de version, permettant de récuperer un ancien fichier, de vérifier qui à modifier quoi (à la ligne de code prêt), et ainsi de mieux gérer un projet avec de nombreuses versions !

Pour toutes questions :

> Selena.Zelia@gmail.com

Bisous sur vos fesses !
