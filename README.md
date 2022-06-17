# hse22_project_kinetoplasts

## Информация об участниках группы

ФИО | Род для анализа | Ссылка на индивидуальный репозиторий
--- | --- | ---|
Виноградова Ульяна | Leishmania | https://github.com/ulvivl/hse22_project
Лоскутникова	Дарья | Leishmania | https://github.com/apieceofwork/bioinf22_hse_project
Сметанин	Антон | Trypanosoma | https://github.com/Stuksus/hse22_project
Мозговой 	Владислав | Leptomonas, Phytomonas, Perkinsela | https://github.com/Vladm0z/hse22_project
Пирогов	Слава | Leishmania  | https://github.com/messlav/hse22_project
Размыслович	Арина | Trypanosoma | https://github.com/Lavriz/hse22_project
Руденко	Анастасия | Leishmania  | https://github.com/ruanmik/hse22_project
Ревенко	Дарья | Porcisia, Trypanosoma, Leishmania | https://github.com/DariaRev/hse22_project
Шарафатдинов	Камиль | Nocardia | https://github.com/coteeq/hse22_project
Каледин	Андрей | Leishmania | https://github.com/kaledinandrew/hse22_project

## [Презентация группы](https://docs.google.com/presentation/d/1xopnTzpB2WuwI916H2pskDhn7zEh3zIMFKPOwN49O7w/edit?usp=sharing)

## [Colab ноутбук](https://colab.research.google.com/drive/1tjL7gKpNsz4kJhEtosaTa0HWuSCIol_K?usp=sharing)

В данном ноутбуке было сделано:
- Создание картинок для презентации;
- Подсчет длины генома и количества генов;
- Применение zhunt
- Аминокислотное выравнивание

В colab ноутбуке, который находится в папке src, происходил запуск команды protheinortho

## Таблица с обзором геномов

Род | Средний gc | Средная длина генома | Среднее кол-во генов | Среднее число z-dna | zh-score > 500
--- | --- | --- | ---|---|---|
Perkinsela | 47 | 9477801 | 5252 | 853862 | 1742
Phytomonas | 46,2 | 18129152 | 6451 | 2329561 | 8392
Leishmania | 59,102425 | 32780421 | 8195 | 275853.5 | 7535.75
Trypanosoma | 26,95 | 25378171 | 10994 | 78461 | 637.5
Porcisia | 56,0229 | 34958538 | 7891 | 258204 | 4946
Leptomonas | 56,6 | 30379903 | 10130 | 2995728 | 34665

## Heatmap

