# MYMOD

<p><strong>Author:</strong> <a href="https://www.baldursgateworld.fr/lacouronne/Auteur.html">bibi</a><br />
<strong>Version:</strong> n.n.n<br />
<strong>Languages:</strong> <a href="README.md">French</a>, English<br />
<strong>Plaeforms:</strong> Windows, Mac OS X et Linux</p>

<strong>Forum du mod :</strong> <a href="https://www.baldursgateworld.fr/lacouronne/mymod/">Mymod</a>
</br></br>



## Overview

<p>Courte description du mod : Ce mod...... ou L'objet de ce mod......</p>

<p>Il s'agit d'un mod�le de fichier readme pour GitHub destin� aux mods d�velopp�s et/ou publi�s sur la Couronne de Cuivre. Il est �crit en langage Markdown. Bien qu'il soit assez proche du langage HTML, certains formatages ne sont pas pris en compte par GitHub, comme l'affichage des couleurs.</p>

<p>Pour chaque section, j'ai repris, chaque fois que c'�tait possible, des �l�ments de traductions d�j� publi�es (par les d'Oghms ou par bibi) afin de conserver un semblant d'homog�n�it� dans les termes employ�s. Il suffit alors de conserver celles dont on a besoin (liste des jeux compatibles, proc�dures d'installation selon la plateforme, liste des outils utilis�s...) et, pour le reste, de remplacer MYMOD et Auteur par le nom du mod et de son auteur, de modifier les liens et de remplir les textes ad�quats. Pour certaines sections, j'ai �t� le plus exhaustif possible : il vous suffit de choisir les paragraphes qui vous int�ressent et de supprimer les autres. &#128521;</p>


<p>Malheureusement, le rendu d'un fichier .md n'est v�ritablement effective que dans GitHuB, ce qui ne vous permet pas de visualiser votre mise en page dans Notepad++. Il existe cependant plusieurs utilitaires vous permettant de les �diter et de visualiser partiellement vos modifications. Parcellement parce que certaines balises comme [br (break line)] apparaissent � l'�cran M�ME si elles resteront invisibles dans GitHub. Personnellement, j'ai opt� pour <a href=https://typora.io/">Typora</a>, mais il en existe d'autres.</p><br>



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


#### :warning: Warning : proc�dure d'installation

###### Variables needed for installation are read from <em><a href="https://raw.githubusercontent.com/Auteur/mymod/master/mymod/mymod-config-default.ini">mymod-config-default.ini</a></em>file, or <em><a href="https://raw.githubusercontent.com/Auteur/mymod/master/mymod/mymod-config.ini">mymod-config.ini</a></em> if it exists.

As interrupting installation with plain text prompts allowing players to customise components to their liking, those variables have been moved into <a href="https://raw.githubusercontent.com/Auteur/mymod/master/mymod/mymod-config-default.ini">mymod-config-default.ini</a> file in <strong>mymod</strong> folder. This file provides a '<em>standard</em>' installation.

If you want to define your own customized installation, you have to modify the variables involved in <strong><em>mymod-config-default.ini</em></strong>, then save this file as <strong><em>mymod-config.ini</em></strong>.

The installation process will read both ini files and prioritize user values. If a value is not set or mismatched in mymod-config.ini, any installation failure will be prevented by reverting it back to its default value.</br>

Please read the <a href="https://raw.githubusercontent.com/Auteur/mymod/master/mymod/mymod-config-english.txt">mymod-config-language.txt</a> file (with 'language' being the installation language you chose) to check the variables names and their meanings. Here is a chart listing the variables related to the installation process:<br>

<table style="margin-left: 80px" summary="Installation variables listing">
	<tr>
		<th>Variables</th>
		<th>Signification</th>
		<th>Type</th>
		<th>Valeurs possibles</th>
		<th>D�faut</th>
	</tr>
	<tr>
		<td>mymod_variable1</td>
		<td>d�finit blabla</td>
		<td>num�rique</td>
		<td>1 ou 2</td>
		<td><strong><span style="color: #FFCC33;">1</span><strong></td>
	</tr>
	<tr>
		<td>mymod_variable2</td>
		<td>d�finit blabla</td>
		<td>num�rique</td>
		<td>1, 2, 3 ou 4</td>
		<td><strong><span style="color: #FFCC33;">2</span><strong></td>
	</tr>
	<tr>
		<td>mymod_variable3</td>
		<td>d�finit blabla</td>
		<td>alphanum�rique</td>
		<td>une lettre : A, B ou C</td>
		<td><strong><span style="color: #FFCC33;">A</span><strong></td>
	</tr>
	<tr>
		<td>mymod_variable4</td>
		<td>d�finit le nom que vous souhaitez donner � votre monture</td>
		<td>alphanum�rique</td>
		<td>un nom !</td>
		<td><strong><span style="color: #FFCC33;">Fl�che d'argent</span><strong></td>
	</tr>
</table>


#### Windows

MYMOD for Windows is distributed as an extractable compressed archive and includes a <acronym title="Weimer Dialogue Utility">WeiDU</acronym> installer.

Extract the contents of the mod archive into the folder of the game you wish to modify, using <a href="http://www.7-zip.org/download.html">7zip</a>, <a href="http://www.rarlab.com/download.htm">WinRAR</a>, or another file compression utility that handles .zip files. When properly extracted, your game directory will contain <strong>setup-mymod.exe</strong> and the folder <strong>mymod</strong>. To install, double-click <strong>setup-mymod.exe</strong> and follow the instructions on screen.

You can run <strong>setup-mymod.exe</strong> in your game folder to reinstall, uninstall or otherwise change components.

[<strong>(Pour une version exe, remplacez les 2 deux premi�res lignes par les suivantes :)</strong>MYMOD for Windows is distributed as a self-extracting archive and includes a <acronym title="Weimer Dialogue Utility">WeiDU</acronym> installer. To install, simply double-click the archive and follow the instructions on screen.

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


#### 10. Composant 1 : blabbla

Description du composant 1.</br>

------------------------

#### 20 Composant 2 : blabbla

Description du composant 2.</br>

------------------------

#### 30 Composant 3 : blabbla

Exemple de composant pr�sentant des tableaux.

<table style="margin-left: 80px" summary="Rebalanced Tazok and Dig-Dag">
	<tr>
		<th>Cr�ature</th>
		<th>Kit</th>
		<th>Niveau <span style="font-weight: normal">&#160;&#160;&#160;(ex)</span></th>
		<th>XP <span style="font-weight: normal">&#160;&#160;&#160;(ex)</span></th>
		<th>PV <span style="font-weight: normal">&#160;&#160;&#160;(ex)</span></th>
		<th>Force <span style="font-weight: normal">&#160;&#160;&#160;(ex)</span></th>
		<th>Constitution <span style="font-weight: normal">&#160;&#160;&#160;(ex)</span></th>
		<th>Comp�tence martiale</th>
	</tr>
	<tr>
		<td>Tazok</td>
		<td>--</td>
		<td><strong>19</strong>&#160;&#160;&#160;(18)</td>
		<td><strong>12000</strong>&#160;&#160;&#160;(6000)</td>
		<td><strong>154</strong>&#160;&#160;&#160;(136)</td>
		<td>--</td>
		<td>--</td>
		<td>TWO-HANDED SWORD +++++</td>
	</tr>
	<tr>
		<td>FIRorc01 (DigDag)</td>
		<td>Berserker</td>
		<td><strong>13</strong>&#160;&#160;&#160;(12)</td>
		<td><strong>7000</strong>&#160;&#160;&#160;2000)</td>
		<td><strong>107</strong>&#160;&#160;&#160;(99)</td>
		<td><strong>22</strong>&#160;&#160;&#160;(17)</td>
		<td><strong>22</strong>&#160;&#160;&#160;(9)</td>
		<td>BASTARD SWORD +++++</td>
	</tr>
</table><br>



## Screenshots

<img src="images/baldr000.jpg">
<img src="images/baldr001.jpg"></br>



## Credits and Acknowledgements

#### Author: <a href="https://www.baldursgateworld.fr/lacouronne/members/freddy_gwendo.html">Gwendolyne</a>


#### Special Acknowledgements to:

- <a href="https://www.baldursgateworld.fr"><acronym title="Copper Coronet">La Couronne de Cuivre</acronym></a> team for hosting the mod.
- The creators of the Baldur's Gate series: <a href="http://www.bioware.com/">Bioware</a> and <a href="http://www.obsidian.net/">Black Isle Studios</a>.
- dugland for coding help.
- trucmuche for coding help and suggestions.
- bidule for dialogue help.
- xxx for the French translation.
- yyy for proofreading.
- Thanks to artists from <a href="https://www.pinterest.fr/">Pinterest</a> for their portraits.
- Everyone else from the <a href="https://www.baldursgateworld.fr">La Couronne de Cuivre</a>, <a href="http://gibberlings3.net/forums/">The Gibberlings Three</a>, <a href="http://www.shsforums.net/">Spellhold Studios</a> forums, and the other Infinity Engine gaming and modding communities who offered their help and support.
- etc.


#### Programs/tools used in creation:

- <a href="http://www.weidu.org/%7Ethebigg/"><acronym title="Weimer Dialogue Utility">WeiDU</acronym></a>, by Wes Weimer, the bigg and Wisp.
- <a href="http://forums.pocketplane.net/index.php/topic,25153.msg314249.html#msg314249">Near Infinity</a>, by Jon Olav Hauglid, FredSRichardson, and Argent77.
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
- <a href="http://www.gibberlings3.net/tools/weidu.php">WeiDU ConTEXT Highlighters </a>, by Idobek, updated by cmorgan.
- <a href="http://www.editpadpro.com/editpadclassic.html">EditPad Classic</a>, by Jan Goyvaerts.
- <a href="http://www.pspad.com/en/">PSPad</a>, by Jan Fiala.
- <a href="http://www.bulkrenameutility.co.uk/">Bulk Rename Utility</a>, by TGRMN Software.


#### Copyright Information

Libre � vous de choisir la formule et la pr�sentation qui vous conviennent :

###### MYMOD is not developed, supported, or endorsed by BioWare&trade; or Interplay/BlackIsle, Overhaul, Beamdog or the Wizards of the Coast. It was developed by AUTEUR, based on material from the game Baldur's Gate II and its expansion.
###### All mod content is &copy;AUTEUR.
###### Baldur's Gate II: Shadows of Amn and Baldur's Gate II: Throne of Bhaal &copy; TSR, Inc. The BioWare Infinity Engine is &copy; BioWare Corp. All other trademarks and copyrights are property of their respective owners.

###### This mod was created to be freely enjoyed by all Baldur's Gate II players, and its content is free of rights. However, it should not be sold, published, compiled or redistributed in any form without the consent of the author.
###### Please note that any and all redistribution and/or hosting of this mod is prohibited without permission from the author.

###### If there are any copyright issues or this statement needs revision, then please contact me and advise me what to do about it. Most notably, if you see any artwork in this mod that might conflict with Copyright rules, please let me know as soon as possible, and I will remove the conflicting content immediately.

###### The modding community for the Infinity Engine has been going strong for more than 10 years now, and is the culmination of thousands of unpaid modding hours by fellow fans of the game. Modders produce their best work and players get the best, well-supported mods when we all work together.
###### There are two big ways to upset this harmony. One is to claim someone else's work as your own. The second is to host and redistribute a mod without permission from the author(s).
###### Be kind to your fellow players and modders. Don't do either.</br></br>



## Version History

#### Version 2.0.0 - Mois jour, 201x
- modification niveau 1
  - modification niveau 2
    - modification niveau 3
  - modification niveau 2
- modification niveau 1


#### Version beta 1.0.0 - Mois jour, 201x
- Initial release.
