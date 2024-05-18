# Motor ovládaný přes Arduino a Dual H most
Mým plánem je, využít vytvořený motor plus již pořízený motor, na kterých budou přidělaná kola která se budou dát rychlostně regulovat, a to každé zvlášť.(Cílový úkol projektu ještě domyslím)

# Schéma zapojení bez napájení
![image](https://github.com/Jahnic35/JahnaO2/assets/154455998/a731dbcd-69c5-46b2-b231-a5fbf07d5ee9)
 Obrázek vzatý z tohoto odkazu https://www.hackster.io/ryanchan/how-to-use-the-l298n-motor-driver-b124c5 

Schéma ukazuje ovládání směru motoru a rychlost motoru, které jsou v mém případě nahrazeny po domácku vyrobeným motorem.

# Po domácku vyrobený motor 

* Nápad je vzatý z videa na instagramu, které se mi již nepodařilo najít

Motor je dělaný jednoduše z plastu a mědi, kterou jsem obmotal okolo 1. dílu a tím vytvořím rotor, na kraj 1. dílu dám kousky měděné trubky.
Na kraj do 2. dílu dám magnety z obou stran pro vytvoření rotace. Motor by měl po připojení k arduinu fungovat.(schéma motoru dodám)

# Foto z prvních testů
![IMG_20240517_174347](https://github.com/Jahnic35/JahnaO2/assets/154455998/2c4a8e30-166c-43d1-b3ee-a9f6f61d1101)
![IMG_20240517_174337](https://github.com/Jahnic35/JahnaO2/assets/154455998/c99dad12-6c49-442e-825c-e83013fafd20)

Jak je vidět, mám jen jeden motor, který ale funguje přesně jak potřebuji. Druhý motor je dočasně nahrazen led diodami, podle kterých vidím, jak motor mění směr.
Bohužel se mi podařilo zničit l298n motor driver, který ovládal motory, při zkoušení složitějších zapojeních z ničeho nic přestal reagovat a posílat signály, budu ho muset nahradit buď novým nebo mnou vymyšleným.
Aspoň ještě dodám kód který jsem používal ještě před selháním ovládání.

# Kód k projektu (nehotový) 
![image](https://github.com/Jahnic35/JahnaO2/assets/154455998/80f98c9b-8c99-4c63-ba2c-ef71a3ea0a8d)
![image](https://github.com/Jahnic35/JahnaO2/assets/154455998/a644d350-ca62-442a-bb33-10344036789f)
![image](https://github.com/Jahnic35/JahnaO2/assets/154455998/5502a751-72c5-4efc-8447-26d8b37ef608)

# Poznámka
Hotový projekt se pokusím dodat co nejdříve. Mám v plánu na něm ještě dost pracovat a když všechno půjde jak má tak krádce po praxích vám ho dodám.
