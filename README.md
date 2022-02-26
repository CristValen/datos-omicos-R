# datos-omicos-R

El síndrome de Turner es un trastorno de aneuploidía de cromosoma X, cuya etiologia sigue siendo desconocida,
este sindrome tiene amplios y diversos efectos sobre el fenotipo de los pacientes, como infertilidad, problemas
cardiacos, baja estatura. Es importante avanzar hacia el conocimiento de la etiologia del sindrome y los genes
que podrian estar involucrados.

El objetivo de este análisis es, a partir de los datos de expresión detectados por microarrays, extraer un listado
de genes diferencialmente expresados entre pacientes con síndrome de Turner cuyo cromosoma X es de herencia
paterna o materna, y comparar estos sujetos entre ellos como con muestras de sujetos control sin sindrome de
Turner, para obtener un listado de genes y determinar si la lista cuyos genes esnte sobrerrepresentados en las
listas.

El material biológico corresponde a un conjunto de datos de síndrome de Turner, cuyos datos de microarrays
fueron obtenidos de ARNm aislado en sangre. Las muestras corresponden a pacientes con TS cuyo cromosoma
X heredado es paterno (N = 6), TS cuyo cromosoma X heredado es materno (N = 6), además, una muestra
correspondiente a sujetos sanos XX (N = 6).

Las muestras de ARN total se aislaron de PBCM utilizando el mini kit Qiagen RNeasy (Qiagen), mientras
que el ARNc biotinilado se prepararon usando el kit de transcripción in vitro (Affymetrix) a partir de 2 ug
de ARN total. Las muestras fueron hibridadas con GeneChip Human U133 2.0 Plus (Affymetrix), y dichos
datos fueron leídos con GeneChip Scanner 3000, para almacenarse utilizando Expression Console Versión 1.1
(Affymetrix). Los archivos .CEL que contienen la anotación de genes destacados fueron descargados de la
página web Gene Expression Omnibus (GEO).
