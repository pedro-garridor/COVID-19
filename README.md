# COVID-19

This repo contains information about COVID-19 evolution in Spain and the Region of Murcia.

**COVID-19.Rmd** is an R Markdown file containing the source code of the repo. When compiled, it will generate several graphs about the disease's evolution in Spain and the Region of Murcia.
Hence, Rmd knitting gives the following items:
* *COVID-19.html*: this file shows both the methodology and code employed.
* *Datos* folder: data files are downloaded here. These CSV files are gathered from [Datadista's GitHub](https://github.com/datadista/datasets/tree/master/COVID%2019), with information publised by the [Spanish Ministry of Health](https://www.mscbs.gob.es/profesionales/saludPublica/ccayes/alertasActual/nCov-China/situacionActual.htm) and [Carlos III Health Institute](https://covid19.isciii.es/).
* *Graficas* folder: graphs from the HTML are exported to this folder, with 1920x1080 px resolution.

> Global hospitalized data is available again as Madrid is giving cummulative results instead of prevalence. Preiously was not reported as an inconsistency was spotted between cummulative data and prevalence depending on the reporting region.

---

Este repositorio contiene información sobre la evolución del COVID-19 en España y en la Región de Murcia.

El archivo **COVID-19.Rmd** es un documento R Markdown que puede ejecutarse para generar diversas gráficas sobre le evoluión de la pandemia en España y en la Comunidad Autónoma de la Región de Murcia.
Así, la ejecución de este Rmd genera los siguientes elementos:
* Fichero *COVID-19.html*: en este archivo se puede visualizar la metodología y el código empleados en el proceso.
* Carpeta *Datos*: aquí se descargan los ficheros de datos actualizados en formato CSV desde el [Github de Datadista](https://github.com/datadista/datasets/tree/master/COVID%2019), con la información publicada por el [Ministerio de Sanidad](https://www.mscbs.gob.es/profesionales/saludPublica/ccayes/alertasActual/nCov-China/situacionActual.htm) y el [Instituto de Salud Carlos III](https://covid19.isciii.es/).
* *Graficas*: las gráficas del fichero HTML se exportan también a esta carpeta, con una resoluión de 1920x1080 px.

> El dato de hospitalizados vuelve a estar disponible, ya que Madrid da ahora resultados acumulados en lugar de prevalencia. Anteriormente no se informaba de este dato al detectar inconsistencias entre datos acumulados y prevalencia de las distintas comunidades autónomas.
