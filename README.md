# Rocnikovy-projekt - Matěj Topinka T3A


Název projektu: DIY "Meteo-časová" stanice na platformě Arduino UNO R3

Mým cílem v tomto projektu bylo vytvořit DIY „Meteo-časovou“ stanici za pomoci mikrokontroléru Arduino UNO R3. V současnosti stanice zobrazuje čas a datum, ale plánujeme ji v budoucnu rozšířit o další funkce.

Popis konstrukce a umístění součástek:

Pro umístění součástek jsem použil starou plastovou krabici od malého rozvaděče, protože má dostatek prostoru pro případné úpravy. Do této krabice jsem pomocí tavné pistole připevnil LCD displej a segmentový displej, následně jsem vše propojit a zapojil. Po připojení zařízení k počítači přes USB a nahrání kódu se na LCD displeji zobrazí aktuální datum a na segmentovém displeji čas.

Schéma zapojení segmentového displeje:
Odkaz na schéma zapojení

Použité součástky:

Arduino UNO R3
4-místný sedmisegmentový displej H5410561K-32
16x2 LCD displej 1602 + I2C převodník (v budoucnu bude nahrazen OLED displejem)

Foto součástek a součásného stavu :
![image](https://github.com/user-attachments/assets/a8477ec6-502a-4dfa-af0c-9eefacdf91a0)

Inspirace a motivace:

Inspiroval jsem se meteo stanicí, kterou vlastním doma. I když práce s mikrokontroléry není mým hlavním zaměřením, rozhodl jsem se tento projekt realizovat, protože mě zaujala možnost přizpůsobit si vlastní „meteostanici“. Rád bych tímto poděkoval svému tátovi za podporu a pomoc při navrhování vzhledu stanice.

Plány na vylepšení:

V druhém pololetí bych chtěl projekt vylepšit. Plánuji přidat teploměrový modul, který bude měřit teplotu, a podsvícení, které bude ovládáno tlačítkem. Zvažuju, zda použít diody nebo LED pásky pro efektivní podsvícení. Také bych rád vyměnil segmentový displej za OLED displej pro lepší viditelnost a estetiku. Projekt je zatím v rozpracované fázi a budu na něm dále pracovat, přidávat nové funkce a vylepšení.

Seznam použitých zdrojů:

YouTube, online. Dostupné z: https://www.youtube.com/. [cit. 2024-12-18].
Arduino Fórum, online. Dostupné z: https://forum.arduino.cc/t/displaying-date-and-time-on-lcd-in-setup-using-for-loop-to-make-time-tick/471731. [cit. 2024-12-18].
