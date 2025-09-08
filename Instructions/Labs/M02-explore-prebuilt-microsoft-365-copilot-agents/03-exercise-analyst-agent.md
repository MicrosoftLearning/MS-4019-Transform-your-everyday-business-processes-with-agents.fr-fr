Les organisations étant de plus en plus axées sur les données, la capacité d’interpréter et de communiquer rapidement des informations brutes est une compétence essentielle. L’agent Analyste de Microsoft 365 Copilot permet aux utilisateurs de le faire simplement en analysant et en visualisant les données directement dans des outils bien connus comme Excel et Forms. Cette activité fournit une procédure pratique d’utilisation de l’agent Analyste pour donner un sens aux jeux de données existants, que ce soit des enquêtes, des feuilles de calcul ou des résultats de sondage, et de les transformer en informations exploitables avec un minimum d’efforts.

Dans cet exercice basé sur des scénarios, vous allez apprendre à utiliser l’agent Analyste pour explorer les tendances, identifier les anomalies et générer des visuels qui améliorent le partage de données. Que vous prépariez des rapports sur les performances de l’équipe, les commentaires des clients ou les métriques opérationnelles, cette activité vous montre comment passer d’un nombre brut à un résumé clair ou à des graphiques prêts pour les parties prenantes. Il s’agit d’un moyen efficace de gagner du temps, de réduire les efforts manuels et de renforcer la confiance dans votre prise de décision analytique avec un support basé sur l’intelligence artificielle.

### Exercice

Vous êtes chargé d’analyser les résultats de l’enquête qui se rapportent à une initiative interne de l’entreprise appelée « Project Nexus », un programme pilote de six semaines visant à améliorer la collaboration inter-départements via une nouvelle plateforme d’espace de travail numérique. Le projet a impliqué des employés de différents services, notamment le service informatique, les RH, les départements marketing et opérations, qui ont été invités à utiliser la plateforme pour la communication quotidienne, le partage de documents et la gestion des tâches. L’objectif du projet était d’évaluer l’efficacité de la plateforme pour améliorer la productivité, simplifier la communication et respecter les échéances du projet. 

Une fois le pilote terminé, les participants ont été interrogés pour évaluer leur niveau de satisfaction du projet, la clarté et l’efficacité de la communication, le respect de la chronologie proposée et leur expérience globale avec le nouveau système. Vous prévoyez d’utiliser l’agent Analyste prédéfini du Microsoft 365 Copilot pour explorer les résultats de l’enquête de Project Nexus. Comme pour tout agent prédéfini, vous pouvez saisir vos propres invites personnalisées ou utiliser les invites de démarrage de l’agent. Les invites de démarrage de l’agent Analyste sont conçues pour produire des analyses quantitatives, qualitatives et de visualisation, ainsi que des informations et des recommandations globales sur le projet.

Effectuez les étapes suivantes pour indiquer à l’agent d’Analyste d’interpréter et de visualiser les résultats de l’enquête concernant Project Nexus :

