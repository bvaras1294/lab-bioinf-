## Informe bioinformatica ##

**Laboratorio 01** Bases de datos biológicas 

### parte 1: Enfermedades genéticas y genes  ###

#### Huntington Disease ####

La enfermedad de Huntintgton (HD) es una enfermedad hereditaria que causa la descomposición progresiva de las celulas nerviosas del cerebro. las personas nacen con el gen defectuoso, pero los síntomas no aparecen hasta la edad madura. Este trastorno genético neurodegenerativo es fatal, afecta la coordinación muscular, conduce al deterioro cognitivo y fisico. Los primeros signos y síntomas pueden incluir movimientos involuntarios, depresión, mala coordinación, problemas para aprender informacón nueva entre otros que van aumentando gradualmente a medida que avanza la enfermedad.

**¿Que gen ha sido relacionado con esta enfermedad?**
Es el gen HTT que codifica a la proteína huntingtina

**¿tiene nombres alternativos el gen?**
IT15, HD GENE, LOMARES (según OMIM y ncbi)

**¿En qué cromosoma está? ¿cuántos exones tiene?**
Locus en el cromosoma 4p16.3 (segun OMIM y ncbi), recuento de exones 67 (segun ncbi) 

**¿Qué tipo de proteina es codificada por este gen? ¿Cuál es su número EC?**
EL gen codifica para la proteína huntingtina, la cual es una proteína nuclear. No es una enzima por tanto no tiene numero de EC.

**¿Qué genes están inmediatamente río arriba/abajo?** 
RIO ARRIBA E ENCUENTRAN LOS GENES :  regulator of G protein signaling 12, GRK4 G protein-coupled receptor kinase 4, RNU6-204P RNA, U6 small nuclear 204, pseudogene, MSANTD1 Myb/SANT DNA binding domain containing 1, LOC100286945 X antigen family member 3 pseudogene
RIO ABAJO SE ENCUENTRAN LOS GENES: NOP14 NOP14 nucleolar protein, RPL7AP29 ribosomal protein L7a pseudogene 29, HTT-AS HTT antisense RNA (head to head), RNU7-33P RNA, U7 small nuclear 33 pseudogene

**¿Cuál es la longitud de tu gen?**
Segun la referencia en ncbi [Ambrose et al. (1994)] encontraron que el gen HTT abarca 180 kb.

**¿Cuántas variantes de tu gen hay descritas y en qué posiciones?**
91 variantes descritas 

**¿Existen ortólogos de tu gen en otras especies? ¿Cuántos?**
223 organismos tienen ortólogos con el gen humano HTT

**¿Y paralógos? ¿Hay pseudogenes? ¿Cuántos? **
No se encuentran paralógos ni pseudogenes en la base de datos ncbi

### Parte 2: Rutas y procesos metabólicos ###

**Anteriormente encontraste nombres alternativos de tu gen ¿Existen otros reportados por Kegg? ¿Cuáles?**
No se encuentran nombres alternativos diferentes a los descritos en la base de datos ncbi (HTT, HD, IT15, LOMARS) 

**¿En qué rutas metabólicas participa la proteína codificada por tu gen?**

