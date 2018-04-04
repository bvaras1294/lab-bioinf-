##Laboratorio 03- Ensamblaje de genomas y predicción de genes

#parte 1: El artículo genoma#

La vida está especificada por los genomas de todos los organismos que conforman el planeta. La mayoría de los genomas de formas de vida celular están compuestos por DNA, pero algunos como por ejemplo ciertos virus tienen genoma de RNA. Todo organismo tiene un genoma el cual contiene su información biológica, es decir el genoma constituye el conjunto de la información genética de un organismo así de esta forma se puede construir su estructura y establecer cada una de sus funciones, manteniendo así un ejemplo viviente de ese organismo [1],[2]. 

    [1] Terry Brown. (2008).Geomas. tercera edicion. Editorial medica panamericana. Pagina 3.
    [2] Gemma Rodríguez-Tarduchy. (2014). Hablamos de gen o mas?. Editorial Hélice. Pagina 1. 

Existen diferentes bases de datos con secuenciación de genomas y genomas completos, una de ellas es la base de datos GOLD (Genomes Online Database), otorga un recurso para el acceso integral a la información sobre los proyectos de secuenciación de genoma y metagenoma, y sus metadatos asociados, en todo el mundo.

**¿Cuántos genomas han sido depositados en GOLD?** 
Según la estadística de GOLD el 2017 se depositaron 4.640 proyectos de genomas completos y para el 20188 se han depositado a la fecha 240 proyectos de genomas completos. 
![](https://github.com/bvaras1294/lab-bioinf-/blob/master/estadistica%20GOLD%202017.png?raw=true)

![](http://github.com/bvaras1294/lab-bioinf-/blob/master/estadistica%20GOLD.png?raw=true)


**¿Son los mismos de GENBANK?**
En la base de datos de genbank hay una mayor cantidad de sencuencias publicadas a la fecha. 

![](https://github.com/bvaras1294/lab-bioinf-/blob/master/GENBANK%20estadistica.png?raw=true)

**¿Cuál es la distribución de procariontes y eucariontes secuenciados?**
Para la distribución de eucariontes según la base de datos GOLD, se aprecia un 2,8% equivalente a 9.570 secuencias de genomas completos. Mirando detalladamente en los estados de secuencias para eucariotas encontramos que hay 78,7% lo que equivale a 35.280 de secuencias de eucariontes completas, un 17,6 % de secuencias en progreso que equivalen a 7.910 y un 2,5% equivalente a 1.140 secuencias en borrador.

Dentro de la distribución de procariontes tenemos el grupo de Arqueas 
que contiene un 88,2% de secuencias de genomas completos y en cuanto a el estado de secuencias tenemos detalladamente que hay 82,5% equivalente a 1.441 secuencias completas, un 8,1% equivalente a 142 secuencias en progreso y a un 3,5% equivalente a 61 secuencias en borrador. 
Y el grupo de bacterias que presenta un 96,5% de genomas completos secuenciasdos mirando detalladamente los estados de estas secuencias se obtiene que hay un 87,3% equivalente a 92.132 secuencias completas, un 9% equivalente a 9.528 secuencias en progreso y un 2,9% equivalente a 3.074 secuencias en borrador. 

![](https://github.com/bvaras1294/lab-bioinf-/blob/master/distribucion%20en%20GOLD.png?raw=true)

![](https://github.com/bvaras1294/lab-bioinf-/blob/master/Estado%20de%20secuencias.png?raw=true)

*Navegando dentro del portal GOLD y en la sección de proyectos completos elegimos un genoma eucarionte de interés. Buscando en las referencias del organismo podemos encontrar el articulo original donde se secuencio el genoma y en materiales y métodos se describen las series de estadísticas que se usan para evaluar el ensamblaje de genomas*

**¿Qué es el N50, L50, NG50?** 
N50 se usa en genómica especialmente en referencia a las longitudes de coting o supercoting dentro de un ensamblaje.Define la calidad del ensamblaje, dado un conjunto de cotings la longitud de N50 se define como la longitud más corta a 50% del genoma.

L50 se define como el menor número de contigs cuya suma de longitud produce N50.

NG50  es idéntica a N50, excepto que se estima la longitud del genoma se define como igual a la media de la longitud del tamaño del genoma estimado.

[https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3227110/](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3227110/)

[https://en.wikipedia.org/wiki/N50,_L50,_and_related_statistics](https://en.wikipedia.org/wiki/N50,_L50,_and_related_statistics)
 
**¿Cuál es el propósito de calcular estas estadísticas?**
Estas métricas son utilizadas para evaluar los ensamblajes de genomas. dando por ejemplo la contigüidad del ensamblaje.

**¿Cuál es el genoma que escogiste? Adjunta la referencia.**
El genoma escogido es del organismo Musa acuminata (dwarf banana). El proyecto de secuencia del genoma de 523 megabases de un genotipo doble haploide de Musa acuminata, que proporciona un trampolín crucial para la mejora genética del banano.

![](https://github.com/bvaras1294/lab-bioinf-/blob/master/musa%20acuminata%20proyecto.png?raw=true)

[https://www.nature.com/articles/nature11241#s1](https://www.nature.com/articles/nature11241#s1)  
 
**¿Cuál es el N50 del genoma que escogiste? ¿Y el NG50?**
N50 es 28,3 y NG50 es 14,2.
![](https://github.com/bvaras1294/lab-bioinf-/blob/master/Estadistica%20general.png?raw=true)

**¿Qué tipo de tecnología se usó para secuenciar el genoma que escogiste?**
según materiales y métodos del artículo se utilizó la tecnología *Whole Genome Shotgun strategy combining Sanger, Roche/454 GSFLX and Illumina GAIIx technologies.* que en la traducción se denomina como Escopeta de Genoma Completo combinando tecnologías Sanger, Roche / 454 GSFLX e Illumina GAIIx.

![](https://github.com/bvaras1294/lab-bioinf-/blob/master/tecnologia%20secuencia.png?raw=true)

**¿Qué organismo escogiste, cuántos cromosomas tiene tu organismo y cuál es su tamaño?**
el organismo escogido es *Musa acuminata, banana enana*. tiene 11 cromosomas y su tamaño según el genoma secuenciado es de 472.2 Mb.
![](https://github.com/bvaras1294/lab-bioinf-/blob/master/Musa%20acuminata.png?raw=true)

##Parte 2:predicción de genes##

Se tiene una secuencia problema para analizar en ORF y en Glimmer 

**¿Cuántos ORF o genes encontró ORFfinder?**
ORFfinder encontró 35 ORF de la secuencia problema.  

![](https://github.com/bvaras1294/lab-bioinf-/blob/master/ORFfinder%20encontrados.png?raw=true)
![](https://github.com/bvaras1294/lab-bioinf-/blob/master/ORF.png?raw=true)
![](https://github.com/bvaras1294/lab-bioinf-/blob/master/ORF2.png?raw=true)
![](https://github.com/bvaras1294/lab-bioinf-/blob/master/ORF3.png?raw=true)
![](https://github.com/bvaras1294/lab-bioinf-/blob/master/ORF4.png?raw=true)

**¿Cuántos ORF o genes encontró Glimmer?**
Glimmer encontró 10 genes de la secuencia problema. 
![](https://github.com/bvaras1294/lab-bioinf-/blob/master/Glimmer.png?raw=true)

**¿Alguno de los genes predichos por estas herramientas coinciden?**
Coinciden perfectamente 3 genes ORF6 con G6, ORF16 con G7 y ORF10 con G10. 

**¿En qué hebra están codificados?**
en la hebra positiva 

**¿Qué tipo de programa es GLIMMER? ¿Ab initio o por homología?** Glimmer es un sistema para encontrar genes en el ADN microbiano. Glimmer es un programa de predicción de genes Ab initio. 

*Se realiza una búsqueda en BLAST para confirmar si los genes predichos existen en GENBANK*

Se buscan los genes poniendo las secuencias nucleotídicas de los genes predichos por Glimmer y ORFfinder. En los resultados otorgados por BLAST para ambas herramientas se encuentran que las secuencias, producen alineaciones significativas con distintas cepas de *Heamophilus influenzae* cada gen consultado tiene una identidad de 100% con alguna de las cepas de Heamophilus influenzae del genoma completo presente en GENBANK

![](https://github.com/bvaras1294/lab-bioinf-/blob/master/GENBANK%20de%20una%20cepa.png?raw=true)
