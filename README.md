# MYMOD

<p><strong>Auteur :</strong> <a href="https://www.baldursgateworld.fr/lacouronne/Auteur.html">bibi</a><br />
<strong>Version :</strong> n.n.n<br />
<strong>Langues :</strong> français, <a href="README_EN.md">anglais</a><br />
<strong>Plateformes :</strong> Windows, Mac OS X et Linux</p>

<strong>Forum du mod :</strong> <a href="https://www.baldursgateworld.fr/lacouronne/mymod/">Menace sur le Royaume de Diamant Éternel</a>
</br></br>



## Présentation

<p>Courte description du mod : Ce mod...... ou L'objet de ce mod......</p>

<p>Il s'agit d'un modèle de fichier readme pour GitHub destiné aux mods développés et/ou publiés sur la Couronne de Cuivre. Il est écrit en langage Markdown. Bien qu'il soit assez proche du langage HTML, certains formatages ne sont pas pris en compte par GitHub, comme l'affichage des couleurs.</p>

<p>Pour chaque section, j'ai repris, chaque fois que c'était possible, des éléments de traductions déjà publiées (par les d'Oghms ou par bibi) afin de conserver un semblant d'homogénéité dans les termes employés. Il suffit alors de conserver celles dont on a besoin (liste des jeux compatibles, procédures d'installation selon la plateforme, liste des outils utilisés...) et, pour le reste, de remplacer MYMOD et Auteur par le nom du mod et de son auteur, de modifier les liens et de remplir les textes adéquats. Pour certaines sections, j'ai été le plus exhaustif possible : il vous suffit de choisir les paragraphes qui vous intéressent et de supprimer les autres. &#128521;</p>


<p>Malheureusement, le rendu d'un fichier .md n'est véritablement effective que dans GitHuB, ce qui ne vous permet pas de visualiser votre mise en page dans Notepad++. Il existe cependant plusieurs utilitaires vous permettant de les éditer et de visualiser partiellement vos modifications. Parcellement parce que certaines balises comme [br (break line)] apparaissent à l'écran MÊME si elles resteront invisibles dans GitHub. Personnellement, j'ai opté pour <a href=https://typora.io/">Typora</a>, mais il en existe d'autres.</p><br>



## Compatibilité

Ce mod est conçu pour fonctionner sur les jeux Infinity Engine suivants : Baldur's Gate: Enhanced Edition (BGEE), Baldur's Gate II: Enhanced Edition (BG2EE), Icewind Dale: Enhanced Edition (IWDEE), Planescape: Torment: Enhanced Edition (PsTEE), ainsi que l'extension de BGEE, Siege of Dragonspear (SoD) ; le jeu original Baldur's Gate (BG), avec ou sans son extension La légende de l'île perdue (Tales of the Sword Coast : TotSC), le jeu original Baldur's Gate II (Les Ombres d'Amn : BG2-SoA), avec ou sans son extension Trône de Bhaal (Throne of Bhaal : ToB) ; les mods de conversion Baldur's Gate Trilogy (BGT), Baldur's Gate Tutu (Tutu), Icewind Dale-in-Baldur's Gate II (IWD-in-BG2), et Enhanced Edition Trilogy (EET) ; le jeu original Icewind Dale (IWD), avec ou sans ses extensions Heart of Winter (HoW) et Trials of the Luremaster (TotLM), Icewind Dale II (IWD2), le jeu original Planescape: Torment (PsT).


MYMOD est un mod <acronym title="Weimer Dialogue Utility">WeiDU</acronym> et devrait par conséquent être compatible avec n'importe quel mod WeiDU. [facultatif : Il a été testé sur plusieurs installations et a fonctionné parfaitement jusqu'à présent.] Je ne peux cependant pas tous les tester. [Choisir une formule parmi les suivantes :] Si vous faites face à des bugs, veuillez contactez <a href="https://www.baldursgateworld.fr/lacouronne/Auteur.html">AUTEUR</a> ou bien poster dans les forums. Si vous faites face à des bugs, veuillez les signaler dans le forum, s'il vous plaît.

<p>Bien que je m'efforce de rendre MYMOD compatible avec le plus grand nombre possible de mods, des incompatibilités risquent toujours de se produire. Voici la liste de celles recensées jusqu'à présent :</p>
- mod 1
- mod 2
- ...


#### Mods pré-requis

<p>[Choisir une formule parmi les suivantes : ]Bien qu'il ne soit pas requis pour faire correctement tourner MYMOD, il est toujours utile d'avoir installé la dernière version du <a href="http://www.gibberlings3.net/bg2fixpack/">BG2 Fixpack</a>. Je vous recommande fortement d'installer la dernière version du <a href="http://www.gibberlings3.net/bg2fixpack/">BG2 Fixpack</a> avant d'installer ce mod.</p><br>


## <a name="installation" id="installation"></a>Installation

#### Mise en garde

<em>Si une ancienne version de ce mod est déjà installée, il est nécessaire de la désinstaller d'abord. Pour cela, lancez <strong>setup-mymod.exe</strong>, et désinstallez tous les composants précédemment installés. Une fois la désinstallation achevée, supprimez le répertoire <strong>mymod</strong> et le fichier <strong>setup-mymod.exe</strong> (version Windows) avant d'extraire la nouvelle version du mod.</em>

<em>Lorsque vous installez ou désinstallez, <strong>ne fermez pas la fenêtre <acronym title="Disk Operating System">DOS</acronym></strong> en cliquant sur le bouton <strong>X</strong> ! Au lieu de cela, appuyez sur la touche <strong>Entrée</strong> lorsque l'invite de commandes vous le demande.</em>

<em>Par précaution, <strong>Désactivez les antivirus</strong> ou tout logiciel résidant en mémoire avant d'installer ce mod, ou tout autre mod. Certains (en particulier avast et Norton !) ont une fâcheuse tendance à déclarer les exécutables des mods comme des faux positifs, provoquant ainsi l'échec de la procédure d'installation.</em></br>


#### Note spéciale pour Siege of Dragonspear fourni par Steam/GOG

Good Old Games (GOG) et Steam fournissent le contenu de Siege of Dragonspear dans un format que <acronym title="Weimer Dialogue Utility">WeiDU</acronym>, l'outil utilisé pour installer ce mod, ne peut pas reconnaitre. Vous devez donc lancer le programme <a href="https://forums.beamdog.com/discussion/50441/modmerge-merge-your-steam-gog-zip-based-dlc-into-something-weidu-nearinfinity-dltcep-can-use/p1">Modmerge</a> dans votre répertoire de SoD avant d'installer ce mod, ou tout autre mod utilisant WeiDU.</br>


#### Note pour les jeux en Édition Améliorée (EE)

Les Éditions améliorées sont des jeux que le développeur fait encore évoluer, notamment par l'ajout de capacités supplémentaires destinées à la création de mods et par l'ajout de contenus. N'oubliez pas que chaque patch de mise à jour effacera les mods que vous avez installés ! Ce mod ne fera pas exception à la règle.

Si vous pouvez retarder la mise à jour du patch en plein milieu d'un partie moddée (si vous en avez la possibilité, notamment chez Beamdog et Good Old Games), n'oubliez pas que même après avoir réinstallé les mods sur un nouveau patch, vous ne pourrez peut-être pas continuer le jeu avec vos anciennes sauvegardes, en particulier à cause de noms de personnages, de lieux, etc, qui pourraient être incorrects. Pour y remédier, copiez tout le dossier du jeu dans un nouveau dossier dans lequel vous installerez vos mods, et qui ne sera pas modifié par les patches de mise à jour. Il est important que vous installiez le mod dans la version linguistique dans laquelle vous jouez. Sinon, les dialogues du mod ne s'afficheront pas et provoqueront des messages d'erreur.</br>


#### :warning: Avertissement : procédure d'installation

###### Les variables nécessaires à l'installation sont lues dans le fichier <em><a ref="https://raw.githubusercontent.com/Auteur/mymod/master/mymod/mymod-config-default.ini">mymod-config-default.ini</a></em>, ou dans le fichier <em><a ref="https://raw.githubusercontent.com/Auteur/mymod/master/mymod/mymod-config.ini">mymod-config.ini</a></em>, si ce dernier existe.

Pour éviter d'interrompre la procédure d'installation par de nombreux messages vous permettant de personnaliser certains composants à votre convenance, ces choix de variables ont été externalisés dans le fichier <a href="">mymod-config-default.ini</a> situé dans le répertoire <strong>mymod</strong>. Ce fichier définit une installation « <em>standard</em> ».

Si vous souhaitez choisir d'autres options d'installation, il vous suffit de modifier les variables souhaitées dans le fichier <em>mymod-config-default.ini</em>, puis de sauvegarder ce dernier sous le nom <em>mymod-config.ini</em>.

Le programme d'installation lira les valeurs des variables dans les deux fichiers ini et donnera la priorité aux vôtres. Si le fichier mymod-config.ini contient une variable non conforme, ou si une variable est manquante, il la remplacera par sa valeur par défaut (celle correspondant à l'installation « <em>standard</em> »).</br>


#### Windows

Menace sur le Royaume de Diamant Éternel for Windows is distributed as an extractable compressed archive and includes a <acronym title="Weimer Dialogue Utility">WeiDU</acronym> installer.

Vous devez extraire les fichiers de l'archive dans votre répertoire de jeu (<em>le dossier qui contient le fichier CHITIN.KEY</em>) à l'aide de <a href="http://www.7-zip.org/download.html">7zip</a> ou de <a href="http://www.rarlab.com/download.htm">WinRAR</a>. Une fois l'archive extraite correctement, vous devriez trouver le répertoire <strong>mymod</strong> et le fichier <strong>setup-mymod.exe</strong> dans votre répertoire de jeu. Pour installer le mod, il suffit de double-cliquer sur <strong>setup-mymod.exe</strong> et de suivre les instructions affichées à l'écran.</br>

Vous pouvez lancer <strong>setup-mymod.exe</strong> dans votre répertoire de jeu pour réinstaller, désinstaller, ou encore changer des composants.

[<strong>(Pour une version exe, remplacez les 2 deux premières lignes par les suivantes)</strong> MYMOD pour Windows est livré et installé avec <acronym title="Weimer Dialogue Utility">WeiDU</acronym>, et est diffusé sous forme d'archive auto-extractible. Pour l'installer, il suffit de double-cliquer sur l'archive et de suivre les instructions affichées à l'écran.

Autrement, vous pouvez extraire les fichiers de l'archive dans votre répertoire de jeu (<em>le dossier qui contient le fichier CHITIN.KEY</em>) à l'aide de <a href="http://www.7-zip.org/download.html">7zip</a> ou de <a href="http://www.rarlab.com/download.htm">WinRAR</a>. Une fois l'archive extraite correctement, vous devriez trouver le répertoire <strong>mymod</strong> et le fichier <strong>setup-mymod.exe</strong> dans votre répertoire de jeu. Pour installer le mod, il suffit de double-cliquer sur <strong>setup-mymod.exe</strong> et de suivre les instructions affichées à l'écran.]


#### Mac OS X

MYMOD pour Mac OS X est livré et installé avec <acronym title="Weimer Dialogue Utility">WeiDU</acronym>, et est diffusé sous forme d'archive compressée (tarball).</p>

Extrayez le contenu du tarball dans votre répertoire de jeu. Après une extraction réussie, ce dernier contiendra les fichiers <strong>setup-mymod</strong>, <strong>setup-mymod.command</strong>, et le répertoire <strong>mymod</strong>. Pour installer, il suffit de double-cliquer sur <strong>setup-mymod.command</strong> et de suivre les instructions affichées à l'écran.

Vous pouvez lancer <strong>setup-mymod.command</strong> dans votre répertoire de jeu pour réinstaller, désinstaller ou changer des composants.


#### Linux

MYMOD pour Linux est diffusé sous forme d'archive compressée (tarball) sans l'installateur <acronym title="Weimer Dialogue Utility">WeiDU</acronym>.

Extrayez le contenu du mod dans le répertoire du jeu que vous voulez moder.

Téléchargez la version la plus récente de WeiDU pour Linux sur <a href="http://www.weidu.org/%7Ethebigg/">WeiDU.org</a> et copiez WeiDU et WeInstall dans /usr/bin. Ouvrez ensuite un terminal et allez (<strong>cd</strong>) dans le répertoire d'installation de votre jeu, lancez « tolower » et répondez « Y » aux deux questions. Vous pouvez éviter d'exécuter la seconde option (Linux.ini) si vous l'avez déjà lancée une fois dans le même dossier. Pour gagner du temps, l'archive est déjà passée en minuscules, aussi il n'est pas non plus nécessaire d'exécuter la première option (passer les noms de fichiers en minuscules) si vous n'avez extrait que ce mod depuis la dernière fois que vous avez passé les noms de fichiers en minuscules. Si vous avez un doute, il vaut mieux exécuter tolower et accepter les deux options.

Lancez <strong>WeInstall setup-mymod</strong> depuis le dossier de votre jeu pour installer le mod. Puis, lancez <strong>wine BGMain.exe</strong> et commencez à jouer.


#### Note pour effectuer une désinstallation complète

En plus des méthodes détaillées plus haut pour supprimer des composants, il est possible de désinstaller complètement le mod en tapant <strong>setup-mymod --uninstall</strong> dans une ligne de commandes, ce qui supprimera tous les composants sans devoir ingurgiter tous les messages.</br></br>



## <a name="components" id="components"></a>Composants

Le programme d'installation comprend les composants suivants. Chacun possède un numéro distinct et pré-défini qui lui attribue une position déterminée (mot-clé <em>DESIGNATED</em> en langage WeiDU) ; ce qui permet aux autres composants de le détecter et aux utilitaires d'installation automatiques comme le BiG World Setup de préciser quels composants installer.


#### 10. 
</br></br>


## <a name="screenshots" id="screenshots"></a>Captures d'écran
</br></br>


## <a name="credits" id="credits"></a>Crédits et remerciements

#### Auteur : <a href="https://www.baldursgateworld.fr/lacouronne/members/freddy_gwendo.html">Freddy_Gwendo</a>

#### Remerciements particuliers à :

#### Logiciels et outils utilisés pour la réalisation de ce mod :

#### Information sur les droits d'auteur
</br></br>


## Historique des versions

#### Version beta 1.0.0 - jour mois 201x
- Sortie initiale.