![image](https://user-images.githubusercontent.com/36156820/174144700-8f84158b-c158-48df-8818-8bbf2be8df09.png)

## Визуализация расположения ZDNA

Cluster 4 | Cluster 6
--- | ---|
![image](https://user-images.githubusercontent.com/36156820/174144959-ac03dd7d-895e-4ab9-8292-dfa64cdbde4b.png) | ![image](https://user-images.githubusercontent.com/36156820/174145296-6e42c5bb-29cb-45f1-a653-d421ffcf323f.png)
![image](https://user-images.githubusercontent.com/36156820/174145094-6e6dba8f-97cf-45c2-882a-d70904330ec6.png) | ![image](https://user-images.githubusercontent.com/36156820/174145328-f8c7cd70-6994-45b5-b382-b3c267452add.png)
![image](https://user-images.githubusercontent.com/36156820/174145122-ee298111-1093-4c6d-9b80-c4ad63770a62.png) | ![image](https://user-images.githubusercontent.com/36156820/174145342-cd5c0cb2-a7ed-48be-a972-a1086812e80e.png)
![image](https://user-images.githubusercontent.com/36156820/174145149-b1bc3eab-c7e5-414c-afd1-e66824a81450.png) | ![image](https://user-images.githubusercontent.com/36156820/174145363-710d6940-b02a-4393-a3c8-4d5c51e6c09c.png)
![image](https://user-images.githubusercontent.com/36156820/174145169-f1a0f389-b01b-4a01-b3c0-e9680e81e7e1.png) | ![image](https://user-images.githubusercontent.com/36156820/174145390-bd514737-903c-4253-a040-5f402e7cb5d5.png)
![image](https://user-images.githubusercontent.com/36156820/174145183-3dd45be2-f237-4aa2-89d0-4eb6bedef598.png) | ![image](https://user-images.githubusercontent.com/36156820/174145417-8c89a640-251a-401e-bf5f-16d8bba234ac.png)
![image](https://user-images.githubusercontent.com/36156820/174145211-41db0321-8215-46f4-920b-6feba11bfc52.png) | ![image](https://user-images.githubusercontent.com/36156820/174145433-c8d65797-76a6-4361-bc73-5eb42b79040d.png)
![image](https://user-images.githubusercontent.com/36156820/174145230-d51c85b5-e807-4456-8597-5d4d557e6b56.png) | ![image](https://user-images.githubusercontent.com/36156820/174145454-341d544d-3330-46f7-b787-75661a6c0cfc.png)

## Аминокислотное выравнивание

Кластер 4:
![image](https://user-images.githubusercontent.com/36156820/174146572-0c16122c-b26f-489b-960e-08bb61ca2fd5.jpg)

Кластер 6:
![image](https://user-images.githubusercontent.com/36156820/174146906-7298efa5-7193-4bd8-ba9a-2e429517e341.jpg)


## Таблица с информацией по кластерам

Номер кластера | Название вида | name | функция белка | расшировка | ccылка на источние 
---|---|---|---|---|---
0 | CCAP | KNH05442.1 | 26S protease regulatory subunit | maintenance of protein homeostasis | https://en.wikipedia.org/wiki/PSMD1
0 | Hart1 | CCW69737.1 | NaN | 
0 | braziliensis | XP_001561635.1 | putative 26S protease regulatory subunit | maintenance of protein homeostasis | https://en.wikipedia.org/wiki/PSMD1
0 | donovani | CBZ31293.1 | 26S protease regulatory subunit, putative | maintenance of protein homeostasis | https://en.wikipedia.org/wiki/PSMD1
0 | grayi | KEG15552.1 | 26S protease regulatory subunit | maintenance of protein homeostasis | https://en.wikipedia.org/wiki/PSMD1
0 | hertigi | KAG5511915.1 | hypothetical protein | определение функции затруднено | https://en.wikipedia.org/wiki/Hypothetical_protein
0 | martiniquensis | KAG5487729.1 | hypothetical protein | определение функции затруднено | https://en.wikipedia.org/wiki/Hypothetical_protein
0 | orientalis | KAG5488026.1 | hypothetical protein | определение функции затруднено | https://en.wikipedia.org/wiki/Hypothetical_protein
0 | pyrrhocoris | KPA73636.1 | putative 26S protease regulatory subunit putat... | maintenance of protein homeostasis | https://en.wikipedia.org/wiki/PSMD1
0 | theileri | ORC93342.1 | 26S protease regulatory subunit | maintenance of protein homeostasis | https://en.wikipedia.org/wiki/PSMD1
1 | CCAP | KNH06104.1 | Lariat debranching enzyme | Cleaves the 2'-5' phosphodiester linkage, may also participate in retrovirus replication | https://www.uniprot.org/uniprot/Q9UK59
1 | Hart1 | CCW68771.1 | NaN | 
1 | braziliensis | XP_001566065.1 | conserved hypothetical protein | функционально не охарактеризован | https://www.ncbi.nlm.nih.gov/pmc/articles/PMC524295/
1 | donovani | CBZ35449.1 | hypothetical protein, conserved | функционально не охарактеризован | https://www.ncbi.nlm.nih.gov/pmc/articles/PMC524295/
1 | grayi | KEG12492.1 | hypothetical protein | определение функции затруднено | https://en.wikipedia.org/wiki/Hypothetical_protein
1 | hertigi | KAG5500355.1 | hypothetical protein | определение функции затруднено | https://en.wikipedia.org/wiki/Hypothetical_protein
1 | martiniquensis | KAG5474262.1 | hypothetical protein | определение функции затруднено | https://en.wikipedia.org/wiki/Hypothetical_protein
1 | orientalis | KAG5474592.1 | hypothetical protein | определение функции затруднено | https://en.wikipedia.org/wiki/Hypothetical_protein
1 | pyrrhocoris | KPA85541.1 | hypothetical protein | определение функции затруднено | https://en.wikipedia.org/wiki/Hypothetical_protein
1 | theileri | ORC88660.1 | hypothetical protein | определение функции затруднено | https://en.wikipedia.org/wiki/Hypothetical_protein
2 | CCAP | KNH08020.1 | U3-containing small subunit processome complex... | Eukaryotic 18S rRNA processing is mediated by the small subunit (SSU) processome, a machine comprised of the U3 small nucleolar RNP | https://www.researchgate.net/publication/24244888_A_Novel_Small-Subunit_Processome_Assembly_Intermediate_That_Contains_the_U3_snoRNP_Nucleolin_RRP5_and_DBP4
2 | Hart1 | CCW70517.1 | NaN | 
2 | braziliensis | XP_001567380.2 | conserved hypothetical protein |функционально не охарактеризован | https://www.ncbi.nlm.nih.gov/pmc/articles/PMC524295/
2 | donovani | CBZ36748.1 | hypothetical protein, conserved |функционально не охарактеризован | https://www.ncbi.nlm.nih.gov/pmc/articles/PMC524295/
2 | grayi | KEG14961.1 | U3 small nucleolar RNA-associated protein 14 | 
2 | hertigi | KAG5496073.1 | hypothetical protein | определение функции затруднено | https://en.wikipedia.org/wiki/Hypothetical_protein
2 | martiniquensis | KAG5470408.1 | hypothetical protein | определение функции затруднено | https://en.wikipedia.org/wiki/Hypothetical_protein
2 | orientalis | KAG5469985.1 | hypothetical protein | определение функции затруднено | https://en.wikipedia.org/wiki/Hypothetical_protein
2 | pyrrhocoris | KPA84496.1 | hypothetical protein | определение функции затруднено | https://en.wikipedia.org/wiki/Hypothetical_protein
2 | theileri | ORC92570.1 | U3 small nucleolar RNA-associated protein 14 | 
3 | CCAP | KNH04732.1 | cyclin 11 | play multiple roles in cell cycle progression, cytokinesis and apoptosis | https://en.wikipedia.org/wiki/Cyclin
3 | Hart1 | CCW71535.1 | NaN | 
3 | braziliensis | XP_001564168.1 | putative synaptobrevin-type transport protein | It is proposed to provide specificity for the targeting and fusion of vesicles with the plasma membrane | https://www.ncbi.nlm.nih.gov/pmc/articles/PMC398073/
3 | donovani | CBZ33511.1 | synaptobrevin-type transport protein, putative | It is proposed to provide specificity for the targeting and fusion of vesicles with the plasma membrane | https://www.ncbi.nlm.nih.gov/pmc/articles/PMC398073/
3 | grayi | KEG10182.1 | synaptobrevin-type transport protein | It is proposed to provide specificity for the targeting and fusion of vesicles with the plasma membrane | https://www.ncbi.nlm.nih.gov/pmc/articles/PMC398073/
3 | hertigi | KAG5507014.1 | hypothetical protein | определение функции затруднено | https://en.wikipedia.org/wiki/Hypothetical_protein
3 | martiniquensis | KAG5480526.1 | hypothetical protein | определение функции затруднено | https://en.wikipedia.org/wiki/Hypothetical_protein
3 | orientalis | KAG5480855.1 | hypothetical protein | определение функции затруднено | https://en.wikipedia.org/wiki/Hypothetical_protein
3 | pyrrhocoris | KPA82658.1,KPA82659.1 | NaN | 
3 | theileri | ORC92492.1 | synaptobrevin-type transport protein | It is proposed to provide specificity for the targeting and fusion of vesicles with the plasma membrane | https://www.ncbi.nlm.nih.gov/pmc/articles/PMC398073/
4 | CCAP | KNH06491.1 | hypothetical protein | определение функции затруднено | https://en.wikipedia.org/wiki/Hypothetical_protein
4 | Hart1 | CCW67664.1 | NaN | 
4 | braziliensis | XP_001564114.1 | conserved hypothetical protein |функционально не охарактеризован | https://www.ncbi.nlm.nih.gov/pmc/articles/PMC524295/
4 | donovani | CBZ32277.1 | hypothetical protein, conserved |функционально не охарактеризован | https://www.ncbi.nlm.nih.gov/pmc/articles/PMC524295/
4 | grayi | KEG12255.1 | putative cell cycle sequence binding phosphopr... | parasital protein | https://www.wikidata.org/wiki/Q61495232
4 | hertigi | KAG5510073.1 | hypothetical protein | определение функции затруднено | https://en.wikipedia.org/wiki/Hypothetical_protein
4 | martiniquensis | KAG5484706.1 | hypothetical protein | определение функции затруднено | https://en.wikipedia.org/wiki/Hypothetical_protein
4 | orientalis | KAG5485313.1 | hypothetical protein | определение функции затруднено | https://en.wikipedia.org/wiki/Hypothetical_protein
4 | pyrrhocoris | KPA76900.1 | putative cell cycle sequence binding phosphopr... | parasital protein | https://www.wikidata.org/wiki/Q61495232
4 | theileri | ORC88610.1 | putative cell cycle sequence binding phosphopr... | parasital protein | https://www.wikidata.org/wiki/Q61495232
5 | CCAP | KNH07463.1 | ribonucleoprotein p18 mitochondrial precursor | multiple functions | https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2246611/#:~:text=The%20cytosolic%20precursor%20proteins%20are,of%20import%20mechanisms%20and%20machineries.
5 | Hart1 | CCW72037.1 | NaN | 
5 | braziliensis | XP_001563480.1,XP_001563481.1 | NaN | 
5 | donovani | CBZ32850.1 | ribonucleoprotein p18, mitochondrial precursor... | multiple functions | https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2246611/#:~:text=The%20cytosolic%20precursor%20proteins%20are,of%20import%20mechanisms%20and%20machineries.
5 | grayi | KEG05370.1 | ribonucleoprotein p18, mitochondrial precursor | multiple functions | https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2246611/#:~:text=The%20cytosolic%20precursor%20proteins%20are,of%20import%20mechanisms%20and%20machineries.
5 | hertigi | KAG5509062.1,KAG5509063.1 | NaN | 
5 | martiniquensis | KAG5482810.1,KAG5482811.1 | NaN | 
5 | orientalis | KAG5482989.1,KAG5482990.1 | NaN | 
5 | pyrrhocoris | KPA73308.1,KPA73309.1 | NaN | 
5 | theileri | ORC88075.1,ORC88076.1 | NaN | 
6 | CCAP | KNH05595.1 | spherulin 4-like cell surface protein | 
6 | Hart1 | CCW71706.1 | NaN | 
6 | braziliensis | XP_001563657.1 | conserved hypothetical protein |функционально не охарактеризован | https://www.ncbi.nlm.nih.gov/pmc/articles/PMC524295/
6 | donovani | CBZ33032.1 | hypothetical protein, conserved |функционально не охарактеризован | https://www.ncbi.nlm.nih.gov/pmc/articles/PMC524295/
6 | grayi | KEG11100.1 | hypothetical protein | определение функции затруднено | https://en.wikipedia.org/wiki/Hypothetical_protein
6 | hertigi | KAG5508760.1 | hypothetical protein | определение функции затруднено | https://en.wikipedia.org/wiki/Hypothetical_protein
6 | martiniquensis | KAG5481975.1 | hypothetical protein | определение функции затруднено | https://en.wikipedia.org/wiki/Hypothetical_protein
6 | orientalis | KAG5482334.1 | hypothetical protein | определение функции затруднено | https://en.wikipedia.org/wiki/Hypothetical_protein
6 | pyrrhocoris | KPA77835.1,KPA77836.1,KPA77837.1 | NaN | 
6 | theileri | ORC89945.1 | hypothetical protein | определение функции затруднено | https://en.wikipedia.org/wiki/Hypothetical_protein
7 | CCAP | KNH08129.1 | ribosomal DEAD box protein | regulator of ribosome assembly | https://pubmed.ncbi.nlm.nih.gov/31188443/
7 | Hart1 | CCW71332.1 | NaN | 
7 | braziliensis | XP_001561513.1 | putative eukaryotic initiation factor 4a | mediates the binding of mRNA to the ribosome | https://pubmed.ncbi.nlm.nih.gov/11333019/#:~:text=Abstract,(the%20DEAD%20box%20family).
7 | donovani | CBZ31166.1 | eukaryotic initiation factor 4a, putative | mediates the binding of mRNA to the ribosome | https://pubmed.ncbi.nlm.nih.gov/11333019/#:~:text=Abstract,(the%20DEAD%20box%20family).
7 | grayi | KEG14530.1 | putative eukaryotic initiation factor 4a | mediates the binding of mRNA to the ribosome | https://pubmed.ncbi.nlm.nih.gov/11333019/#:~:text=Abstract,(the%20DEAD%20box%20family).
7 | hertigi | KAG5512328.1,KAG5512329.1 | NaN | 
7 | martiniquensis | KAG5488146.1,KAG5488147.1 | NaN | 
7 | orientalis | KAG5488297.1,KAG5488298.1 | NaN | 
7 | pyrrhocoris | KPA73781.1,KPA73782.1 | NaN | 
7 | theileri | ORC91171.1 | putative eukaryotic initiation factor 4a | mediates the binding of mRNA to the ribosome | https://pubmed.ncbi.nlm.nih.gov/11333019/#:~:text=Abstract,(the%20DEAD%20box%20family).
8 | CCAP | KNH05944.1 | hypothetical protein | определение функции затруднено | https://en.wikipedia.org/wiki/Hypothetical_protein
8 | Hart1 | CCW71719.1 | NaN | 
8 | braziliensis | XP_001563636.1 | conserved hypothetical protein | функционально не охарактеризован | https://www.ncbi.nlm.nih.gov/pmc/articles/PMC524295/
8 | donovani | CBZ33012.1 | hypothetical protein, conserved | функционально не охарактеризован | https://www.ncbi.nlm.nih.gov/pmc/articles/PMC524295/
8 | grayi | KEG06617.1 | tRNA (guanine-N(1)-)-methyltransferase | enzyme that catalyzes the chemical reaction | https://en.wikipedia.org/wiki/TRNA_(guanine-N1-)-methyltransferase
8 | hertigi | KAG5508733.1 | hypothetical protein | определение функции затруднено | https://en.wikipedia.org/wiki/Hypothetical_protein
8 | martiniquensis | KAG5481954.1 | hypothetical protein | определение функции затруднено | https://en.wikipedia.org/wiki/Hypothetical_protein
8 | orientalis | KAG5482313.1 | hypothetical protein | определение функции затруднено | https://en.wikipedia.org/wiki/Hypothetical_protein
8 | pyrrhocoris | KPA77805.1,KPA77806.1 | NaN | 
8 | theileri | ORC83604.1 | hypothetical protein | определение функции затруднено | https://en.wikipedia.org/wiki/Hypothetical_protein
9 | CCAP | KNH02444.1 | protease Do-like 10 |  enzyme that catalyzes proteolysis | https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2576539/
9 | Hart1 | CCW70563.1 | NaN | 
9 | braziliensis | XP_001567428.1 | conserved hypothetical protein | функционально не охарактеризован | https://www.ncbi.nlm.nih.gov/pmc/articles/PMC524295/
9 | donovani | CBZ36798.1 | hypothetical protein, conserved | функционально не охарактеризован | https://www.ncbi.nlm.nih.gov/pmc/articles/PMC524295/
9 | grayi | KEG14749.1 | ammecr1 | The contiguous gene deletion syndrome is characterised by Alport syndrome (A), intellectual disability (M), midface hypoplasia (M), and elliptocytosis (E), as well as generalized hypoplasia and cardiac abnormalities. It is caused by a deletion in Xq22.3, comprising several genes including ammecr1 | https://en.wikipedia.org/wiki/AMMECR1
9 | hertigi | KAG5496122.1 | hypothetical protein | определение функции затруднено | https://en.wikipedia.org/wiki/Hypothetical_protein
9 | martiniquensis | KAG5470459.1 | hypothetical protein | определение функции затруднено | https://en.wikipedia.org/wiki/Hypothetical_protein
9 | orientalis | KAG5470033.1 | hypothetical protein | определение функции затруднено | https://en.wikipedia.org/wiki/Hypothetical_protein
9 | pyrrhocoris | KPA84565.1 | hypothetical protein | определение функции затруднено | https://en.wikipedia.org/wiki/Hypothetical_protein
9 | theileri | ORC88436.1 | ammecr1 | The contiguous gene deletion syndrome is characterised by Alport syndrome (A), intellectual disability (M), midface hypoplasia (M), and elliptocytosis (E), as well as generalized hypoplasia and cardiac abnormalities. It is caused by a deletion in Xq22.3, comprising several genes including ammecr1 | https://en.wikipedia.org/wiki/AMMECR1
