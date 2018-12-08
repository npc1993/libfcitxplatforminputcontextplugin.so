System info:	Debian sid  
Date:		2018.12.08   
Qt 5 Version: 5.11.1

Compiled using QT and [fcitx-qt5](https://github.com/fcitx/fcitx-qt5.git).

`libfcitxplatforminputcontextplugin.so.for.RStudio` might be used to fix Fcitx Chinese input issue under RStudio 1.2.1114. It was compiled using QT 5.11.1, and dev version of fcitx-qt5 from GitHub.  
Put the file in `/usr/lib/rstudio/bin/plugins/platforminputcontexts/` and 
rename it to `libfcitxplatforminputcontextplugin.so`.

If you have the same environment with me, you can try the deb package out.
- Date: 2018-12-08
- Tested: Debian stretch + RStudio 1.1.453, Debian sid + RStudio 1.1.453.

Other distro or Rstudio version are to be tested.