![](http://https://github.com/bvaras1294/lab-bioinf-/blob/master/ruta%20metabolica.png?raw=true)

**¿Cuál es el número de identificación de tu gen (entry number)?**
3064

**En qué otras rutas metabólicas está involucrado tu gen?**

![](http://https://github.com/bvaras1294/lab-bioinf-/blob/master/ruta%20htt.png?raw=true)


**¿Qué significan los cuadros verdes en el diagrama?**
Indica la presencia de genes en el genoma y la integridad de la ruta.

**¿Cuántos "dominios" forman la anotación GO?**

** GO:0006096 ¿A qué corresponde este término y qué información te entrega la página?**
proceso glucolítico, adhesión, nombre ontología sinonimos id alternativos, definición, relacionados, anotaciones graficos etc…

**Haz clic en "Graph Views" y examina el gráfico. Anota 10 sub-categorías GO a la cual GO:0006096 pertenece.**
-Generacion de ATP a partir de ATP
-proceso metabolico del ADN 
-fosforilacion nucletidica
-proceso biosintetico de ATP 
-proceso biosintetico de piruvato 
-proceso metabolico de ATP
-proceso metabolico del piruvato 
-proceso metabolico cofactor 
-genaracion de metabolitos precursores 
-proceso biosintetico celular 


### Parte 3: Descargando secuencias, convirtiendo formatos ###

**¿Cuántos items fueron encontrados? ¿cuántos en animales?**
70748 items 13419 en animales 

**Probablemente tus resultados fueron una mezcla de fragmentos de genes, regiones codificantes parciales, genes completos, etc. Filtra tus datos por mRNA, animales, RefSeq. Haz clic en la entrada para la secuencia de GAPDH de gallina ¿Cuál es la longitud del gen?**
1288 bp

**¿Cuál es la referencia bibliográfica más reciente? **
REFERENCIA 1 (bases 1 a 1288)
  AUTORES Ren X, Zhang L, Gao Y, Gao H, Wang Y, Liu C, Cui H, Zhang Y, Jiang
            L, Qi X y Wang X.
  TÍTULO Unión de pollo Anx2 es beneficioso para la infección con infecciones
            virus de la enfermedad bursal
  JOURNAL Virus Res. 210, 232-240 (2015)

**¿Cuál es el número de acceso?**
374193

**Secuencia en formato fasta **
NM_204305.1 Gliceraldehído-3-fosfato deshidrogenasa de Galo (GAPDH), ARNm
ACCTTCTCACTGCGCGCTGGGGCCGTTGACGTGCAGCAGGAACACTATAAAGGCGAGATGGTGAAAGTCG
GAGTCAACGGATTTGGCCGTATTGGCCGCCTGGTCACCAGGGCTGCCGTCCTCTCTGGCAAAGTCCAAGT
GGTGGCCATCAATGATCCCTTCATCGATCTGAACTACATGGTTTACATGTTCAAATATGATTCTACACAC
GGACACTTCAAGGGCACTGTCAAGGCTGAGAACGGGAAACTTGTGATCAATGGGCACGCCATCACTATCT
TCCAGGAGCGTGACCCCAGCAACATCAAATGGGCAGATGCAGGTGCTGAGTATGTTGTGGAGTCCACTGG
TGTCTTCACCACCATGGAGAAGGCTGGGGCTCATCTGAAGGGTGGTGCTAAGCGTGTTATCATCTCAGCT
CCCTCAGCTGATGCCCCCATGTTTGTGATGGGTGTCAACCATGAGAAATATGACAAGTCCCTGAAAATTG
TCAGCAATGCATCGTGCACCACCAACTGCCTGGCACCCTTGGCCAAGGTCATCCATGACAACTTTGGCAT
TGTGGAGGGTCTTATGACCACTGTCCATGCCATCACAGCCACACAGAAGACGGTGGATGGCCCCTCTGGG
AAGCTGTGGAGAGATGGCAGAGGTGCTGCCCAGAACATCATCCCAGCGTCCACTGGGGCTGCTAAGGCTG
TGGGGAAAGTCATCCCTGAGCTGAATGGGAAGCTTACTGGAATGGCTTTCCGTGTGCCAACCCCCAATGT
CTCTGTTGTTGACCTGACCTGCCGTCTGGAGAAACCAGCCAAGTATGATGATATCAAGAGGGTAGTGAAG
GCTGCTGCTGATGGGCCCCTGAAGGGCATCCTAGGATACACAGAGGACCAGGTTGTCTCCTGTGACTTCA
ATGGTGACAGCCATTCCTCCACCTTTGATGCGGGTGCTGGCATTGCACTGAATGACCATTTCGTCAAGCT
TGTTTCCTGGTATGACAATGAGTTTGGATACAGCAACCGTGTTGTGGACTTGATGGTCCACATGGCATCC
AAGGAGTGAGCCAGGCACACAGCCCCCCTGCTGCCTAGGGAAGCAGGACCCTTTGTTGGAGCCCCTGCTC
TTCACCACCGCTCAGTTCTGCATCCTGCAGTGAGAGGCCAGTTCTGTTCCCTTCTGTCTCCCCCACTCCT
CCAATTTCTTCCTCCACCTGGGGGAGGTGGGAGAGGCTGATAGAAACTGATCTGTTTGTGTACCACCTTA
CATCAATAAAAGTGTTCACCATCTGAAG

![](http://https://github.com/bvaras1294/lab-bioinf-/blob/master/fasta.png?raw=true)

**Uno de los formatos más usados es el FASTA, sin embargo en filogenética uno súper popular y requerido por muchos programas es el formato NEXUS.**
 #NEXUS
[TITLE: Written by EMBOSS 21/03/18]

begin data;
dimensions ntax=1 nchar=1288;
format interleave datatype=DNA missing=N gap=-;

matrix
NM_204305.1          ACCTTCTCACTGCGCGCTGGGGCCGTTGACGTGCAGCAGGAACACTATAA

NM_204305.1          AGGCGAGATGGTGAAAGTCGGAGTCAACGGATTTGGCCGTATTGGCCGCC

NM_204305.1          TGGTCACCAGGGCTGCCGTCCTCTCTGGCAAAGTCCAAGTGGTGGCCATC

NM_204305.1          AATGATCCCTTCATCGATCTGAACTACATGGTTTACATGTTCAAATATGA

NM_204305.1          TTCTACACACGGACACTTCAAGGGCACTGTCAAGGCTGAGAACGGGAAAC

NM_204305.1          TTGTGATCAATGGGCACGCCATCACTATCTTCCAGGAGCGTGACCCCAGC

NM_204305.1          AACATCAAATGGGCAGATGCAGGTGCTGAGTATGTTGTGGAGTCCACTGG

NM_204305.1          TGTCTTCACCACCATGGAGAAGGCTGGGGCTCATCTGAAGGGTGGTGCTA

NM_204305.1          AGCGTGTTATCATCTCAGCTCCCTCAGCTGATGCCCCCATGTTTGTGATG

NM_204305.1          GGTGTCAACCATGAGAAATATGACAAGTCCCTGAAAATTGTCAGCAATGC

NM_204305.1          ATCGTGCACCACCAACTGCCTGGCACCCTTGGCCAAGGTCATCCATGACA

NM_204305.1          ACTTTGGCATTGTGGAGGGTCTTATGACCACTGTCCATGCCATCACAGCC

NM_204305.1          ACACAGAAGACGGTGGATGGCCCCTCTGGGAAGCTGTGGAGAGATGGCAG

NM_204305.1          AGGTGCTGCCCAGAACATCATCCCAGCGTCCACTGGGGCTGCTAAGGCTG

NM_204305.1          TGGGGAAAGTCATCCCTGAGCTGAATGGGAAGCTTACTGGAATGGCTTTC

NM_204305.1          CGTGTGCCAACCCCCAATGTCTCTGTTGTTGACCTGACCTGCCGTCTGGA

NM_204305.1          GAAACCAGCCAAGTATGATGATATCAAGAGGGTAGTGAAGGCTGCTGCTG

NM_204305.1          ATGGGCCCCTGAAGGGCATCCTAGGATACACAGAGGACCAGGTTGTCTCC

NM_204305.1          TGTGACTTCAATGGTGACAGCCATTCCTCCACCTTTGATGCGGGTGCTGG

NM_204305.1          CATTGCACTGAATGACCATTTCGTCAAGCTTGTTTCCTGGTATGACAATG

NM_204305.1          AGTTTGGATACAGCAACCGTGTTGTGGACTTGATGGTCCACATGGCATCC

NM_204305.1          AAGGAGTGAGCCAGGCACACAGCCCCCCTGCTGCCTAGGGAAGCAGGACC

NM_204305.1          CTTTGTTGGAGCCCCTGCTCTTCACCACCGCTCAGTTCTGCATCCTGCAG

NM_204305.1          TGAGAGGCCAGTTCTGTTCCCTTCTGTCTCCCCCACTCCTCCAATTTCTT

NM_204305.1          CCTCCACCTGGGGGAGGTGGGAGAGGCTGATAGAAACTGATCTGTTTGTG

NM_204305.1          TACCACCTTACATCAATAAAAGTGTTCACCATCTGAAG
;

end;
begin assumptions;
options deftype=unord;
end;
![](http://https://github.com/bvaras1294/lab-bioinf-/blob/master/nexus.png?raw=true)

### Parte 4: Buscando artículos científicos en linea ###

**Crea una cuenta gratuita en NCBI y Google Scholar.Escoge un área de investigación, e.g., bacterial genomics, human genetics, etc.Ahora crea una alerta de búsqueda en NCBI PubMed.**

![](http://https://github.com/bvaras1294/lab-bioinf-/blob/master/alerta%20ncbi.png?raw=true)

**Ahora vamos a la página de la revista Nature Genetics. El obejtivo es configurar una tabla de contenidos electrónica, i.e., que cada vez que la revista publique un número nuevo te llegue la tabla de contenidos de ese número a tu correo electrónico. Puedes encontrar el vínculo en la esquina superior derecha, E-alert.**

![](http://https://github.com/bvaras1294/lab-bioinf-/blob/master/registro%20nature.png?raw=true)


operadores de búsqueda en Google Scholar.
** busca Human Microbiome, Ahora usa comillas para realizar tu búsqueda "Human Microbiome"**
![](http://https://github.com/bvaras1294/lab-bioinf-/blob/master/human%20micr.png?raw=true)

![](http://https://github.com/bvaras1294/lab-bioinf-/blob/master/human%20comillas.png?raw=true)

**¿Son los resultados idénticos o no?**
Con ambas busquedas se obtienen los mismos resultados 

**utiliza "Human Microbiome *" ¿En qué cambiaron los resultados de la búsqueda?**
Se destaca una palabra extra al titulo buscado 

**Para buscar artículos científicos también es útil restringir los resultados de búsqueda a tipos de archivo. Prueba con "human microbiome" filetype:pdf**
*Describe tus resultados*
La mayoría de los resultados obtenidos se encuentran en formato pdf 

**Otro truco útil es usar signos - y +. Por ejemplo trata buscar "PCR amplification" +temperature, y luego "PCR amplification" -temperature**
*¿En qué cambian los resultados de la búsqueda?* 
Al poner + temperatura salen artículos donde se indica la temperatura y en el caso de poner – temperatura en los articulos cientificos obtenidos la temperatura no es relavante. 