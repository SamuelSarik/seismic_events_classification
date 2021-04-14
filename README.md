# Automatic classification of seismic events using convolutional neural networks
Samuel Sarik, Viera Maslej Krešňáková and Peter Butka
# Funkcia programu
Tento program slúži na klasifikáciu zemetrasení a explózií analýzou seizmických meraní. Klasifikátor je založený na 2D konvolučnej neurónovej sieti. Ide o binárnu klasifikáciu do dvoch tried, ktorými sú zemetrasenia a explózie. Náš program obsahuje naučenú neurónovú sieť, ktorá je súčasťou riešenia úlohy.
# Inštalácia programu
Náš program nevyžaduje žiadnu inštaláciu. Na to, aby sme ho mohli spustiť, stačí rozbaliť súbory nachádzajúce sa v tomto repozitári do pracovného
adresára spolu s datasetmi a spustiť to v programe Pycharm alebo v Anaconde. Po nahraní nášho skriptu je nutné stiahnuť všetky potrebné balíky, ktoré sa využívajú počas behu programu. Zoznam všetkých balíkov je obsiahnutý v súbore packages.txt.
# Požiadavky na technické prostriedky
Náš program bol vyvíjaný na počítači s operačným systémom Windows 10 s 8GB RAM, procesorom Intel 4Core 3700 a integrovanou grafickou kartou Intel HD Graphics.
# Požiadavky na programové prostriedky
Pri spúšťaní nášho programu odporúčame mať nainštalované prostredie Pycharm, alebo iné, funkciami podobné prostredie, ktoré dokáže pracovať so súbormi typu .ipynb. My sme využívali Anacondu, a v nej integrované prostredie Spyder, ale aj Jupyter Notebook.
# Vlastná inštalácia
Pri spustení programu je potrebné rozbaliť súbory do pracovného adresára, kde sa nachádzajú aj dátové súbory v adresári \textbf{svmdat}. Adresár \textbf{svmdat} obsahuje 54 súborov so seizmickými signálmi. Ďalšia inštalácia nie je potrebná.
# Popis štruktúry programu
Zdrojový kód je obsiahnutý v súbore seismic_events_classification.ipynb. Je to súbor typu Jupyter Notebook, ktorý je charakteristický rozdelením kódu do blokov. Každý blok reprezentuje čiastkovú funkcionalitu celej úlohy. Obsah blokov je bližšie charakterizovaný v systémovej príručke v časti Popis algoritmov a údajových štruktúr, globálnych premenných.
# Popis správ pre systémového programátora
Počas behu programu sa v konzole vypisujú jednotlivé epochy v procese učenia učenia, presnosť modelu, kontingenčná tabuľka, classification report, confusion matrix, a sledované metriky: Miss Rate a Fall-out.
