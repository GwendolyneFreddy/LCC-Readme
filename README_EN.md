
![Latest Release](https://img.shields.io/github/v/release/gwendolynefreddy/lcc-readme?include_prereleases&color=gold)<a name="top" id="top">
![Latest Release](https://img.shields.io/static/v1?label=version&message=v4.0.0&color=gold)
![Platform](https://img.shields.io/static/v1?label=platform&message=windows&color=informational)
![Language](https://img.shields.io/static/v1?label=language&message=English%20%7C%20French%20&color=limegreen)

<div align="center"><h1>MYMOD</h1>

<h3>A <a href="https://www.baldursgateworld.fr">La Couronne de Cuivre</a> mod for Baldur's Gate II:ToB, Baldur's Gate Trilogy, BG2:EE and EET<h3>

</div><br />


**Author:** <a href="https://www.baldursgateworld.fr/lacouronne/Auteur.html">bibi</a>  
**Languages:** <a href="README.md">French</a>, English  
**Mod Website and Forum:** <a href="https://www.baldursgateworld.fr/lacouronne/mymod/">MYMOD</a><br /><br />


<div align="center">
<a href="#intro">Overview</a> &#8226; <a href="#compat">Compatibility</a> &#8226; <a href="#installation">Installation</a> &#8226; <a href="#components">Components</a> &#8226; <a href="#images">Screenshots</a> &#8226; <a href="#credits">Credits and Acknowledgements</a> &#8226; <a href="#versions">Version History</a></br>
</div>

<hr>


## <a name="intro" id="intro"></a>Overview

>Courte description du mod : Ce mod... ou L'objet de ce mod...</p>

Il s'agit d'un modèle de fichier readme pour GitHub destiné aux mods développés et/ou publiés sur la Couronne de Cuivre. Il est écrit en langage Markdown. Bien qu'il soit assez proche du langage HTML, certains formatages ne sont pas pris en compte par GitHub, comme l'affichage des couleurs.

Pour chaque section, j'ai repris, chaque fois que c'était possible, des éléments de traductions déjà publiées (par les d'Oghms ou par bibi) afin de conserver un semblant d'homogénéité dans les termes employés. Il suffit alors de conserver celles dont on a besoin (liste des jeux compatibles, procédures d'installation selon la plateforme, liste des outils utilisés...) et, pour le reste, de remplacer MYMOD et Auteur par le nom du mod et de son auteur, de modifier les liens et de remplir les textes adéquats. Pour certaines sections, j'ai été le plus exhaustif possible : il vous suffit de choisir les paragraphes qui vous intéressent et de supprimer les autres. &#128521;


Malheureusement, le rendu d'un fichier .md n'est véritablement effective que dans GitHub, ce qui ne vous permet pas de visualiser votre mise en page dans Notepad++. Il existe cependant plusieurs utilitaires vous permettant de les éditer et de visualiser partiellement vos modifications. Partiellement parce que certaines balises comme [br (break line)] apparaissent à l'écran MÊME si elles resteront invisibles dans GitHub. Personnellement, j'ai opté pour <a href="https://typora.io/">Typora</a>, mais il en existe d'autres.<br>

<details><summary>CLICK ME</summary>
<p>

#### yes, an hidden code block!

Deux listes de codes de smileys et d'emoji utilisables par markdown :
- <a href="https://gist.github.com/rxaviers/7360908">Complete list of github markdown emoji markup</a>.
- <a href="https://github.com/StylishThemes/GitHub-Dark/wiki/Emoji">GitHub-Dark Emoji (All GitHub Emoji)</a>.

<ins>Voici comment souligner un texte</ins>

</p><br>
</details>
<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="compat" id="compat"></a>Compatibility

This mod is designed to work on all Infinity Engine games. This includes: Baldur's Gate: Enhanced Edition (BGEE), Baldur's Gate II: Enhanced Edition (BG2EE), Icewind Dale: Enhanced Edition (IWDEE), Planescape: Torment: Enhanced Edition (PsTEE), and the BGEE Siege of Dragonspear expansion (SoD) ; the original Baldur's Gate (BG), with or without the Tales of the Sword Coast (TotSC) expansion, the original Baldur's Gate II (BG2, or just SoA), with or without the Throne of Bhaal (ToB) expansion ; the conversion projects <a href="http://www.shsforums.net/forum/261-bgt-weidu/">Baldur's Gate Trilogy</a> (BGT), <a href="http://www.pocketplane.net/tutu/">Baldur's Gate Tutu (Tutu)</a>, Icewind Dale-in-Baldur's Gate II (IWD-in-BG2), and <a href="https://github.com/K4thos/EET/releases">Enhanced Edition Trilogy</a> (EET) ; the original Icewind Dale (IWD) with or without either of its expansions, Heart of Winter (HoW) and Trials of the Luremaster (TotLM), Icewind Dale II (IWD2), the original Planescape: Torment (PsT).


MYMOD is a WeiDU mod, and therefore should be compatible with all WeiDU mods. [facultatif : It has been tested on several different installations, and has so far worked perfectly.] However, we cannot test every single one. [Choisir une formule parmi les suivantes :] If you do encounter any bugs, please contact <a href="https://www.baldursgateworld.fr/lacouronne/Auteur.html">AUTHOR</a> or alternatively post on the forums. If you encounter any bugs, please report them on the forum!

Though I am striving to make MYMOD compatible with as many other mods as possible, there is always a chance that incompatibilities will arise. Below are the ones discovered thus far:
- mod 1
- mod 2
- ...


You are strongly recommended to also download and install the <a href="http://www.gibberlings3.net/bg2fixpack/">BG2 Fixpack</a> before proceeding with the installation of this mod.<br>
<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="installation" id="installation"></a>Installation

#### Notes

*If you've previously installed the mod, remove it before extracting the new version. To do this, run **`setup-mymod.exe`**, un-install all previously installed components and delete the :file_folder: **mymod** folder.*

*When installing or un-installing, **do not close the DOS window** by clicking on the **X** button! Instead, press the **Enter** key whenever instructed to do so.*

*__Disable any antivirus__ or other memory-resident software before installing this or any other mod. Some (particularly avast and Norton!) have a tendency to report false positives with mod activity, resulting in failed installs.*

## 

#### Special Note for Siege of Dragonspear from Steam/GOG

Good Old Games (GOG) and Steam both package the additional content for Siege of Dragonspear in a method that WeiDU, the tool used to install this mod, cannot access. You must run a program called <a href="https://github.com/Argent77/A7-DlcMerger/releases/latest">DLC Merger</a> on your SoD installation before you can install this or any other WeiDU-based mod.

## 

#### Enhanced Editions Note

The Enhanced Editions are actively supported games. Please note that every patch update will wipe your current mod setup! If in the middle of a modded game you might want to delay the patch update (if possible) as even after reinstalling the mods, you might not be able to continue with your old savegames. Alternatively, copy the whole game's folder into a new one that can be modded and will stay untouched by game patches. It is important that you install the mod to the language version you are playing the game in. Otherwise, the dialogues of the mod will not show but give error messages.

## 

#### :warning: Warning : Installation process

###### Options needed for installation are read from *<a href="https://raw.githubusercontent.com/Auteur/mymod/master/mymod/mymod.ini">mymod.ini</a>* file, or *<a href="https://raw.githubusercontent.com/Auteur/mymod/master/mymod/mymod-user.ini">mymod-user.ini</a>* if it exists.

As interrupting installation with plain text prompts allowing players to customise components to their liking, those options have been moved into <a href="https://raw.githubusercontent.com/Auteur/mymod/master/mymod/mymod.ini">mymod.ini</a> file in :file_folder: **mymod** folder. This file provides a '*standard*' installation.

If you want to define your own customized installation, you have to edit the **<em>[Mod_content]</em>** section of *__mymod.ini__* with Notepad or another text editor, then save this file as *__mymod-user.ini__*.

Each line consists of a configuration option, then '=', then a number or an alphanumeric character string. The only thing you should edit is the number or the string.

The installation process will read both ini files and prioritize user's options values. If a value is not set or mismatched in mymod-user.ini, any installation failure will be prevented by reverting it back to its default value.</br>

Here is a chart listing options related to the installation process (Don't change anything not listed; these are part of the testing framework.):<br>

| Option | Install Option Description | Type | Values | Default |
| :---: | --- | :---: | :---: | :---: |
| mymod_variable1 | blabla<br>1 = first value description (recommended).<br>2 = second value description.<br> | integer | 1 or 2 | <strong>1<strong> |
| mymod_variable2 | blabla<br>1 = first value description (recommended).<br>2 = second value description.<br>3 = third value description.<br> | integer | 1, 2 or 3 | <strong>1<strong> |
| mymod_variable3 | blabla<br> | string | one character | <strong>A<strong> |
| mymod_variable4 | blabla<br> | string | a name! | <strong>Hello<strong> |

## 

#### Windows

MYMOD for Windows is distributed as an extractable compressed archive and includes a WeiDU installer.

Extract the contents of the mod archive into the folder of the game you wish to modify (*the folder which contains the "CHITIN.KEY" file*), using <a href="http://www.7-zip.org/download.html">7zip</a>, <a href="http://www.rarlab.com/download.htm">WinRAR</a>, or another file compression utility that handles .zip files. On successful extraction, there should be a :file_folder: mymod and a setup-mymod.exe file in your game folder. To install, simply double-click **`setup-mymod.exe`** and follow the instructions on screen.

Run **`setup-mymod.exe`** in your game folder to reinstall, un-install or otherwise change the components settings.

[**(Pour une version exe, remplacez les 2 deux premières lignes par les suivantes :)**MYMOD for Windows is distributed as a self-extracting archive and includes a WeiDU installer. To install, simply double-click the archive and follow the instructions on screen.

Alternatively, the files can be extracted into your game directory using <a href="http://www.7-zip.org/download.html">7zip</a> or <a href="http://www.rarlab.com/download.htm">WinRAR</a>. When properly extracted, your game directory will contain **setup-mymod.exe** and the folder **mymod**. To install, double-click **setup-mymod.exe** and follow the instructions on screen.]

## 

#### Mac OS X

MYMOD for Mac OS X is distributed as a compressed tarball and includes a WeiDU installer.

First, extract the files from the tarball into your game directory. On successful extraction, there should be a :file_folder: mymod folder, setup-mymod and setup-mymod.command files in your game folder. To install, simply double-click **`setup-mymod.command`** and follow the instructions on screen.

Run **`setup-mymod.command`** in your game folder to reinstall, un-install or otherwise change the components settings.

## 

#### Linux

MYMOD for Linux is distributed as a compressed tarball and does not include a WeiDU installer.

Extract the contents of the mod to the folder of the game you wish to modify.

Download the latest version of WeiDU for Linux from <a href="https://github.com/WeiDUorg/weidu/releases">WeiDU.org</a> and copy weidu, weinstall and tolower to `/usr/local/bin` (create it if needed). Following that, open a terminal, **`cd`** to your game installation directory, run **`/usr/local/bin/tolower`** and answer 'Y' to both queries. You can avoid running the second option (linux.ini) if you've already ran it once in the same directory. To save time, the archive is already tolowered, so there's no need to run the first option (lowercasing file names) either if you've extracted only this mod since the last time you lowercased file names. If you're unsure, running tolower and choosing both options is the safe bet.

To install, type **`export PATH=$PATH:/usr/local/bin`**, then run **`weinstall setup-mymod`** (or **`wine baldur.exe`** for EE games) in your game folder. Then run **`wine bgmain.exe`** and start playing.

## 

#### Note for Complete Un-installation

In addition to the methods above for removing individual components, you can completely un-install the mod using **`setup-mymod --uninstall`** at the command line to remove all components without wading through prompts.</br>
<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="components" id="components"></a>Components

The installer includes the following components. The number of each is the component *DESIGNATED* number which gives it a fixed install position and allows automated installers to specify component choices.<br /><br />


#### 10. Component 10 : main component

Description du composant 10.</br>

## 

#### 20. Component 20 : blabbla

Description du composant 20.</br>

## 

#### 30. Component 30 : blabbla

Exemple de composant présentant des tableaux.

<table style="margin-left: 80px" summary="Rebalanced Tazok and Dig-Dag">
	<tr>
		<th>Creature</th>
		<th>Kit</th>
		<th>Level <span style="font-weight: normal">&#160;&#160;&#160;(ex)</span></th>
		<th>XP <span style="font-weight: normal">&#160;&#160;&#160;(ex)</span></th>
		<th>HD <span style="font-weight: normal">&#160;&#160;&#160;(ex)</span></th>
		<th>Strength <span style="font-weight: normal">&#160;&#160;&#160;(ex)</span></th>
		<th>Constitution <span style="font-weight: normal">&#160;&#160;&#160;(ex)</span></th>
		<th>Weapon Proficiency</th>
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
<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="componentslist" id="componentslist"></a>Components (alternative presentation for lots of components)

To be used with a huge number of components. 

The installer includes the following components. The number of each is the component *DESIGNATED* number which gives it a fixed install position and allows automated installers to specify component choices.<br /><br />

><span style="margin-left: 50px;"><a href="#10">[10] Component 10 (main component)</a></span></br>
><span style="margin-left: 50px;"><a href="#20">[20] Component 20</a></span></br>
><span style="margin-left: 50px;"><a href="#30">[30] Component 30</a></span></br>
><span style="margin-left: 50px;"><a href="#40">[40] ...</a></span></br>


## 

<a name="10" id="10"></a>**10. Component 10 (main component)**<br />

Main component description.</br>
<div align="right"><a href="#componentslist">Back to components list</a></div>

## 

<a name="10" id="20"></a>**20. Component 20**<br />

Component 20 description.</br>
<div align="right"><a href="#componentslist">Back to components list</a></div>

## 

<a name="30" id="10"></a>**30. Component 30**<br />

Component 30 description.</br>
<div align="right"><a href="#componentslist">Back to components list</a></div>


<hr>


## <a name="images" id="images"></a>Screenshots

<img src="images/baldr000.jpg">
<img src="images/baldr001.jpg"></br>
<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="credits" id="credits"></a>Credits and Acknowledgements

#### Author: <a href="https://www.baldursgateworld.fr/lacouronne/members/freddy_gwendo.html">Gwendolyne</a>

## 

#### Special Acknowledgements to:

- <a href="https://www.baldursgateworld.fr">La Couronne de Cuivre</a> team for hosting the mod.
- The creators of the Baldur's Gate series: <a href="http://www.bioware.com/">Bioware</a> and <a href="http://www.obsidian.net/">Black Isle Studios</a>.
- machin for permission to use blabla.
- dugland for coding help.
- trucmuche for coding help and suggestions.
- bidule for dialogue help.
- xxx for the French translation.
- yyy for proofreading.
- Thanks to artists from <a href="https://www.pinterest.fr/">Pinterest</a> for their portraits.
- Everyone else from the <a href="https://www.baldursgateworld.fr">La Couronne de Cuivre</a>, <a href="http://gibberlings3.net/forums/">The Gibberlings Three</a>, <a href="http://www.shsforums.net/">Spellhold Studios</a> forums, and the other Infinity Engine gaming and modding communities who offered their help and support.
- etc.

## 

#### Programs/tools used in creation:

- <a href=https://github.com/WeiDUorg/weidu/releases"><acronym title="Weimer Dialogue Utility">WeiDU</acronym></a>, by Wes Weimer, Valerio Bigiani (the bigg) and Wisp.
- <a href="https://github.com/Argent77/NearInfinity/releases">Near Infinity</a>, by Jon Olav Hauglid, FredSRichardson, and Argent77.
- <a href="http://www.shsforums.net/topic/31285-infinity-explorer-v085/">Infinity Explorer</a>, by Dmitry Jemerov / bigmoshi.
- <a href="http://www.gibberlings3.net/tools/dltcep.php"><acronym title="Dragonlance Total Conversion Editor Pro">DLTCEP</acronym></a>, by Avenger.
- <a href="http://www.baldursgatemods.com/forums/index.php?action=downloads;sa=view;down=85">CreMaker_v3.1.9</a>.
- <a href="https://gibberlings3.github.io/iesdp/"><acronym title="Infinity Engine Structures Description Project">IESDP</acronym></a>, maintained by igi and lynx.
- <a href="http://www.gibberlings3.net/debug/">G3 Debugging Suite</a>, by CamDawg.
- <a href="http://www.teambg.eu/?page=tools&amp;cat=32">BAM Workshop</a>, by Glenn Flansburg.
- <a href="http://www.shsforums.net/topic/57564-bamworkshop/">BAMWorkshop 2</a>, by Andrew Bridges.
- <a href="http://www.shsforums.net/index.php?showtopic=42359">BAM Batcher</a>, by Miloch.
- <a href="https://www.adobe.com/products/photoshop.html">Adobe Photoshop</a>
- <a href="http://www.gimp.org/"><acronym title="GNU Image Manipulation Program">GIMP</acronym></a>, by the GIMP team.
- <a href="http://www.gamani.com/">GIF Movie Gear</a>
- <a href="https://www.blender.org/">Blender</a>, by the Blender Foundation.
- <a href="https://www.autodesk.com/products/3ds-max/overview">3ds Max</a>
- <a href="http://notepad-plus-plus.org/">Notepad++</a>, by the Notepad++ team, Don Ho, and the spellcheck plug-in.
- <a href="http://www.shsforums.net/files/file/1048-weidu-highlighter-for-notepad/">WeiDU Notepad++ Highlighters </a>, by Argent77.
- <a href="http://www.context.cx/">ConTEXT Text Editor</a>, by Eden Kirin.
- <a href="https://www.gibberlings3.net/mods/tools/weidu/">WeiDU ConTEXT Highlighters </a>, by Idobek, updated by cmorgan.
- <a href="http://www.editpadpro.com/editpadclassic.html">EditPad Classic</a>, by Jan Goyvaerts.
- <a href="http://www.pspad.com/en/">PSPad</a>, by Jan Fiala.
- <a href="http://www.bulkrenameutility.co.uk/">Bulk Rename Utility</a>, by TGRMN Software.

## 

#### Copyright Information

Libre à vous de choisir la formule et la présentation qui vous conviennent :

###### MYMOD is not developed, supported, or endorsed by BioWare&trade; or Interplay/BlackIsle, Overhaul, Beamdog or the Wizards of the Coast. It was developed by AUTEUR, based on material from the game Baldur's Gate II and its expansion.
###### All mod content is &copy;AUTEUR.
###### Baldur's Gate II: Shadows of Amn and Baldur's Gate II: Throne of Bhaal &copy; TSR, Inc. The BioWare Infinity Engine is &copy; BioWare Corp. All other trademarks and copyrights are property of their respective owners.

###### This mod was created to be freely enjoyed by all Baldur's Gate II players, and its content is free of rights. However, it should not be sold, published, compiled or redistributed in any form without the consent of the author.
###### Please note that any and all redistribution and/or hosting of this mod is prohibited without permission from the author.

###### If there are any copyright issues or this statement needs revision, then please contact me and advise me what to do about it. Most notably, if you see any artwork in this mod that might conflict with Copyright rules, please let me know as soon as possible, and I will remove the conflicting content immediately.

###### <a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/deed.en_US"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by-sa/3.0/88x31.png" /></a> MYMOD is not developed, supported, or endorsed by BioWare&trade; or Interplay/BlackIsle, Overhaul, Beamdog or the Wizards of the Coast. It was developed by Auteur, based on material from the game Baldur's Gate II and its expansion, and is licensed under a <a href="http://creativecommons.org/licenses/by-sa/3.0/deed.en_US">Creative Commons Attribution-ShareAlike 3.0 Unported License</a>.

###### The modding community for the Infinity Engine has been going strong for more than 10 years now, and is the culmination of thousands of unpaid modding hours by fellow fans of the game. Modders produce their best work and players get the best, well-supported mods when we all work together.
###### There are two big ways to upset this harmony. One is to claim someone else's work as your own. The second is to host and redistribute a mod without permission from the author(s).
###### Be kind to your fellow players and modders. Don't do either.</br></br>
<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="versions" id="versions"></a>Version History

#### Version 2.0.0 (Mois jour, 201x)

- modification niveau 1
  - modification niveau 2
    - modification niveau 3
  - modification niveau 2
- modification niveau 1

## 

#### Version beta 1.0.0 (Mois jour, 201x)

- Initial release.
<div align="right"><a href="#top">Back to top</a></div>
