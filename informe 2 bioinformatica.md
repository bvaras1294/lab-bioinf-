##Laboratorio 02- Alineamiento de secuencias 

#Parte 1: colectar genes homólogos#

**¿Que función cumple el gen SRY**

Este gen sin intrones codifica un factor de transcripción que es un miembro de la familia de proteínas de unión a ADN del grupo de alta movilidad (HMG). Esta proteína es el factor determinante de los testículos (TDF), que inicia la determinación del sexo masculino

**¿Cuantos genes ortólogos están anotados en esa base de datos?**

26 genes ortólogos a partir del gen SRY de humanos 

#Parte 2: Alineamiento múltiple#

**¿Qué es el EMBL-EBI?**

 Es un instituto europeo de bioinformática, esta página es internacional que pone a disposición de la comunidad científica los datos biológicos del mundo a través de una gama de servicios y herramientas. Además, realizan investigaciones básicas y proporcionan capacitación en bioinformática.
 
**¿Cuántos tipos de alineamiento múltiple se pueden realizar en EMBL-EBI?**
alineamiento múltiple de secuencias de proteínas, ADN, alineación de secuencias múltiples basadas en consistencia, alineación de secuencias múltiples muy grandes, medianas, de secuencias de UniProt 

**¿Cuál es el programa que ellos ofrecen que funciona mejor para secuencias de proteínas?**
segun EMBL el mejor programa que ofreces para secuencias de roteinas es muscle y uniprot 

**¿Qué otros tipos de herramientas ofrece EMBL-EBI?**
alineación de secuencia múltiple, detección de características de proteínas, reconocimiento de motivos de secuencia, búsqueda de similitud de secuencias, análisis de función de proteína, leer mapeo, enriquecimiento de similitud química, formateo, comparación de ontología, búsqueda en la base de datos, DNA back-translation, alineación de secuencia por ares, alineación local, alineación global, formateo de secuencia, cálculo de propiedades de las proteínas, cálculo de hidropatía proteica, traducción de ADN, entre otros. 

**¿cuál es el costo de abrir un gap?**

Según la herramienta MAFFT de EMBL-EBI el costo de abrir un gap es de 1.53

**¿Cuál es el costo de extender un gap?**

Según la herramienta MAFFT de EMBL-EBI el costo de extender un gap es de 0.123

**¿Cuál es la longitud total del alineamiento?**

1907 nucleótidos 

**¿Cuál es la especie cuyo gen SRY está más relacionado con el gen SRY de humanos?**
![](http://github.com/bvaras1294/lab-bioinf-/blob/master/TREE.png?raw=true)

el gen SRY más relacionado con el gen SRY de humanos es de la especie Pan troglodytes

**¿Cuál es el más lejano?**
Equus przewalskii

**¿Cuál es la especie cuyo gen SRY es más cercana a la del burro?**

Equus przewalskii

**¿Cómo esperas que sea el alineamiento si el costo de abrir un gap aumenta? ¿Y si disminuye?**
al aumentar el costo de abrir un gap no habran tantos en la alineacion, por el contrario si disminuye el costo de abrir un gap habran varios en la alineacion produciendo varias mutaciones a lo largo del alineamineto 

**¿Cómo esperas que sea el alineamiento si el costo de extender un gap aumenta? ¿Y si disminuye?**
si el costo de extender un gap aumenta no varia tanto la longitud del alineamiento ya que no habran tantos gaps y si disminuye habran mas gaps disminuyendo el alineamiento ya que habra una mutacion extendida.

***Prueba aumentando el costo de abrir gaps cambiando el valor de 1.53 a 2.0***
**¿Cuál fue el efecto de aumentar el costo de abrir un gap en la longitud total del alineamiento?**

aumenta la longitud del alineamiento del 1097 a 1957 nucleótidos ya que al abrir gaps hay variadas mutaciones entre los nucleotidos corriendo el alineamiento. 

**prueba lo mismo pero esta vez disminuyendo al mínimo el costo de extender un gap. Describe cómo cambia el alineamiento**
disminuye relativamente la logitud del alineamiento ya que al disminuir el costo de extender un gap solo hay una mutacion extendida entre los nucleotidos adyacentes en la alineacion. 

#Parte 3: Diseño de partidores#
**Pega en tu informe los partidores que el programa encontró**

Amplicon 1 codon_usage_table = mitochondrion_Chlorocebus_sabaeus :
CCGCCGTTCAACAAaayathccngc 5'->3' N 17 174 (aligned residues)
cagctgcgcaacagaatattcctgc >001 sry gene [Chlorocebus sabaeus] 
cagctgtgcaagagaatattcccgc >002 sry gene [Homo sapiens] 
cagctgtgcaacagaatattcccgc >003 sry gene [Pan troglodytes] 
cagctgcgcaacagaatattcctgc >004 sry gene [Macaca mulatta] 
.!..!.?!...?.!..!..!..?..
CAGCTGTGCAACAGaatattccygc codeh_corr c14f3118_intronless_cluster_01_N17
cagctgygcaasagaatattccygc relax_corr c14f3118_intronless_cluster_01_N17
cagctgygcaasagaatattccygc degen_corr c14f3118_intronless_cluster_01_N17

GGGTAGGTGGCCTAGTtgrtgytscat 5'->3' C 17 174 (aligned residues)
cggtaagtggcctaactggtgctgcat >001 sry gene [Chlorocebus sabaeus] 
cggtaagtggcctagctggtgctccat >002 sry gene [Homo sapiens] 
cggtaagtggcctagctggtgctccat >003 sry gene [Pan troglodytes] 
cggtaagtggcctaactggtgctgcat >004 sry gene [Macaca mulatta] 
!....!........?!..!..!.....
CGGTAAGTGGCCTAGCtggtgctscat codeh_corr c14f3118_intronless_cluster_01_C174
cggtaagtggcctarctggtgctscat relax_corr c14f3118_intronless_cluster_01_C174
cggtaagtggcctarctggtgctscat degen_corr c14f3118_intronless_cluster_01_C174


![](https://github.com/bvaras1294/lab-bioinf-/blob/master/primer.png?raw=true)
