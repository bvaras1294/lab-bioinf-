##Laboratorio 05- Metagenómica 

#Metagenómica#
La metagenomica consiste en la aplicaciòn de tecnologìas de secuenciaciòn e identificacion de genes y protìnas a microorganismos no cultivados.  
`Francisco Castillo Rodrìguez. (2005). Biotecnologàa ambiental. editorial tebar. pagina 357. `
La ciencia de la metagenòmica engloba los trabajos destinados a extraer genes funcionales de diversos microbiomas.
`Mark Feldman, Lawrence S. Friedman, Lawrence J. Brandt. (2017). Sleisenger y Fordtran. Enfermedades digestivas y hepáticas + ExpertConsult: Fisiopatología, diagnóstico y tratamiento.Elsevier Health Sciences. Pagina 30. ` 


**¿Cuántas secuencias fueron subidas?**
Para *GS025 Shotgun - Fringing Reef - Eastern Tropical Pacific - Dirty Rock, Cocos Island - Costa Rica* en MG-RAST fueron subidas  120,671 secuencias.
![](https://github.com/bvaras1294/lab-bioinf-/blob/master/cannt%20sec.png?raw=true)
![](https://github.com/bvaras1294/lab-bioinf-/blob/master/cant%20secuencia.jpg?raw=true)
**¿Qué tipo de plataforma de secuenciamiento fue usada para producir estos datos?**
Los protocolos de secuenciación se basaron en el método de secuenciación di-desoxi. Las reacciones de secuenciación se completaron usando la química Big Dye Terminator y los cebadores estándar M13 directo e inverso. Se optimizaron las mezclas de reacción, los perfiles de ciclos térmicos y las condiciones de electroforesis para reducir el volumen de la mezcla Big Dye Terminator (Applied Biosystems) y extender las longitudes de lectura en los secuenciadores AB3730xl (Applied Biosystems). Las reacciones de secuenciación fueron establecidas por Biomek FX (Beckman Coulter) pipeteando estaciones de trabajo.
[https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1821060/](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1821060/)
**¿Cuántas secuencias pasaron el control de calidad? ¿A qué crees que se refiere esto?**
120,671 secuencias pasaron el control de calidad. La cantidad de secuencias subidas con las que pasaron el control de calidad son iguales esto pudo suceder debido a que los autores debieron haber realizado previamente un análisis a las secuencias.
![](https://github.com/bvaras1294/lab-bioinf-/blob/master/control%20calidad.jpg?raw=true) 
**¿Cuántos otros meta genomas están disponibles para el bioma “marine hábitat”?**
Se busca en MG-RAST el bioma hábitat marino y se obtienen 6,969 resultados para este filtro. 
![](https://github.com/bvaras1294/lab-bioinf-/blob/master/hbitat%20marino_LI.jpg?raw=true)
**¿Cuántas reads fueron asignadas a eucariontes según MG-RAST?**
Analizando el grafico de dominio en MG-RAST para *GS025 Shotgun - Fringing Reef - Eastern Tropical Pacific - Dirty Rock, Cocos Island - Costa Rica* en Eucariotas hay 9,207 secuencias expresadas en un 13,03%. 
![](https://github.com/bvaras1294/lab-bioinf-/blob/master/eucariota.png?raw=true)
**¿Cuál es el filo (Phylum) más abundante en la muestra?**
El filo más abundante según lo observado en el grafico es cyanobacteria con 22,956 secuencias equivalente a un 37,03% de los datos.
![](https://github.com/bvaras1294/lab-bioinf-/blob/master/cyanobacteria.png?raw=true)
**¿A cuántas secuencias se les asignó una función de acuerdo a la base de datos KEGG con un e-value entre -10 y -20?**
Según el grafico de barras observado en MG-RAST para la base de datos KEGG tiene 7,960 secuencias con un e-value entre -10 y -20. 
![](https://github.com/bvaras1294/lab-bioinf-/blob/master/e%20value.png?raw=true)
**¿Por qué hay tan pocas secuencias con funciones asignadas según SwissProt?**
SwissProt es una base de datos curada, es decir las secuencias están anotadas,  revisadas y no son redundantes. la información en esta base de datos es de alta calidad es por esto que la cantidad de secuencias es menos en comparación las demás bases de datos. 
**¿Cuántas secuencias mapearon en contra de Proteobacteria?**
SE utiliza la herramienta análisis que otorga MG-RAST se busca *GS025 Shotgun - Fringing Reef - Eastern Tropical Pacific - Dirty Rock, Cocos Island - Costa Rica* mediante su ID y se filtra la información para obtener los filos y se obtiene que para proteobacteria hay 24194 secuencias mapeadas. 
![](https://github.com/bvaras1294/lab-bioinf-/blob/master/proteobacteria.png?raw=true)
**¿Cuántas secuencias de Salmonella (Proteobacteria; Gammaproteobacteria; Enterobacteriales; Enterobacteriaceae) fueron identificadas? (Pista: level - genus)**
Con la misma herramienta de análisis se filtra en genero para obtener salmonella y se tiene que hay 72 secuencias identificadas para salmonella. 
![](https://github.com/bvaras1294/lab-bioinf-/blob/master/salmonella.png?raw=true)
