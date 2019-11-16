
![Latest Release](https://img.shields.io/github/v/release/gwendolynefreddy/lcc-readme?include_prereleases&color=gold)<a name="top" id="top">
![Latest Release](https://img.shields.io/static/v1?label=version&message=v4.0.0&color=gold)
![Platform](https://img.shields.io/static/v1?label=plateforme&message=windows&color=informational)
![Language](https://img.shields.io/static/v1?label=langues&message=Anglais%20%7C%20Français%20&color=limegreen)

<div align="center"><h1>MYMOD</h1>

<h3>Un mod développé sur <a href="https://www.baldursgateworld.fr">La Couronne de Cuivre</a> pour Baldur's Gate II: ToB, BGT, BG2:EE et EET<h3>

</div><br />


**Auteur(e) :** <a href="https://www.baldursgateworld.fr/lacouronne/Auteur.html">bibi</a>  
**Langues :** français, <a href="README_EN.md">anglais</a>  
**Forum du mod :** <a href="https://www.baldursgateworld.fr/lacouronne/mymod/">Mymod</a><br /><br />


<div align="center">
<a href="#intro">Présentation</a> &#8226; <a href="#compat">Compatibilité</a> &#8226; <a href="#installation">Installation</a> &#8226; <a href="#components">Composants</a> &#8226; <a href="#componentslist">Composants (présentation alternative</a> &#8226; <a href="#images">Captures d'écran</a> &#8226; <a href="#credits">Crédits et remerciements</a> &#8226; <a href="#versions">Historique des versions</a></br>
</div>

<hr>


## <a name="intro" id="intro"></a>Présentation

Courte description du mod : Ce mod...... ou L'objet de ce mod......

Il s'agit d'un modèle de fichier readme pour GitHub destiné aux mods développés et/ou publiés sur la Couronne de Cuivre. Il est écrit en langage Markdown. Bien qu'il soit assez proche du langage HTML, certains formatages ne sont pas pris en compte par GitHub, comme l'affichage des couleurs.

Pour chaque section, j'ai repris, chaque fois que c'était possible, des éléments de traductions déjà publiées (par les d'Oghms ou par bibi) afin de conserver un semblant d'homogénéité dans les termes employés. Il suffit alors de conserver celles dont on a besoin (liste des jeux compatibles, procédures d'installation selon la plateforme, liste des outils utilisés...) et, pour le reste, de remplacer MYMOD et Auteur par le nom du mod et de son auteur, de modifier les liens et de remplir les textes adéquats. Pour certaines sections, j'ai été le plus exhaustif possible : il vous suffit de choisir les paragraphes qui vous intéressent et de supprimer les autres. &#128521;


Malheureusement, le rendu d'un fichier .md n'est véritablement effectif que dans GitHuB, ce qui ne vous permet pas de visualiser votre mise en page dans Notepad++. Il existe cependant plusieurs utilitaires vous permettant de les éditer et de visualiser partiellement vos modifications. Partiellement parce que certaines balises comme [br (break line)] apparaissent à l'écran MÊME si elles resteront invisibles dans GitHub. Personnellement, j'ai opté pour <a href=https://typora.io/">Typora</a>, mais il en existe d'autres.<br>

<details><summary>CLIQUER</summary>
<p>

#### hé hé, un bloc spoiler !

Deux listes de codes de smileys et d'emoji utilisables par markdown :
- <a href="https://gist.github.com/rxaviers/7360908">Complete list of github markdown emoji markup</a>.
- <a href="https://github.com/StylishThemes/GitHub-Dark/wiki/Emoji">GitHub-Dark Emoji (All GitHub Emoji)</a>.

<ins>Voici comment souligner un texte</ins>

</p><br>
</details>
<div align="right"><a href="#top">Retour en haut de page</a></div>


<hr>


## <a name="compat" id="compat"></a>Compatibilité

Ce mod est conçu pour fonctionner sur les jeux Infinity Engine suivants : Baldur's Gate: Enhanced Edition (BGEE), Baldur's Gate II: Enhanced Edition (BG2EE), Icewind Dale: Enhanced Edition (IWDEE), Planescape: Torment: Enhanced Edition (PsTEE), ainsi que l'extension de BGEE, Siege of Dragonspear (SoD) ; le jeu original Baldur's Gate (BG), avec ou sans son extension La légende de l'île perdue (Tales of the Sword Coast : TotSC), le jeu original Baldur's Gate II (Les Ombres d'Amn : BG2-SoA), avec ou sans son extension Trône de Bhaal (Throne of Bhaal : ToB) ; les mods de conversion Baldur's Gate Trilogy (BGT), Baldur's Gate Tutu (Tutu), Icewind Dale-in-Baldur's Gate II (IWD-in-BG2), et Enhanced Edition Trilogy (EET) ; le jeu original Icewind Dale (IWD), avec ou sans ses extensions Heart of Winter (HoW) et Trials of the Luremaster (TotLM), Icewind Dale II (IWD2), le jeu original Planescape: Torment (PsT).


MYMOD est un mod <acronym title="Weimer Dialogue Utility">WeiDU</acronym> et devrait par conséquent être compatible avec n'importe quel mod WeiDU. [facultatif : Il a été testé sur plusieurs installations et a fonctionné parfaitement jusqu'à présent.] Je ne peux cependant pas tous les tester. [Choisir une formule parmi les suivantes :] Si vous faites face à des bugs, veuillez contactez <a href="https://www.baldursgateworld.fr/lacouronne/Auteur.html">AUTEUR</a> ou bien poster dans les forums. Si vous faites face à des bugs, veuillez les signaler dans le forum, s'il vous plaît.

Bien que je m'efforce de rendre MYMOD compatible avec le plus grand nombre possible de mods, des incompatibilités risquent toujours de se produire. Voici la liste de celles recensées jusqu'à présent :
- mod 1
- mod 2
- ...


#### Mods pré-requis

[Choisir une formule parmi les suivantes : ]Bien qu'il ne soit pas requis pour faire correctement tourner MYMOD, il est toujours utile d'avoir installé la dernière version du <a href="http://www.gibberlings3.net/bg2fixpack/">BG2 Fixpack</a>. Je vous recommande fortement d'installer la dernière version du <a href="http://www.gibberlings3.net/bg2fixpack/">BG2 Fixpack</a> avant d'installer ce mod.<br>
<div align="right"><a href="#top">Retour en haut de page</a></div>


<hr>


## <a name="installation" id="installation"></a>Installation

#### Mise en garde

*Si une ancienne version de ce mod est déjà installée, il est nécessaire de la désinstaller d'abord. Pour cela, lancez **`setup-mymod.exe`**, et désinstallez tous les composants précédemment installés. Une fois la désinstallation achevée, supprimez le :file_folder: répertoire **mymod** et le fichier **setup-mymod.exe** (version Windows) avant d'extraire la nouvelle version du mod.*

*Lorsque vous installez ou désinstallez, **ne fermez pas la fenêtre DOS** en cliquant sur le bouton **X** ! Au lieu de cela, appuyez sur la touche **Entrée** lorsque l'invite de commandes vous le demande.*

*Par précaution, **désactivez les antivirus** ou tout logiciel résidant en mémoire avant d'installer ce mod, ou tout autre mod. Certains (en particulier avast et Norton !) ont une fâcheuse tendance à déclarer les exécutables des mods comme des faux positifs, provoquant ainsi l'échec de la procédure d'installation.*

## 

#### Note spéciale pour Siege of Dragonspear fourni par Steam/GOG

Good Old Games (GOG) et Steam fournissent le contenu de Siege of Dragonspear dans un format que WeiDU, l'outil utilisé pour installer ce mod, ne peut pas reconnaitre. Vous devez donc lancer le programme <a href="https://forums.beamdog.com/discussion/50441/modmerge-merge-your-steam-gog-zip-based-dlc-into-something-weidu-nearinfinity-dltcep-can-use/p1">Modmerge</a> dans votre répertoire de SoD avant d'installer ce mod, ou tout autre mod utilisant WeiDU.</br>

## 

#### Note pour les jeux en Édition Améliorée (EE)

Les Éditions améliorées sont des jeux que le développeur fait encore évoluer, notamment par l'ajout de capacités supplémentaires destinées à la création de mods et par l'ajout de contenus. N'oubliez pas que chaque patch de mise à jour effacera les mods que vous avez installés ! Ce mod ne fera pas exception à la règle.

Si vous pouvez retarder la mise à jour du patch en plein milieu d'un partie moddée (si vous en avez la possibilité, notamment chez Beamdog et Good Old Games), n'oubliez pas que même après avoir réinstallé les mods sur un nouveau patch, vous ne pourrez peut-être pas continuer le jeu avec vos anciennes sauvegardes, en particulier à cause de noms de personnages, de lieux, etc, qui pourraient être incorrects. Pour y remédier, copiez tout le dossier du jeu dans un nouveau dossier dans lequel vous installerez vos mods, et qui ne sera pas modifié par les patches de mise à jour. Il est important que vous installiez le mod dans la version linguistique dans laquelle vous jouez. Sinon, les dialogues du mod ne s'afficheront pas et provoqueront des messages d'erreur.</br>

## 

#### &#9888;&#65039; Avertissement : procédure d'installation

###### Les variables nécessaires à l'installation sont lues dans le fichier *<a href="https://raw.githubusercontent.com/Auteur/mymod/master/mymod/mymod.ini">mymod.ini</a>*, ou dans le fichier *<a href="https://raw.githubusercontent.com/Auteur/mymod/master/mymod/mymod-user.ini">mymod-user.ini</a>*, si ce dernier existe.

Pour éviter d'interrompre la procédure d'installation par de nombreux messages vous permettant de personnaliser certains composants à votre convenance, ces options ont été externalisées dans le fichier <a href="https://raw.githubusercontent.com/Auteur/mymod/master/mymod/mymod.ini">mymod.ini</a> situé dans le répertoire :file_folder: **mymod**. Ce fichier définit une installation « *standard* ».

Si vous souhaitez choisir d'autres options d'installation, il vous suffit de modifier, avec Notepad ou un autre éditeur de texte, les options de configuration de la section **<em>[Mod_content]</em>** dans le fichier *__mymod.ini__*, puis de sauvegarder ce dernier sous le nom *__mymod-user.ini__*.

Chaque ligne de ce fichier comprend une option de configuration, suivie de « = », puis d'un chiffre ou d'une chaîne de caractères. Tout ce que vous avez à faire, c'est modifier la valeur du chiffre ou de la chaîne.

Le programme d'installation lira les valeurs des variables dans les deux fichiers ini et donnera la priorité aux vôtres. Si le fichier mymod-user.ini contient une variable non conforme, ou si une variable est manquante, il la remplacera par sa valeur par défaut (celle correspondant à l'installation « *standard* »).</br>

Voici le tableau des options concernées (ne modifiez pas les variables non listées ; elle font partie de l'architecture de debugging et de test) :<br>

| Option | Signification de l'option d'installation | Type | Valeurs | Défaut |
| :---: | --- | :---: | :---: | :---: |
| mymod_variable1 | blabla<br>1 = description de la première valeur (recommandée).<br>2 = description de la seconde valeur.<br> | numérique | 1 ou 2 | <strong>1<strong> |
| mymod_variable2 | blabla<br>1 = description de la première valeur (recommandée).<br>2 = description de la deuxième valeur.<br>3 = description de la troisième valeur.<br> | numérique | 1, 2 ou 3 | <strong>1<strong> |
| mymod_variable3 | blabla<br> | alphanumérique | une lettre | <strong>A<strong> |
| mymod_variable4 | blabla<br> | alphanumérique | un nom! | <strong>Hello<strong> |

## 

#### Windows

MYMOD pour Windows est livré et installé avec WeiDU, et est diffusé sous forme d'archive.

Vous devez extraire les fichiers de l'archive dans votre répertoire de jeu (*le dossier qui contient le fichier CHITIN.KEY*) à l'aide de <a href="http://www.7-zip.org/download.html">7zip</a> ou de <a href="http://www.rarlab.com/download.htm">WinRAR</a>. Une fois l'archive extraite correctement, vous devriez trouver le répertoire :file_folder: mymod et le fichier setup-mymod.exe dans votre répertoire de jeu. Pour installer le mod, il suffit de double-cliquer sur **`setup-mymod.exe`** et de suivre les instructions affichées à l'écran.

Vous pouvez lancer **`setup-mymod.exe`** dans votre répertoire de jeu pour réinstaller, désinstaller, ou encore changer des composants.

[**(Pour une version exe, remplacez les 2 deux premières lignes par les suivantes)** MYMOD pour Windows est livré et installé avec <acronym title="Weimer Dialogue Utility">WeiDU</acronym>, et est diffusé sous forme d'archive auto-extractible. Pour l'installer, il suffit de double-cliquer sur l'archive et de suivre les instructions affichées à l'écran.

Autrement, vous pouvez extraire les fichiers de l'archive dans votre répertoire de jeu (*le dossier qui contient le fichier CHITIN.KEY*) à l'aide de <a href="http://www.7-zip.org/download.html">7zip</a> ou de <a href="http://www.rarlab.com/download.htm">WinRAR</a>. Une fois l'archive extraite correctement, vous devriez trouver le répertoire **mymod** et le fichier **setup-mymod.exe** dans votre répertoire de jeu. Pour installer le mod, il suffit de double-cliquer sur **setup-mymod.exe** et de suivre les instructions affichées à l'écran.]

## 

#### Mac OS X

MYMOD pour Mac OS X est livré et installé avec WeiDU, et est diffusé sous forme d'archive compressée (tarball).

Extrayez le contenu du tarball dans votre répertoire de jeu. Après une extraction réussie, ce dernier contiendra les fichiers setup-mymod, setup-mymod.command, et le répertoire :file_folder: mymod. Pour installer, il suffit de double-cliquer sur **`setup-mymod.command`** et de suivre les instructions affichées à l'écran.

Vous pouvez lancer **`setup-mymod.command`** dans votre répertoire de jeu pour réinstaller, désinstaller ou changer des composants.

## 

#### Linux

MYMOD pour Linux est diffusé sous forme d'archive compressée (tarball) sans l'installateur WeiDU.

Extrayez le contenu du mod dans le répertoire du jeu que vous voulez moder.

Téléchargez la version la plus récente de WeiDU pour Linux sur <a href="https://github.com/WeiDUorg/weidu/releases">WeiDU.org</a> et copiez WeiDU et WeInstall dans /usr/bin. Ouvrez ensuite un terminal et allez (**cd**) dans le répertoire d'installation de votre jeu, lancez « tolower » et répondez « Y » aux deux questions. Vous pouvez éviter d'exécuter la seconde option (Linux.ini) si vous l'avez déjà lancée une fois dans le même dossier. Pour gagner du temps, l'archive est déjà passée en minuscules, aussi il n'est pas non plus nécessaire d'exécuter la première option (passer les noms de fichiers en minuscules) si vous n'avez extrait que ce mod depuis la dernière fois que vous avez passé les noms de fichiers en minuscules. Si vous avez un doute, il vaut mieux exécuter tolower et accepter les deux options.

Lancez **`WeInstall setup-mymod`** depuis le dossier de votre jeu pour installer le mod. Puis, lancez **`wine BGMain.exe`** et commencez à jouer.

## 

#### Note pour effectuer une désinstallation complète

En plus des méthodes détaillées plus haut pour supprimer des composants, il est possible de désinstaller complètement le mod en tapant **`setup-mymod --uninstall`** dans une ligne de commandes, ce qui supprimera tous les composants sans devoir ingurgiter tous les messages.</br>
<div align="right"><a href="#top">Retour en haut de page</a></div>


<hr>


## <a name="components" id="components"></a>Composants

Le programme d'installation comprend les composants suivants. Chacun possède un numéro distinct et pré-défini qui lui attribue une position déterminée (mot-clé *DESIGNATED* en langage WeiDU) ; ce qui permet aux autres composants de le détecter et aux utilitaires d'installation automatiques de préciser quels composants installer.<br /><br />


#### 10. Composant 10 (composant principal)

Description du composant principal.</br>

## 

#### 20 Composant 20 : blabbla

Description du composant 20.</br>

## 

#### 30 Composant 30 : blabbla

Exemple de composant présentant des tableaux.

<table style="margin-left: 80px" summary="Rebalanced Tazok and Dig-Dag">
	<tr>
		<th>Créature</th>
		<th>Kit</th>
		<th>Niveau <span style="font-weight: normal">&#160;&#160;&#160;(ex)</span></th>
		<th>XP <span style="font-weight: normal">&#160;&#160;&#160;(ex)</span></th>
		<th>PV <span style="font-weight: normal">&#160;&#160;&#160;(ex)</span></th>
		<th>Force <span style="font-weight: normal">&#160;&#160;&#160;(ex)</span></th>
		<th>Constitution <span style="font-weight: normal">&#160;&#160;&#160;(ex)</span></th>
		<th>Compétence martiale</th>
	</tr>
	<tr>
		<td>Tazok</td>
		<td>--</td>
		<td>**19**&#160;&#160;&#160;(18)</td>
		<td>**12000**&#160;&#160;&#160;(6000)</td>
		<td>**154**&#160;&#160;&#160;(136)</td>
		<td>--</td>
		<td>--</td>
		<td>TWO-HANDED SWORD +++++</td>
	</tr>
	<tr>
		<td>FIRorc01 (DigDag)</td>
		<td>Berserker</td>
		<td>**13**&#160;&#160;&#160;(12)</td>
		<td>**7000**&#160;&#160;&#160;2000)</td>
		<td>**107**&#160;&#160;&#160;(99)</td>
		<td>**22**&#160;&#160;&#160;(17)</td>
		<td>**22**&#160;&#160;&#160;(9)</td>
		<td>BASTARD SWORD +++++</td>
	</tr>
</table><br>
<div align="right"><a href="#top">Retour en haut de page</a></div>


<hr>


## <a name="componentslist" id="componentslist"></a>Composants (présentation alternative si vous avez beaucoup de composants)


Le programme d'installation comprend les composants suivants. Chacun possède un numéro distinct et pré-défini qui lui attribue une position déterminée (mot-clé *DESIGNATED* en langage WeiDU) ; ce qui permet aux autres composants de le détecter et aux utilitaires d'installation automatiques de préciser quels composants installer.<br /><br />

><span style="margin-left: 50px;"><a href="#10">[10] Composant 10 (composant principal)</a></span></br>
><span style="margin-left: 50px;"><a href="#20">[20] Composant 20</a></span></br>
><span style="margin-left: 50px;"><a href="#50">[30] Composant 30</a></span></br>
><span style="margin-left: 50px;"><a href="#40">[40] ...</a></span></br>


## 

<a name="10" id="10"></a>**10. Composant 10 (composant principal)**<br />

Description du composant principal.</br>
<div align="right"><a href="#componentslist">Back to components list</a></div>

## 

<a name="10" id="20"></a>**20 Composant 20**<br />

Description du composant 20.</br>
<div align="right"><a href="#componentslist">Back to components list</a></div>

## 

<a name="30" id="10"></a>**30 Composant 30**<br />

Description du composant 30.</br>
<div align="right"><a href="#componentslist">Back to components list</a></div>


<hr>


## <a name="images" id="images"></a>Captures d'écran

<img src="images/baldr000.jpg">
<img src="images/baldr001.jpg"></br>
<div align="right"><a href="#top">Retour en haut de page</a></div>


<hr>


## <a name="credits" id="credits"></a>Crédits et remerciements

#### Auteur(e) : <a href="https://www.baldursgateworld.fr/lacouronne/members/auteur.html">Auteur</a>


#### Remerciements particuliers à :

- L'équipe de <a href="https://www.baldursgateworld.fr">La Couronne de Cuivre</a> pour l'hébergement de ce mod.
- Les créateurs de la série Baldur's Gate : <a href="http://www.bioware.com/">Bioware</a> et <a href="http://www.obsidian.net/">Black Isle Studios</a>.
- machin pour m'avoir donner la permission d'utiliser blabla.
- dugland pour m'avoir aidé à coder.
- trucmuche pour son aide dans le codage et ses suggestions.
- bidule pour son aide dans la rédaction des dialogues.
- xxx pour la traduction française.
- yyy pour la relecture.
- Merci aux artistes de portraits du site <a href="https://www.pinterest.fr/">Pinterest</a>.
- Merci à toutes les personnes des forums de <a href="https://www.baldursgateworld.fr">La Couronne de Cuivre</a>, <a href="http://gibberlings3.net/forums/">The Gibberlings Three</a>, <a href="http://www.shsforums.net/">Spellhold Studios</a>, et des autres communautés de joueurs et de moddeurs IE qui m'ont offert leur aide.
- etc.

## 

#### Logiciels et outils utilisés pour la réalisation de ce mod :

- <a href="https://github.com/WeiDUorg/weidu/releases"><acronym title="Weimer Dialogue Utility">WeiDU</acronym></a> de Wes Weimer, the bigg et Wisp.
- <a href="https://github.com/Argent77/NearInfinity/releases">Near Infinity</a> de Jon Olav Hauglid, FredSRichardson et Argent77.
- <a href="http://www.shsforums.net/topic/31285-infinity-explorer-v085/">Infinity Explorer</a> de Dmitry Jemerov / bigmoshi.
- <a href="http://www.gibberlings3.net/tools/dltcep.php"><acronym title="Dragonlance Total Conversion Editor Pro">DLTCEP</acronym></a> de Avenger.
- <a href="http://www.baldursgatemods.com/forums/index.php?action=downloads;sa=view;down=85">CreMaker_v3.1.9</a>.
- <a href="https://gibberlings3.github.io/iesdp/"><acronym title="Infinity Engine Structures Description Project">IESDP</acronym></a> maintenu par igi et lynx.
- <a href="http://www.gibberlings3.net/debug/">G3 Debugging Suite</a> de CamDawg.
- <a href="http://www.teambg.eu/?page=tools&amp;cat=32">BAM Workshop</a> de Glenn Flansburg.
- <a href="http://www.shsforums.net/topic/57564-bamworkshop/">BAMWorkshop 2</a> de Andrew Bridges.
- <a href="http://www.shsforums.net/index.php?showtopic=42359">BAM Batcher</a> de Miloch.
- <a href="https://www.adobe.com/products/photoshop.html">Adobe Photoshop</a>
- <a href="http://www.gimp.org/"><acronym title="GNU Image Manipulation Program">GIMP</acronym></a> par l'équipe de the GIMP.
- <a href="http://www.gamani.com/">GIF Movie Gear</a>
- <a href="https://www.blender.org/">Blender</a> par la Fondation Blender.
- <a href="https://www.autodesk.com/products/3ds-max/overview">3ds Max</a>
- <a href="http://notepad-plus-plus.org/">Notepad++</a> par l'équipe de Notepad++, Don Ho, et le plug-in de correction orthographique.
- <a href="http://www.shsforums.net/files/file/1048-weidu-highlighter-for-notepad/">WeiDU Notepad++ Highlighters </a> de Argent77.
- <a href="http://www.context.cx/">ConTEXT Text Editor</a> de Eden Kirin.
- <a href="http://www.gibberlings3.net/tools/weidu.php">WeiDU ConTEXT Highlighters </a> de Idobek, mis à jour par cmorgan.
- <a href="http://www.editpadpro.com/editpadclassic.html">EditPad Classic</a> de Jan Goyvaerts.
- <a href="http://www.pspad.com/en/">PSPad</a> de Jan Fiala.
- <a href="http://www.bulkrenameutility.co.uk/">Bulk Rename Utility</a> de TGRMN Software.

## 

#### Information sur les droits d'auteur

Libre à vous de choisir la formule et la présentation qui vous conviennent :

###### MYMOD n'est pas développé, supporté ni approuvé par BioWare&trade; ou Interplay/Black Isle, Overhaul, Beamdog ou Wizards of the Coast. Il a été développé par AUTEUR, et est basé sur le jeu Baldur's Gate II et son extension.
###### Tout le contenu du mod appartient à &copy;AUTEUR.
###### Baldur's Gate II : Les Ombres d'Amn et Baldur's Gate II : Trône de Bhaal appartiennent à &copy; TSR, Inc. Le moteur Infinity Engine appartient à &copy; BioWare Corp. Toutes les autres marques et droits d'auteur appartiennent à leurs propriétaires respectifs.

###### Ce mod a été créé pour être librement apprécié par tous les joueurs de Baldur's Gate II. Cependant, il ne doit pas être vendu, publié, compilé ou redistribué sous une forme quelconque sans le consentement de son auteur.
###### Veuillez noter que tout partage ou hébergement de ce mod est interdit sans la permission de l'auteur.

###### S'il existe des problèmes de droits d'auteur ou si cette déclaration nécessite une révision, veuillez me contacter et conseillez-moi sur ce qu'il faut faire à ce sujet. Plus particulièrement, si vous trouvez dans ce mod des illustrations susceptibles d'être en conflit avec les règles de droit d'auteur, merci de bien vouloir me le faire savoir dès que possible et je supprimerai immédiatement le contenu en conflit.

###### La communauté de modding sur le moteur Infinity Engine a été très active depuis plus de quinze ans maintenant, et a produit des milliers d'heures de travail non rémunérées effectuées par des fans du jeu. Les moddeurs s'efforcent de publier le meilleur de leur travail, et les joueurs bénéficient des mods les plus performants et les mieux maintenus, à condition que nous travaillions tous dans le même sens.
###### Mais cette harmonie peut malheureusement être perturbée, principalement par deux comportements. Le premier, c'est de revendiquer le travail de quelqu'un d'autre. Le second consiste à héberger et à redistribuer un mod sans la permission de son(es) auteur(s).
###### Soyez assez sympa avec vos collègues joueurs et moddeurs. Ne le faites pas.</br></br>
<div align="right"><a href="#top">Retour en haut de page</a></div>


<hr>


## <a name="versions" id="versions"></a>Historique des versions

<p>Note du traducteur : l'historique n'est volontairement pas traduit afin de faciliter la mise à jour par l'auteur.</p>

#### Version 4.0.0 (16 novembre 2019)

- Modifications générales (fichiers .html et .md) :
  - Correction de typos.
  - Ajouts de lignes de séparations manquantes.
  - Section Installation :
	- Réécriture de la procédure.
	- Modification du nom des fichiers ini.
	- Ajout du traitement des chaînes de caractères dans les fichiers ini.
  - Section Composants :
	- Suppression de la référence au BiG World Setup, obsolète et plus maintenu.
	- Traduction en anglais du tableau.
	- Ajout d'une présentation alternative si le mod comprend au moins une dizaine de composants.
  - Section Crédits et remerciements :
    - Mise à jour des liens GitHub pour WeiDU et NearInfinity.

- readme-lcc.html
  - Reformatage (notamment introduction du code Dos).

- readme.md
  - Modifications générales :
	- Ajout de badges en en-tête.
	- Centrage du nom du mod en en-tête.
	- Utilisation des codes de formatage markdown.
	- Alignement à droite du retour en haut de page.
	- Ajout de liens vers deux listes de codes de smileys et d'emoji utilisables par markdown.
	- Ajout du "truc" pour souligner un texte.
  - Section Compatibilité :
	- Ajout des lignes manquantes en anglais.

## 

#### Version 3.0.0 (5 février 2019)

- Ajout de balises spoilers dans les fichiers html et md.
- Ajout d'un petit bonus dans la section Présentation du fichier html.
- Corrections mineures diverses.

## 

#### Version 2.0.0 (21 octobre 2018)

- Correction de liens erronés, de typos, et ajout de Blender dans les outils.
- Ajout de la proposition d'Isaya pour gérer les listes à plusieurs niveaux. Je l'ai modifiée pour ajouter un niveau supplémentaire de liste.
- Ajout de la procédure de lecture des fichiers ini qui sera utilisée par les prochains outils d'installation automatique.
- Ajout des fichiers .md pour les dépôts github.
- Ajout de plusieurs drapeaux étrangers.

## 

#### Version 1.1 (15 octobre 2018)

- Un drapeau permet de passer du readme français à l'anglais, et lycée de Versailles.

## 

#### Version beta 1.0 (13 octobre 2018)

- Sortie initiale.
<div align="right"><a href="#top">Retour en haut de page</a></div>
