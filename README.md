# Rocnikovy-projekt - Matěj Topinka T3A


Mým cílem projetku udělat DIY "Meteo-časovou" stanicí za pomocí mikrokontroleru Arduino UNO R3. Která prozatím ukazuje pouze čas a datum.

Pro umístění součástek jsem použil starou plastovou krabici od malého rozvaděče kvůli tomu že je má dostatek místa na případné úpravy. 
Do plastové krabice jsem tavnou pistolí přilepil displeje a pozapojoval. Po zapojení do usb a nahrání kodu se nastaví dnešní datum na lcd displeji a 
společne s čase na segmentovém displeji.

Schéma zapojení segmentového displeje : https://drive.google.com/file/d/1-3PZHfnvbcpjpSS8pFqTY1hVv5znygu3/view

Použité součástky: 
 - Arduino Uno R3
 - 4-místný sedmisegmentový displej H5410561K-32
 - 16x2 LCD displej 1602 + I2C převodník (bude nahrazen oled displejem)
 

Inspiroval jsem se Meteo stanicí kterou vlastním doma a celkem mě to zaujalo i když pracování s mikrokontrolery nemá
můj větší obdiv, i tak jsem se rozhodl že to bude nejlepší pro mě.
Tímhle bych chtěl poděkovat mému tátovi který mě do toho dokopal a pomohl mi s tím jak bude stanice vypadat.
V druhém pololetí bych chtěl stanici ještě vylepšit na základě teploměrového modulu se kterým budeme pracovat.
Dále pak podsvícení které bude ovládáno přes tlačítko ještě přemýšlím jestli to bude skrz didody nebo přes led pásky.
Místo segmentového displeje bych chtěl použít OLED displej pro lepší viditelnost.
Projekt je teprve rozpracovaný a budu na něm pokračovat dále a přidávat nové věci.


Youtube. Online. Dostupné z: https://www.youtube.com/. [cit. 2024-12-18].
Arduino. Online. Dostupné z: https://forum.arduino.cc/t/displaying-date-and-time-on-lcd-in-setup-using-for-loop-to-make-time-tick/471731. [cit. 2024-12-18].
