# Introducción {#intro}


Podríamos definir la *Bioestadística* como una disciplina científica que se encarga de la aplicación del análisis estadístico a diferentes cuestiones vinculadas a la biología principalmente.   
Las aplicaciones de la Bioestadística, son en varias campos como en el sector de la epidemiología, la bioestadística permite el modelamiento estadístico de una epidemia, en qué lugares está resultando más eficaz la prevención o hacia dónde hay que enviar más recursos para revertir una tendencia negativa.

La ecología también puede hacer uso de la bioestadística para registrar niveles de contaminación y otros indicadores que inciden de manera directa en la vida de las personas, los animales, las plantas y el resto de los seres vivos.

La estadística descriptiva es el primer paso de acercarse

## Conceptos básicos
Para el análisis de un estudio estadístico se hace necesario:  
**Planteamiento del problema**: Consiste en definir el objetivo de la investigación y precisar el
universo o población.
Base de Datos: consiste en recolectar los datos necesarios relacionados al problema de
investigación. 
**Análisis descriptivo**: Consiste en describir a la población de estudio y extraer la información
relevante en el estudio, a través de las medidas estadísticas, gráficos etc., con los datos disponibles
para extraer la información relevante en el estudio.  
**Inferencia estadística**: Consiste en deducir características de la población de estudio con base al
análisis de un subconjunto representativo (muestra). Es decir, se pretende tomar como generales
propiedades que sólo se han verificado para casos particulares. En otro contexto, consiste en
suponer un modelo para toda la población partiendo de los datos analizados para obtener
conclusiones generales  
## Medidas Estadísticas
Las medidas estadísticas se dividen en:  
-Medidas de tendencia central  
-Medidas de variación  
-Medidas de dispersión  
-Medidas de forma  
## Representación de datos   

La representación de la información se puede hacer para datos agrupados y no agrupados



```r
par(mar = c(4, 4, .1, .1))
plot(pressure, type = 'b', pch = 19)
```

<div class="figure" style="text-align: center">
<img src="01-intro_files/figure-html/nice-fig-1.png" alt="Figura de salida" width="80%" />
<p class="caption">(\#fig:nice-fig)Figura de salida</p>
</div>




```r
knitr::kable(
  head(iris, 20), caption = 'Esto es una tabal',
  booktabs = TRUE
)
```



Table: (\#tab:nice-tab)Esto es una tabal

| Sepal.Length| Sepal.Width| Petal.Length| Petal.Width|Species |
|------------:|-----------:|------------:|-----------:|:-------|
|          5.1|         3.5|          1.4|         0.2|setosa  |
|          4.9|         3.0|          1.4|         0.2|setosa  |
|          4.7|         3.2|          1.3|         0.2|setosa  |
|          4.6|         3.1|          1.5|         0.2|setosa  |
|          5.0|         3.6|          1.4|         0.2|setosa  |
|          5.4|         3.9|          1.7|         0.4|setosa  |
|          4.6|         3.4|          1.4|         0.3|setosa  |
|          5.0|         3.4|          1.5|         0.2|setosa  |
|          4.4|         2.9|          1.4|         0.2|setosa  |
|          4.9|         3.1|          1.5|         0.1|setosa  |
|          5.4|         3.7|          1.5|         0.2|setosa  |
|          4.8|         3.4|          1.6|         0.2|setosa  |
|          4.8|         3.0|          1.4|         0.1|setosa  |
|          4.3|         3.0|          1.1|         0.1|setosa  |
|          5.8|         4.0|          1.2|         0.2|setosa  |
|          5.7|         4.4|          1.5|         0.4|setosa  |
|          5.4|         3.9|          1.3|         0.4|setosa  |
|          5.1|         3.5|          1.4|         0.3|setosa  |
|          5.7|         3.8|          1.7|         0.3|setosa  |
|          5.1|         3.8|          1.5|         0.3|setosa  |


