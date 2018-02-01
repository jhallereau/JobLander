# Projet JobLander
L'application JobLander a pour finalité la mise en place d'une API de dépôt d'annonce d'offre d'emploi.

# I - Technologies employées
Dans le cadre du projet JobLander, nous avons souscrit à l'offre gratuite de MongoDB Atlas comprenant :
- 512Mb de stockage
- 3 facteurs de réplication
- De la RAM partagée
- La version MongoDB 3.4 avec WiredTiger™
- Le fournisseur de cloud est ici Amazon Web Services
  
Notre Cluster comprend actuellement les 3 collections suivantes :
- JobLander.entreprises
- JobLander.avis
- JobLander.emplois
  
Nous avons utilisé la fonctionnalité "Linked Stitch App" pour lier notre base MongoDB à l'application JobLander.
Pour cela, nous avons utilisé le code JS(Browser) fourni dans le head et adapté le Snippet prégénéré à notre projet.

# II - Récupération et installation du projet
1) Ouvrir dans un navigateur l'url suivante : https://github.com/jhallereau/JobLander
2) Cliquer sur le bouton vert "Clone or download", puis sur "Download ZIP"
3) Extraire l'archive précédemment récupérée
4) Lancer depuis votre navigateur le fichier index.html
Le projet est à présent fonctionnel, veuillez consulter la partie suivante pour la prise en main de l'application.

# III - Prise en main de l'application (Nécessite une connexion internet pour les interactions en BDD)
Si l'installation s'est bien déroulée, vous devriez vous trouvez sur la page index.html dans votre navigateur web. Si ce n'est pas encore le cas, je vous invite à consulter la partie II.

Sur l'interface principale, vous disposez de 3 menus:
- Annonce
- Entreprise
- Avis

Dans notre exemple, nous utiliserons la partie Annonce, le principe étant le même pour les 3 interfaces.
1) Ajout d'une annonce
- Renseigner l'ensemble des champs puis cliquer sur "Valider"
- Si l'ajout a bien fonctionné, vous devriez voir une ligne comportant les différents éléments saisis apparaître
 
2) Modification d'une annonce
- Cliquer sur le bouton "Mettre à jour" de la ligne concernée
- Une ligne apparaît, saisissez votre nouvelle valeur dans les champs
- Cliquer sur valide
- Vérifier que la ligne à modifier comporte bien les nouvelles valeurs
- Si la modification a bien fonctionné, vous pouvez cliquer sur le bouton masquer
 
3) Suppression d'une annonce
- Cliquer sur le bouton "Supprimer" de la ligne concernée
- Si la ligne n'est pas directement supprimée de la liste, rafraîchissez la page
- Vérifier la bonne suppression de votre ligne
