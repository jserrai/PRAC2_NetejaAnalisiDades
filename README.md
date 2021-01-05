# PRAC2 Neteja i Anàlisi de dadaes

PRAC2 - Tipologia i cicle de vida de de les dades UOC Màster en Ciència de Dades.

## Components del grup:
Jordi Serra i Paula Sobrevals

## Index

race-result-horse.csv - Dataset sobre els cavalls extret en format csv.

race-result-race.csv - Dataset sobre les curses extret en format csv.

practica2.Rmd - Codi en R del projecte.

practica2.html - Codi en html del projecte. El GitHub no el pot mostrar, cal descarregar-se'l i obrir-lo.

practica2.pdf - Pràctica RMarkdown passada a pdf.

PRAC2_NetejaiAnalisiDades_JordiSerra_PaulaSobrevals.pdf - PDF amb les respostes als enunciats.

Wiki del repositori - Descripció de la PRAC2, Bibliografia i components del grup.


___________________



## Descripció del dataset

Hem obtingut el dataset de la pàgina web suggerida: Kaggle (https://www.kaggle.com/lantanacamara/hong-kong-horse-racing?select=race-result-race.csv). 

El dataset és compost de dos taules, race-result-horse.csv i race-result-race.csv. Nosaltres hem ajuntat aquestes dues taules, utilitzant un merge() amb la columna de race_id que coincideix a totes dues taules, creant un únic dataset.
Aquest conté els resultats de les 1561 curses de cavalls fetes a Hong Kong entre el 14 de Setembre del 2014 i el 16 de Juliol de 2017. Així com, informació sobre els cavalls i genets que hi van participar i els seus entrenaments, com informació sobre les condicions de les curses.

Hem fet servir **R** per a dur a terme la Neteja i Anàlisi de dades.

![https://i.ytimg.com/vi/rbaqI4NttAU/maxresdefault.jpg](https://i.ytimg.com/vi/rbaqI4NttAU/maxresdefault.jpg) 

## Descripció del la pràctica

Primer hem descarregat el dataset i ens hem qüestionat una pregunta/problema a respondre: En aquesta pràctica pretenem crear un model per a predir els resultats de les carreres de cavalls, és a dir, pretenem respondre la següent pregunta: Qui serà el cavall guanyador a la següent carrera?
Per a respondre-ho, primer hem fet una neteja de les dades: hem determinat si tenien valors buits o extrems, on eren i què fer amb ells. Un cop fet això, hem buscat quines eren les variables que ens podrien ajudar més a aconseguir el nostre obsectiu, i les hem escolllit per a dur a terme els nostres analisis. En tercer lloc, hem comprovat la nromalitat i la homogeneïtat que tenien les nostres dades. I finalment, hem fet l'anàlisi: en aquest cas, els tres anàlisis que hem determinat han estat, correlació (pearson i anova), regressió i regressió amb PCA. Finalment hem visualitzat les dades.



## Bibliografia

> * Calvo M., Subirats L., Pérez D. (2019). Introducción a la limpieza y análisis de los datos. Editorial UOC.<br>
> * Megan Squire (2015). Clean Data. Packt Publishing Ltd <br>
> * Jiawei Han, Micheine Kamber, Jian Pei (2012). Data mining: concepts and techniques. Morgan Kaufmann.<br>
> * Jason W. Osborne (2010). Data Cleaning Basics: Best Practices in Dealing with Extreme Scores. Newborn and Infant Nursing Reviews; 10 (1): pp. 1527-3369. <br
> * Peter Dalgaard (2008). Introductory statistics with R. Springer Science & Business Media. <br
> * Wes McKinney (2012). Python for Data Analysis. O’Reilley Media, Inc. <br


