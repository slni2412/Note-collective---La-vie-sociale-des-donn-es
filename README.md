<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

# **Enquête sur le classement des flux d’écoute *Spotify***

## Dans quelle mesure *Spotify* remodèle les usages de ses utilisateurs, ainsi que l'organisation de l'industrie musicale à travers sa base de données de classement des flux d'écoute ?

## **Introduction**

## **I - Conception**

### Qui a créé ce jeu de données ? À quelles fins ?

Lorsque Spotify est lancé en 2006, l’enjeu de l’entreprise suédoise était simplement de connecter de rendre accessible au plus grand nombre un catalogue de musique le plus exhaustif possible. En effet, à ces prémices, “La tâche de Spotify est simplement de répondre à la demande de l’utilisateur” (Eriksson, Fleischer, Johansson, Snickars, & Vonderau, 2019).
La base de données qui nous intéresse est le fruit d’une redirection de leur business model qui a fait évoluer la plateforme d’un simple catalogue, à une plateforme sociale et désormais un producteur de recommandation musicale depuis 2013. 

Les détails de l’infrastructure du géant de streaming musical est un des secrets les mieux gardés. Néanmoins, en 2014, l’acquisition de l’éditeur d’analyses de données musicales, The Echo Nest change la donne. En effet, l’introduction de playlists personnalisation mais surtout de la segmentation des publics fut permise grâce à l’implémentation de plusieurs Application Programming Interface (API) qui recueillent des métadonnées sur les artistes musicaux, les albums et les titres, directement à partir du catalogue de données de Spotify. 

![imagenet logo](WebAPI_intro.png)

La captation de ces métadonnées enrichit les algorithmes de recommandations basés sur l’intelligence artificielle. Ainsi, Spotify améliore et personnalise de plus en plus l’expérience d’un utilisateur au fur et à mesure de son flux d’écoute. “Chaque fois qu’un utilisateur effectue une action dans le client Spotify – par exemple, écouter une piste ou rechercher un artiste – un élément d’information (un événement) est envoyé aux serveurs de l'entreprise.” (Eriksson, Fleischer, Johansson, Snickars, & Vonderau, 2019). Fournir la musique aux utilisateurs ainsi que l’extraction des données issues de ces flux d’écoute afin de renforcer la personnalisation sont les deux missions principales de l’infrastructure de la plateforme. Ainsi, la conception de la base données de Spotify qui permet la constitution notamment des classements de flux d’écoute “Top 200” et “Viral 500” mais également de l’ensemble des playlists de recommandation musicales personnalisés émanent de l’application du Machine Learning qui reposent premièrement sur l’apprentissage (training) et la classification (classification) puis successivement à la prédiction (prediction) (Pasquinelli & Joler, 2020). 

![imagenet logo](Nooscope_05 Modes.svg)

Si l’image de marque de Spotify met en avant la volonté de rassembler et de connecter les utilisateurs entre eux tout en leur fournissant une expérience auditive amplifiée et améliorée car unique, les objectifs de cette base de données peuvent être résumés de manière plus pragmatique. La rétention et l’engagement des utilisateurs sur la plateforme sont fondamentaux. En effet, le business model de Spotify repose sur le principe de freemium en offrant un accès gratuit mais restreint à l’application. Si la publicité est présente sur l’interface, celle-ci n’est pas la principale source de revenus de la plateforme.  qui n’est pas vraiment le but final de la stratégie commerciale de ces publicités “n’est pas de concourir à la viabilité économique du service, liée aux abonnements, mais à créer une friction, une cassure dans l’expérience de l’utilisateur pour le pousser à chercher à la contourner, précisément en souscrivant à un abonnement payant” (Pineau. & Fabre, 2021) (Brandall, 2018). Ainsi, l’objectif, à peine voilé, est celui de la recommandation personnalisée. Rendre l’expérience tellement satisfaisante et singulière pour chaque utilisateur qu’aucun autre service de streaming ne pourrait remplacer l’expérience Spotify. Leur recommandation s’étant des classements de flux d’écoute par genre musical, régions du monde, artistes et même humeur, ce qui nous amène à notre deuxième étape du processus de Machine Learning, la classification/catégorisation.

