## ![logo](https://user-images.githubusercontent.com/12600107/131232938-61d4757d-58ee-4b27-baf7-6273ff568ad2.png)  V.Tracker




**Diplomatura en Big Data y Machine Learning contra COVID-19**

La evolución de la pandemia del SARS-CoV-2 produce nuevas variantes caracterizando las diferentes realidades epidemiológicas. En ese sentido poder detectar a tiempo los nuevos clados y sus mutaciones asociadas (Figura 1), en especial monitorear los cambios asociados a la proteína Spike del virus es una tarea rutinaria que se vuelve más compleja con el actual volumen de información generada cada día (Big data).  

En el presente repositorio se comparten cuatro scripts desarrollados en lenguaje python ejecutables en google colab. El conjunto de estos cuatro scripts forman la versión beta 1 del software VTraker (Virus Tracker). 

En que nos ayuda: Actualmente la busqueda y detección de posibles linajes emergentes es una tarea manual, y debe de proponerse en la página oficial (https://github.com/cov-lineages/pango-designation) donde un grupo de expertos decide si es posible asignarle un nombre basados en unas reglas sugeridas por ellos (https://www.pango.network/the-pango-nomenclature-system/statement-of-nomenclature-rules/). Los scripts desarrollados usan las reglas propuestas dando como producto final un posible linaje emergente a ser propuesto. 


![imagen_orson](https://user-images.githubusercontent.com/12600107/131230337-10c7b01c-aed3-4663-a1d9-f946156e3986.png)

                         Figura 1. Representación de cluster nuevos detectados y sus mutaciones asociadas. 




**Flujo de trabajo de V.Tracker**

![pseudocodigo_diplomado (1)](https://user-images.githubusercontent.com/12600107/131232717-52e2c9ef-3cdc-4248-a321-5758c0fd61d8.png)

                                     Figura 2. Diagrama de flujo de trabajo desarrollado



**Manual para el Usuario**

Para poder familiarizarse con los programa V.Tracker recomendamos usar los datos compartidos en la carpeta Data/
y descargar los arcivhos scripts de Code_colab/ .ipynb. En la carpeta Data/ seguir las instrucciones del archivo Data_Information.rmd.
para cada google colab.


**Limitaciones**

1. Actualmente el VTracker solo se encuentra disponible en formato Google colab.
2. El análisis filogenético es necesario generar a parte. 
3. Es necesario someterlo a más pruebas para comprobar su real rendimiento.

**Desarrollo Futuro**

1. Desarrollar el pipiline completo para usuarios Linux. 

**Dependencias**

Es necesario instalar estos programas para el correcto funcionamiento 

Iqtree2 - Para generar el análisis filogenético - (http://www.iqtree.org/)

Nextclade - Para realizar anotación de genomas - (https://clades.nextstrain.org/)

Treecluster - Para detectar los cluster en una filogenía - (https://github.com/niemasd/TreeCluster)

**Autores**

- Orson Mestanza
- Pierre Padilla
- Alejandro Lopez
- Edgar Aza
- Diana Tapia
