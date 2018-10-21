# MYMOD

<p><strong>Author:</strong> <a href="https://www.baldursgateworld.fr/lacouronne/Auteur.html">bibi</a><br />
<strong>Version:</strong> n.n.n<br />
<strong>Languages:</strong> <a href="README.md">French</a>, English<br />
<strong>Plaeforms:</strong> Windows, Mac OS X et Linux</p>

<strong>Forum du mod :</strong> <a href="https://www.baldursgateworld.fr/lacouronne/mymod/">Mymod</a>
</br></br>



## Overview

<p>Courte description du mod : Ce mod...... ou L'objet de ce mod......</p>

<p>Il s'agit d'un modèle de fichier readme pour GitHub destiné aux mods développés et/ou publiés sur la Couronne de Cuivre. Il est écrit en langage Markdown. Bien qu'il soit assez proche du langage HTML, certains formatages ne sont pas pris en compte par GitHub, comme l'affichage des couleurs.</p>

<p>Pour chaque section, j'ai repris, chaque fois que c'était possible, des éléments de traductions déjà publiées (par les d'Oghms ou par bibi) afin de conserver un semblant d'homogénéité dans les termes employés. Il suffit alors de conserver celles dont on a besoin (liste des jeux compatibles, procédures d'installation selon la plateforme, liste des outils utilisés...) et, pour le reste, de remplacer MYMOD et Auteur par le nom du mod et de son auteur, de modifier les liens et de remplir les textes adéquats. Pour certaines sections, j'ai été le plus exhaustif possible : il vous suffit de choisir les paragraphes qui vous intéressent et de supprimer les autres. &#128521;</p>


<p>Malheureusement, le rendu d'un fichier .md n'est véritablement effective que dans GitHuB, ce qui ne vous permet pas de visualiser votre mise en page dans Notepad++. Il existe cependant plusieurs utilitaires vous permettant de les éditer et de visualiser partiellement vos modifications. Parcellement parce que certaines balises comme [br (break line)] apparaissent à l'écran MÊME si elles resteront invisibles dans GitHub. Personnellement, j'ai opté pour <a href=https://typora.io/">Typora</a>, mais il en existe d'autres.</p><br>



## Compatibility

This mod is designed to work on all Infinity Engine games. This includes: Baldur's Gate: Enhanced Edition (BGEE), Baldur's Gate II: Enhanced Edition (BG2EE), Icewind Dale: Enhanced Edition (IWDEE), Planescape: Torment: Enhanced Edition (PsTEE), and the BGEE Siege of Dragonspear expansion (SoD) ; the original Baldur's Gate (BG), with or without the Tales of the Sword Coast (TotSC) expansion, the original Baldur's Gate II (BG2, or just SoA), with or without the Throne of Bhaal (ToB) expansion ; the conversion projects Baldur's Gate Trilogy (BGT), Baldur's Gate Tutu (Tutu), Icewind Dale-in-Baldur's Gate II (IWD-in-BG2), and Enhanced Edition Trilogy (EET) ; the original Icewind Dale (IWD) with or without either of its expansions, Heart of Winter (HoW) and Trials of the Luremaster (TotLM), Icewind Dale II (IWD2), the original Planescape: Torment (PsT).



## Installation

#### Notes

<em>If you've previously installed the mod, remove it before extracting the new version. To do this, run <strong>setup-mymod.exe</strong>, uninstall all previously installed components and delete the <strong>mymod</strong> folder.</em>

<em>When installing or uninstalling, <strong>do not close the <acronym title="Disk Operating System">DOS</acronym> window</strong> by clicking on the <strong>X</strong> button! Instead, press the <strong>Enter</strong> key whenever instructed to do so.</em>

<em><strong>Disable any antivirus</strong> or other memory-resident software before installing this or any other mod. Some (particularly avast and Norton!) have a tendency to report false positives with mod activity, resulting in failed installs.</em>


#### Special Note for Siege of Dragonspear from Steam/GOG

Good Old Games (GOG) and Steam both package the additional content for Siege of Dragonspear in a method that <acronym title="Weimer Dialogue Utility">WeiDU</acronym>, the tool used to install this mod, cannot access. You must run a program called <a href="https://forums.beamdog.com/discussion/50441/modmerge-merge-your-steam-gog-zip-based-dlc-into-something-weidu-nearinfinity-dltcep-can-use/p1">Modmerge</a> on your SoD installation before you can install this or any other WeiDU-based mod.


#### Enhanced Editions Note

The Enhanced Editions are actively supported games. Please note that every patch update will wipe your current mod setup! If in the middle of a modded game you might want to delay the patch update (if possible) as even after reinstalling the mods, you might not be able to continue with your old savegames. Alternatively, copy the whole game's folder into a new one that can be modded and will stay untouched by game patches. It is important that you install the mod to the language version you are playing the game in. Otherwise, the dialogues of the mod will not show but give error messages.


#### :warning: Warning : procédure d'installation

###### Les variables nécessaires à l'installation sont lues dans le fichier diamant-config-default.ini, ou dans le fichier diamant-config.ini, si ce dernier existe.

Avec les versions prédécentes, pendant la procédure d'installation, de nombreux messages vous permettaient de personnaliser les composants à votre convenance (en fonction de votre jeu IE et des composants que vous aviez installés). Tous ces choix de variables déterminés pendant l'installation du mod ont été externalisés dans le fichier **_diamant-config-default.ini_** situé dans le répertoire mymod. Ce fichier établit une installation « _standard_ ».

Si vous souhaitez choisir d'autres options d'installation, il vous suffit de modifier les variables souhaitées dans le fichier diamant-config-default.ini, puis de sauvegarder ce dernier sous le nom **_1pp-config.ini_**.

Le programme d'installation lira les valeurs des variables dans les deux fichiers ini et donnera la priorité aux vôtres. Si le fichier diamant-config.ini contient une variable non conforme, ou si une variable est manquante, il la remplacera par sa valeur par défaut (celle correspondant à l'installation « _standard_ »).


#### Windows

MYMOD for Windows is distributed as an extractable compressed archive and includes a <acronym title="Weimer Dialogue Utility">WeiDU</acronym> installer.

Extract the contents of the mod archive into the folder of the game you wish to modify, using <a href="http://www.7-zip.org/download.html">7zip</a>, <a href="http://www.rarlab.com/download.htm">WinRAR</a>, or another file compression utility that handles .zip files. When properly extracted, your game directory will contain <strong>setup-mymod.exe</strong> and the folder <strong>mymod</strong>. To install, double-click <strong>setup-mymod.exe</strong> and follow the instructions on screen.

You can run <strong>setup-mymod.exe</strong> in your game folder to reinstall, uninstall or otherwise change components.

[<strong>(Pour une version exe, remplacez les 2 deux premières lignes par les suivantes :)</strong>MYMOD for Windows is distributed as a self-extracting archive and includes a <acronym title="Weimer Dialogue Utility">WeiDU</acronym> installer. To install, simply double-click the archive and follow the instructions on screen.

Alternatively, the files can be extracted into your game directory using <a href="http://www.7-zip.org/download.html">7zip</a> or <a href="http://www.rarlab.com/download.htm">WinRAR</a>. When properly extracted, your game directory will contain <strong>setup-mymod.exe</strong> and the folder <strong>mymod</strong>. To install, double-click <strong>setup-mymod.exe</strong> and follow the instructions on screen.]


#### Mac OS X

MYMOD for Mac OS X is distributed as a compressed tarball and includes a <acronym title="Weimer Dialogue Utility">WeiDU</acronym> installer.

First, extract the files from the tarball into your game directory. When properly extracted, your game directory will contain <strong>setup-mymod</strong>, <strong>setup-mymod.command</strong>, and the folder<strong>mymod</strong>. To install, double-click <strong>setup-mymod.command</strong> and follow the instructions on screen.

You can run <strong>setup-mymod.command</strong> in your game folder to reinstall, uninstall or otherwise change components.


#### Linux

MYMOD for Linux is distributed as a compressed tarball and does not include a <acronym title="Weimer Dialogue Utility">WeiDU</acronym> installer.

Extract the contents of the mod to the folder of the game you wish to modify.

Download the latest version of WeiDU for Linux from <a href="http://www.weidu.org/%7Ethebigg/">WeiDU.org</a> and copy WeiDU and WeInstall to /usr/bin. Following that, open a terminal, <strong>cd</strong> to your game installation directory, run tolower and answer 'Y' to both queries. You can avoid running the second option (linux.ini) if you've already ran it once in the same directory. To save time, the archive is already tolowered, so there's no need to run the first option (lowercasing file names) either if you've extracted only this mod since the last time you lowercased file names. If you're unsure, running tolower and choosing both options is the safe bet.

To install, run <strong>WeInstall setup-mymod</strong> in your game folder. Then run wine <strong>BGMain.exe</strong> and start playing.


#### Note for Complete Uninstallation

In addition to the methods above for removing individual components, you can completely uninstall the mod using <strong>setup-mymod --uninstall</strong> at the command line to remove all components without wading through prompts.</br></br>



## <a name="components" id="components"></a>Components

The installer includes the following components. The number of each is the component <em>DESIGNATED</em> number which gives it a fixed install position, lets other components detect it and allows automated installers like the BiG World Setup specify component choices.


#### 10. 



## Screenshots



## Credits and Acknowledgements

#### Author: <a href="https://www.baldursgateworld.fr/lacouronne/members/freddy_gwendo.html">Gwendolyne</a>

#### Special Acknowledgements to:

#### Programs/tools used in creation:

#### Copyrights Information



## Versions History

#### Version beta 1.0.0 - jour mois novembre 201x
- Initial release.
