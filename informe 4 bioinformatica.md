##Laboratorio 04- Filogenética Molecular 

#Filogenia#
La filogenia es una hipótesis evolutiva de un conjunto de secuencias. Es decir, evalúa las relaciones genealógicas y como estas secuencias han evolucionado en el tiempo llegando a su forma actual[1].

[1] [https://github.com/bioinf-biotec/clases_bioinf/blob/master/c04_2018.pdf](https://github.com/bioinf-biotec/clases_bioinf/blob/master/c04_2018.pdf)

**¿Qué cosas ofrece este portal?** 
Esta plataforma permite que de un grupo de secuencias moleculares se pueda reconstruir y analizar las relaciones filogenéticas entre ellas. Además, es posible utilizar varios programas bioinformáticos para así lograr construir un árbol filogenético a partir del conjunto de secuencias. 

**¿Para qué tipo de usuario está diseñado?**
La plataforma Phylogeny.fr está diseñada para usuarios que busquen hacer un análisis filogenético de secuencias. Otorga servicios para usuarios sin experiencia en filogenia y para usuarios aficionados a la filogenia que pueden utilizar la plataforma en un modo avanzado eligiendo sus programas favoritos y los pasos a seguir al momento de realizar un análisis filogenético. 
Es decir, es una plataforma dirigida a cualquier usuario que tenga un conjunto de secuencias moleculares y quiera analizar su filogenia sin importar a experiencia que este tenga. 
 
**Menciona 5 tipos de análisis que se pueden realizar en el portal**
*Phylogeny.fr ofrece ejecutar un análisis filogenético en tres modos principales:*  
1. *One click* que es un método completo donde ya están configurados los programas y pasos a seguir para realizar la filogenia.
2. *Modo avanzado* donde se pueden elegir los pasos a realizar.
3. Y existe el *modo a la carta* donde se pueden además ejecutar y probar más programas de alineación y filogenia.
4. Además, la plataforma ofrece distintos programas para analizar y buscar filogenias como por ejemplo:
*MrBayes* que busca filogenia bayesiana.
*FastDist / Protdist + BioNJ / Neighbor PHYLYP)* que analizan filogenias usando distancias.
*TNT* que analiza filogenia usando parsimonia.
*PhyML* que busca filogenias utilizando máxima verosimilitud.
    
 **¿A qué se refiere el paso de *Alignment curation* y para qué sirve?**
Alignment curation se refiere a un refinamiento de la alineación, sirve para mejorarla eliminando locis y secuencias en las cuales no haya suficiente información filogenetica.

**¿Cuál es la diferencia entre BioNJ y Neighbor?**
Ambos tienen la función de buscar filogenias usando distancias, se difieren su limitación ya que BioNJ tiene una limitación de <5000 taxones y Neighbor tiene una limitación de <500. 

**Se infieren dos filogenias**
-*Una con ProbCons, GBlocks, MrBayes, y TreeDyn*

- *Otra con ClustalW, "Remove positions with gaps", TNT, y TreeDyn*

![](https://github.com/bvaras1294/lab-bioinf-/blob/master/datos%20prob%20curado.png?raw=true)

![](https://github.com/bvaras1294/lab-bioinf-/blob/master/datos%20prob%20no%20curado.png?raw=true)

![](https://github.com/bvaras1294/lab-bioinf-/blob/master/datos%20clustalW%20no%20curado.png?raw=true)

![](https://github.com/bvaras1294/lab-bioinf-/blob/master/datos%20clustalW%20curado.png?raw=true)

**¿Qué pasa si se corre de nuevo las filogenias pero esta vez sin *Alignment curation*?. ¿Cuál es el efecto en las filogenias?**
Al analizar las filogenias sin Alignment curation tanto en las secuencias corridas por ProbCons y ClustalW se observa que hay mucho más ruido en la filogenia, hay secuencias inconsistentes con mucha falta de información filogenética. 
Se puede apreciar variación en el largo de las ramas indicando una mayor cantidad de cambios. El largo de las ramas en algunos casos se puede analizar como una relación de tiempo es decir como un reloj molecular significando que al ser más largas las ramas indicaría una distancia evolutiva más grande. Aumenta en número de nodos que indican ancestro, es decir que en las filogenias analizadas *sin alineamiento curado* aumenta la cantidad de ancestros en los datos otorgados. La mayoría de los grupos monofiléticos desaparecen por ejemplo en el alineamiento utilizando ClustalW y la filogenia por TNT utilizando el *alineamiento curado* se observa un grupo monofilético entre las especies *MINIOPTERUS NATALENSIS Y PTEROPUS ALECTO* que en el análisis filogenético *sin el alineamiento curado* se pierde y se alejan entre sí. En resumen al utilizar el *alineamiento curado* se entrega una información revisada y más confiable, se ordena la filogenia sin tanto ruido evolutivo ni discordancias entre las secuencias en comparación a las filogenias usadas *sin el alineamiento curado* donde se observa una mayor cantidad de ruidos, secuencias casi sin información filogenética y una mayor lejanía evolutiva entre especies anteriormente relacionadas.

![](https://github.com/bvaras1294/lab-bioinf-/blob/master/ProbCons%20no%20curada.png?raw=true)

![](https://github.com/bvaras1294/lab-bioinf-/blob/master/ProbCons%20curada.png?raw=true)

![](https://github.com/bvaras1294/lab-bioinf-/blob/master/clustalW%20curada.png?raw=true)

![](https://github.com/bvaras1294/lab-bioinf-/blob/master/ClustalW%20no%20curada.png?raw=true)