### Quelles catégories sont utilisées pour le représenter ?

## **II - Usages**

### Quels sont les usages de ce jeu de données ?

## **III - Controverses**

### Quelles sont les limites ou les critiques rencontrées par ce jeu données ?

Le jeu de données dont fait l’objet notre étude, à savoir le classement des titres *Spotify*, est sujet, de par sa nature même, à nombre de limites et fait l’objet de certaines critiques que nous pouvons, à travers le spectre des enjeux de quantifications, mettre en lumière. De fait, les polémiques gravitant autour des classements de titres et albums mis en évidence sur les différentes plateformes numériques de *Spotify* prennent racines sur leur conception propre fondée sur l’élaboration d’un algorithme. Le rejet et la distanciation relativement récents de ce dernier, non seulement des artistes, mais également des auditeurs des classements *Spotify* en particulier et des plateformes de streaming en général émanent tous deux des critiques que l’on reconnaît à la prévalence que prennent les nombres dans notre société. De fait, spécialement pertinent dans le cadre de notre étude, la mise en compétition généralisée qui découle de la course à la première place du classement d’écoute dénature pour beaucoup de chanteurs la passion censée être au cœur de leur motivation de produire et partager leur musique. (Supiot, 2015)
 
L’un des facteurs exacerbant la brèche de confiance, générée par les classements *Spotify*, qui sépare les artistes d’un côté et les utilisateurs de l’autre sont les accusations d'achats “d'écoutes digitales” par des “bots” auxquels Spotify doit faire face. En effet, les “bots” ou “robots” représentent un moyen détourné pour la maison de disques représentant l’artiste, mis au courant ou non, de lui obtenir davantage d’écoutes via la mise en ligne de pistes audio par le biais d’un agrégateur numérique, puis par la programmation de plusieurs ‘bots’ pour les écouter en continu et générer des revenus. 
Face à ces controverses, la plateforme *Spotify* est accusée d’être au fait de ces agissements et de choisir délibérément de les ignorer, voire de les orchestrer. Ainsi, pas suffisamment robustes pour être perméable aux critiques acerbes, les écoutes mesurées ne "tiennent" plus aux yeux des utilisateurs. 
De plus, bien que dans le cas particulier de la musique, il puisse être argumentable que le nombre d’écoutes soit corrélé avec l’émotion cathartique de la chanson en question, la “réalité” non-quantifiable des sentiments personnels sont perdu dans la masse statistique qui efface l’expérience unique au profit d’un agrégat détaché de toute subjectivité qui ne retranscrit pas l’individualité des utilisateurs. (Desrosières, 2013)
 
Les dérives du mésusage des données récoltées par *Spotify* alimentent également les critiques à l’encontre de la plateforme de streaming. Le fossé qui sépare la réalité des comportements numériques des usagers nourrit les dangers que représente la vente de données personnelles. De fait, les récentes ventes de données de la base de *Spotify* aux différents réseaux sociaux, plus récemment sur TikTok, mais tout particulièrement le groupe *Meta* par le biais duquel il est désormais directement possible de se connecter et de s’identifier à *Spotify*, à des fins de ciblage publicitaire, contribue à une augmentation de la méfiance de la part des utilisateurs. En effet, le contenu personnalisé découlant de l’analyse des préférences musicales des utilisateurs permet d’entretenir l’effet bulle (Pariser, 2011) qui exacerbe le biais de confirmation déjà omniprésent sur les différentes plateformes. 
Par ailleurs, la précision de ces données est telle qu’elle permet de déduire des traits identitaires d’un utilisateur en fonction des titres écoutés. (Marwick, 2013) Les différentes chansons portant des connotations L.G.B.T.Q.+, ou plus directement, interprétées par des artistes faisant ouvertement partie de ladite communauté, peuvent par exemple suffire quant à l'évaluation et à la création d’un profil d’un utilisateur.
Si la différence sensible entre le « dire faire » et le « faire » représentait auparavant un frein à l’appréhension quantitative des phénomènes sociaux sur les plateformes numériques, cette dernière pourrait désormais être aisément déconstruite par les statistiques découlant de la vente et éventuellement de la publication des données d’écoutes des utilisateurs, et ce, compte tenu du caractère extrêmement personnel que comporte et véhicule la musique, à leur dépens. 