1. Sélectionnez le lien suivant pour télécharger une copie des [Résultats de l’enquête de Project Nexus](https://github.com/MicrosoftLearning/MS-4004-Empower-workforce-copilot-use-cases/raw/refs/heads/master/ResourceFiles/Project_Nexus_survey_results.xlsx). Sélectionnez le bouton **Télécharger** en haut de l’écran pour enregistrer le fichier sur votre appareil.
1. Dans **Microsoft Edge**, ouvrez un nouvel onglet et entrez l’URL suivante : [**https://M365copilot.com**](https://M365copilot.com)
1. Dans **Microsoft 365**, sélectionnez l’agent **Analyste** s’il apparaît dans le volet de navigation sous la section **Agents**. Dans le cas contraire, sélectionnez **Tous les agents** dans le volet de navigation, puis, dans la fenêtre **Magasin d’assistants**, sélectionnez **Analyste** dans la section **Créé par Microsoft**. 
1. Dans **Microsoft 365**, la fenêtre de l’agent **Analyste**s’affiche. Dans le champ d’invite, sélectionnez l’icône **Ajouter du contenu et des agents**, qui est l’icône du signe plus (+****). 
1. Dans le menu qui s’affiche, sélectionnez **Charger à partir de cet appareil**. Dans **Explorateur de fichiers**, accédez au dossier **Téléchargements**, sélectionnez le fichier **Résultats de l’enquête Project Nexus** que vous avez téléchargé précédemment, puis sélectionnez **Ouvrir**. 
1. Dans le champ d’invite, saisissez l’invite suivante à côté du fichier lié des résultats de l’enquête Project Nexus : **Analysez ce tableur et indiquez-moi les trois principales tendances**.

   > [!NOTE]
   > Observez comment l’agent Analyste exécute plusieurs commandes Python pour obtenir sa liste définitive de tendances. Vous devrez peut-être attendre une minute ou deux pour que toutes les commandes soient exécutées afin d’agréger les résultats et de déterminer les trois premières tendances. Chaque commande est suivie d’une description des résultats obtenus. Continuez à faire défiler les résultats vers le bas pour voir les trois principales tendances.
1. Pour explorer plus en profondeur chaque catégorie, commencez par saisir l’invite suivante : **Quelle est l’évaluation moyenne pour chaque catégorie d’enquête** ?
1. Dans nos tests, l’agent retourne ce qui semble être une page vierge. En réalité, il ne s’agit pas d’une page vierge ; il s’agit simplement d’un grand bloc d’espace vide entre la réponse de l’agent et le champ d’invite. Si la même chose se produit, faites défiler la page vers le haut à l’aide de la barre de défilement verticale et vous devriez trouver la réponse. De même, si vous faites défiler jusqu’au bas de la page, le champ d’invite doit s’afficher. Cet agent étant nouveau, il semble que tout cet espace vide constitue un problème qu’il faut résoudre. En revanche, au moment où vous effectuez cet exercice, ce problème d’espace vide supplémentaire a peut-être été résolu. Dans les deux cas, passez en revue les résultats. Si l’agent Analyste vous propose de passer à l’étape suivante, par exemple « Voulez-vous une comparaison visuelle de ces moyennes ? » puis saisissez **Oui** dans le champ d’invite (si le problème d’espace vide persiste, vous devez faire défiler jusqu’au bas de la page pour afficher le champ d’invite).
1. Là encore, faites défiler jusqu’aux résultats de l’invite précédente (si nécessaire) et examinez-les.
1. À ce stade, vous pouvez consacrer autant de temps que vous le souhaitez à l’analyse des résultats de l’enquête à l'aide de l’agent Analyste. Vous pouvez saisir vos propres invites personnalisées ou, si vous le souhaitez, essayer l’une de ces invites en fonction du type d’analyse que vous souhaitez effectuer :
   - Invites d’analyse quantitative :
      - **Quelle catégorie a reçu l’évaluation moyenne la plus élevée et laquelle a reçu la moyenne la plus faible** ?
      - **Combien de participants ont attribué une note de satisfaction de 4 ou plus au projet **?
      - **Quel pourcentage de participants a attribué une note inférieure à 3 au respect du calendrier** ?
      - **Pouvez-vous identifier des corrélations entre l’efficacité de la communication et l’expérience globale** ?
   - Invites d’analyse qualitative :
      - **Résume les thèmes les plus courants dans la section commentaires**.
      - **Y a-t-il des problèmes récurrents ou des suggestions mentionnées dans les commentaires** ?
      - **Identifie les commentaires qui mentionnent des problèmes de communication ou de chronologie**.
   - Informations et invites de recommandation :
      - **Selon les données de l’enquête, quelles sont les trois principales forces de Project Nexus** ?
      - **Quels sont les principaux domaines d’amélioration suggérés par les participants** ?
      - **Fournis un rapport de synthèse des résultats de l’enquête avec des recommandations exploitables**.
   - Invites de visualisation quantitative :
      - **Génère un graphique à secteurs de la distribution globale des évaluations**.
      - **Crée un graphique à barres comparant les évaluations moyennes de la satisfaction du projet, de l’efficacité des communications, de l’adhésion au calendrier et de l’expérience globale**.
      - **Trace un histogramme des évaluations de satisfaction pour voir la distribution des évaluations**.
      - **Génère un nuage de points pour analyser la relation entre l’efficacité de la communication et l’expérience globale**.
      - **Crée une carte thermique de corrélation pour toutes les catégories d’évaluation numériques**.
      - **Crée un tracé de zone pour chaque catégorie d’évaluation afin d’afficher la plage et les quartiles**.
      - **Trace un graphique à lignes montrant les évaluations d’adhésion à la chronologie sur les participants classés par ID de participant**.
