# ATOM
Atom is een tekstverwerkingsprogramma dat meer kan dan alleen het schrijven en compileren van TEX-files. Het kan gebruikt worden als platform IDE voor embedded systemen als Arduino, ARM, … . Het installeren van dit programma is iets minder voor de hand liggend, maar het resultaat en gebruik ervan mag er des te meer zijn. Atom is volledig aanpasbaar en extra packages voor het optimaliseren van het gebruik kunnen eenvoudig geïnstalleerd worden.

_Belangrijk: installeer de twee programma&#39;s in deze volgorde!_

## MiKTeX/MacTeX installeren

#### MiKTeX installeren (WINDOWS)
  1. Ga naar de MiKTeX download [pagina](http://miktex.org/download/) en selecteer de basis installer.
  2. Voer het .exe bestand uit.
  3. Aanvaard de &quot;copying conditions&quot; en ga door alle stappen van de installer. **GEBRUIK DE DEFAULT LOCATIE VOOR HET INSTALLEREN VAN DE BINARIES. DIT OM LATER PROBLEMEN TE VOORKOMEN BIJ HET INSTALLEREN VAN ATOM.**
  4. Het downloaden van de packages kan enkele minuten duren.
  5. Sluit de installatie af. Er staat nu LaTeX op je computer.

#### MacTeX (OSX)
  1. Ga naar de MacTeX download [pagina](https://tug.org/mactex/mactex-download.html) en download het juiste pkg-bestand. Dit kan enige tijd duren door de grootte van het bestand. (&gt;2GB)
  2. Sleep het gedownloade bestand naar een daarvoor toegekende map en dubbel klik het om te installeren.
  3. In /Applications/TeX staat een READ ME bestand wat uitlegt hoe LaTeX te gebruiken.

## ATOM installeren
  1. Ga naar de download [pagina](https://atom.io/) en download de laatste versie van ATOM.
  2. Voor je de installer uitvoert, wees er zeker van dat MiKTeX volledig geïnstalleerd is. Indien dit het geval is, voer je het .exe bestand uit.
  3. Aanvaard alle voorwaarden en gebruik de default locatie voor het installeren van het programma.
  4. Open het programma en open hierin de Package Installer. Dit kan gedaan worden door naar File menu &gt; Settings te gaan of eenvoudigweg CTRL+SHIFT+P en in het zoekveld naar **Install Packages** te zoeken **en Settings View: Install Packages and Themes** te klikken.
  5. Zoek hierin naar &quot;Latex&quot; en installeer de package. Voor meer [info](https://atom.io/packages/latex).
  6. Wees er zeker van dat het PATH naar de binaries voor de Tex-distributie correct is. Zie figuur hieronder. Dit kan gedaan worden door in Instellingen van de Latex-package naar de binaries te verwijzen.
  7. Hierna kan je naar believen LaTeX documenten beginnen typen.
  8. Het builden van de PDF&#39;s wordt gedaan door eenvoudigweg CTRL+ALT+B.
  9. Enkele interessante links voor het instellen packages vind je [hier](http://blog.matteomerola.me/2016/02/atom-for-latex), [hier](http://economistry.com/2016/02/create-first-pdf-latex-atom-mac/) en [hier](https://rolflekang.com/writing-latex-in-atom/).

![alt text](https://github.com/BertCox/LaTex/blob/master/installation-procedure/Atom.png "Markdown Settings")