### Quelles réalités ces données/indicateurs sont-ils censés représenter ?

Les données récoltées et mises en avant dans le cadre des classements *Spotify* sont censées témoigner de la popularité des artistes et plus précisément de certaines de leurs chansons à un moment donné. Cependant, ces derniers, comme nous l’avons précédemment mentionné, sont victimes de la méfiance des utilisateurs concernant leur véracité et leur capacité à illustrer la réelle popularité des titres et leurs nombres d’écoutes qui leur sont associées, et ce, notamment en raison de la visibilité de certains d’entre eux qui peut désormais s’acheter au lieu de se mériter. En effet, nous pouvons mettre en avant la pertinence de la loi de Goodhart “Dès qu’une mesure devient un objectif, elle cesse d’être une bonne mesure” (Chrystal & Mizen, 2001) que l’on peut rétorquer à l’usage même de classement afin de définir la popularité d’un artiste et induit de manière implicite les différents comportements qu’un utilisateur “lambda”, dans la norme, devrait adopter afin de se conformer aux différents titres se trouvant au sommet du classement. (Espeland & Sauder, 2007)

De fait, tout codage est un désalignement dont la capacité est limitée et ne permet pas de retranscrire la complexité individuelle et marginalise les utilisateurs dont les préférences musicales ne sont pas reflétées par les différents classements de *Spotify*. Suivant la même logique, de manière diamétralement opposée, ces classements créés une nouvelle catégorie d’écouteurs, celles de ceux qui s’y identifient bel et bien et écoutent les chansons les plus écoutées figurant dans les classements tendances. Ces derniers entretiennent ainsi le nouveau paradigme des comportements des auditeurs qui influencent les statistiques des classements et qui à leur tour impactent les habitudes musicales des auditeurs. Ces utilisateurs sont quant à eux, également paradoxalement stigmatisés par leur manque de diversité et d’originalité ne transparaissant pas dans leurs choix musicaux. (Thévenot, 1992)
D’autres problèmes de catégorisation surviennent quant à la classification des artistes dans tel ou tel genre musical. De fait, si certains interprètes correspondent relativement aux différentes catégories musicales établies, la diversité du style musical de certains ne permet pas d’effectuer une catégorisation reflétant la variété des genres musicaux, parfois multiples au sein d’une même chanson. Les limites de la catégorisation ne s’arrêtant pas au simple genre musical, l’identité même des artistes, de leurs sexes à leurs origines en passant par leur ancienneté, et restreinte dans des catégories qui ne reflètent pas non seulement leur pluralité artistique, mais également les discrimine en réduisant leur talent et popularité à leur identité quel qu’elle soit. 

## **Conclusion**

## **Bibliographie**

- Chrystal, K. A. & Mizen, P. D., 2001. *Goodhart's Law: Its Origins, Meaning and Implications for Monetary Policy* . s.l.:s.n.
- Desrosières, A., 2013. *Pour une sociologie historique de la quantification. L’argument statistique I*. Paris: Presses des Mines.
- Espeland, W. & Sauder, M., 2007. Rankings and Reactivity: How Public Measures Recreate Social Worlds. *American Journal of Sociology*, CXIII(1).
- Marwick, A. E., 2013. *Status update : celebrity, publicity, and branding in the social media age*. New Haven: Yale University Press.
- Pariser, E., 2011. *The filter bubble*. London: Penguin Books.
- Supiot, A., 2015. *La gouvernance par les nombres, Cours au Collège de France (2012-2014)*. Paris: Coll. « Poids et Mesures du Monde », Fayard.
- Thévenot, L., 1992. *Des chiffres parlants: Mesure statistique et jugement ordinaire*. Paris: La cité des chiffres.
