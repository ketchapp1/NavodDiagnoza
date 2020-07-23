# Diagnoza - poslední pokus (Varianta A)

1. Nainstalovat [VirtualBox](https://download.virtualbox.org/virtualbox/6.1.12/VirtualBox-6.1.12-139181-Win.exe)
2. Nainstalovat [Rozšíření pro USB2 / 3](https://download.virtualbox.org/virtualbox/6.1.12/Oracle_VM_VirtualBox_Extension_Pack-6.1.12.vbox-extpack)
3. Na emailu budeš mít odkaz na úschovnu, stáhneš si ten archiv a rozbalíš ho, obsahuje **fitkit.vmdk** image OS WinXP s již nainstalovaným diagnostickým software
4. Vytvoříš si někde na disku (tam kde to bez problémů najdeš) složku, kam vložíš ten image **fitkit.vmdk**
5. Až budeš mít tyto kroky splněné, spustíš VirtualBox

6. Po spuštění VirtualBoxu klikneš v levém horním rohu na **Nový**
7. Otrevře se ti okno "Vytvoření virtuálního počítače", kde zadáš název XP a zkontroluješ, jestli je TYP Microsoft Windows a VERZE Windows XP (32-bit), pak potvrdíš
8. Dále se ti objeví okno s nastavením RAM, to nastavíš na 4096MB a potvrdíš
9. Pak máš okno s nastavením disku, tady zaklikneš "Použít existující soubor s virtuálním pevným diskem" a najdeš si cestu do složky s image **fitkit.vmdk** a opet potvrdíš. Pod tlačítkem **Nový** se ti vytvořil disk **XP**

10. Připojíš ten kabel k PC
11. Teď příjde věc, u které si nejsem úplně jistý (nemám to na čem vyzkoušet), pravým tlačítkem myši klikneš na ten virtuální počítač **XP**, pak **Nastavení** a najdeš kolonku **USB**, kde potvrdíš **Povolit USB ovladač** a zvolíš **USB 2.0** (asi, kdyžtak dáš 3.0). Pak klikneš na tlačítko s plusem a vybereš ten kabel a potvrdíš.

12. Poklepeš na ten virtuální počítač a spusí se ti WinXP, máš tam nainstalovanou tu diagnostiku a když dá pán bůh bude registrovat i ten kabel.
---
- Byl bych rád, aby se ten image nikde nešířil
- Ve tvém notebooku nemusíš vypínat internet, ani antivir, v tom image neníé přístup k internetu.
- Pokud se ti to podaří podle předchozího návodu rozchodit, máš vyhráno, když bude nějaký zádrhel v instalaci VirtualBoxu, image nebo v nastavení USB, připojím se k tobě přes TeamViewer a pokusím se to rozchodit. Pokud to i tak nepujde, tak je tu Varianta B

## Varianta B
Když selže Varianta A, tak ti nezbívá nic jiného, než si udělat výlet do Pasohlávek, zajíét si do Aqua a vyřešit to s borcem :)
