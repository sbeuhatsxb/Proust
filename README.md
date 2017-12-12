*Longtemps, je me suis couché de bonne heure. Souvent, à peine l’ordinateur éteint, mes yeux se fermaient si vite que je n’avais pas le temps de me dire : « J’ai bien codé. »*

...

Cette pastiche que l’on prête à Marcel Sbeuh, est inspirée de l’œuvre majeure de Proust : « A la recherche du temps perdu » dont l’auteur est réputé pour pondre des phrases interminables.

Cette semaine m’est venue l’idée de vous faire faire quelques menues révisions sur un certain nombre de fonctions déjà largement abordées ces trois derniers mois, lorsque nous nous rendions, tous les jours, d’un pas guilleret et le cœur léger, vers ce lieu improbable qui jouxte la fameuse rue du Corps de Garde, non loin de la Kibitzenau et du Neuhof – à vrai dire juste entre les deux – et qui héberge en son sein les pâles bâtiments de l’AFPA lentement usés par les foules innombrables d’imbéciles déprimés à la recherche d’un emploi déjà perdu dans les limbes de l’administration kafkaïenne en charge des chômeurs de moyenne ou longue durée, locaux tristement réputés pour accueillir en leur enclave la célébrissime Wild Code School qui offre la perspective d’un avenir meilleur en permettant à ses élèves de recourir à un usage presque banal d’un langage pourtant déjà mort ; comme sont morts aujourd’hui le latin ou le grec, car cette langue – le PHP – n’a rien d’une langue dans la mesure où sa pratique s’effectue à travers l’usage d’un clavier anodin ; à ce titre peut-être devrions-nous oser ici un néologisme plus adéquat : à la place d’un « langage de programmation » je propose l’usage d’un « clavage de programmation », car nous ne saurions jamais être assez précis, ni même assez verbeux pour décrire avec une précision balzacienne le moindre phénomène qui peut nous être donné à la vue ou à l’esprit.

Cette dernière phrase totalement inutile possède 241 mots. Vous l’aurez remarqué. Une phrase moyenne en français accessible à tout un chacun pour sa compréhension immédiate devrait contenir entre 14 et 16 mots. Ce qui est bien peu.

Si vous avez de la suite dans les idées, vous aurez déjà deviné que dans le cadre de ce dojo, il vous sera demandé d’effectuer un certain nombre de calculs et de statistiques sur un texte bien épais contenu dans un seul fichier (vous avez de la chance) : l’intégralité de l’oeuvre « A la recherche du temps perdu » de Marcel Proust. Le fichier texte pèse 7 mégas. Sans déconner.

* A l’aide de PHP, en POO aidé par PHPUnit, vous devrez afficher :
  * **Le nombre total de phrases** du bouquin
  * Trouver la phrase contenant le plus de **mots** et l’afficher en entier d’une manière ou d’une autre.
  * Calculer le **nombre moyen de mots** par phrase afin de savoir si la réputation de Proust est méritée.
(bonus – calculer le nombre de mots par phrase en excluant les dialogues contenant seulement *« Ah [?] » « Eh [?] » « Oh [?] »* qui font diminuer drastiquement cette moyenne et qui ne peuvent être considérées comme des phrases à part entière.
  * Les fichiers test1.txt et test2.txt pourront vous servir de support pendant vos tests. Le premier contient 8 mots et une phrase. Le deuxième contient 30 mots (8 + 22 mots) et 2 phrases. Si vos tests fonctionnent sur ces deux fichiers il n'y a pas de raison qu'ils ne marchent pas sur l'intégralité de l'oeuvre.


A l’antiquité, il pouvait être courant de voir des phrases « moyennes » de 40 mots... Pour l'anecdote, Proust a écrit l’incipit et le dernier paragraphe l’un juste après l’autre. Et de même en a-t-il fait pour chacun des chapitres du livre. Le premier chapitre correspond au dernier intitulé « Le temps retrouvé », le deuxième à l’avant dernier etc. Pour le support, il s’est servi de feuillets assez larges qu’il pouvait plier de manière à ce que le manuscrit forme déjà un livre. La Recherche du temps perdu est née de ce simple principe et évidemment du génie de Proust.


Les spécificités de la langue française étant les siennes, il est inutile de recourir à la fonction : __str_word_count()__ de PHP dans la mesure où elle est prévue pour la langue anglaise. Je sais, c’est dommage. Le __REGEX__ vous sera bien plus utile. 

Afin de vous aiguiller correctement il faudra réfléchir au préalable à ce qui détermine le fait qu'une phrase soit une phrase et de quels signes de ponctuation peut-elle être composée ?


Bon chance !
