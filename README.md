

Este es material del curso de introducción a  Big Data

## Installation

Algunas de las herramientas que usamos son

| tecnologia | Link 							|	 ¿Quien?					| ¿Para qué sirve?|
| :---:		 | :---: 							| :---: 										| :---: |	
| Docker 		| [docker](https://docker.com) 	|	Solomon Hykes								|  para instanciar nuevos proyectos  |
|haddop| [hadoop](https://hadoop.com)|Apache  | distribuir data mediante un algoritmo que es mapreduce





[haddop](https://haddop) es una solicion desarrollada por Apache que permite guardar contenido de manera distribuida


```bash
ls sirve para listar los archivos 
```

## Usage



```python
import foobar

foobar.pluralize('word') # returns 'words'
foobar.pluralize('goose') # returns 'geese'
foobar.singularize('phenomena') # returns 'phenomenon'
```

## Contributing
Este es el repo del maestro Benjamín


## License
[MIT](https://choosealicense.com/licenses/mit/)



```sql

 mysql -uroot -p
 show databases;
  use company;
 show tables;
 select * from employees;
```
```bash
docker exec -it mysql bash

```


```bash
docker stats 
docker ps 
```

### Redes con docker

```bash
docker network
```

### Install docker

```bash
sudo apt-get update && sudo apt-get install apt-transport-https ca-certificates curl gnupg-agent software-properties-common -y && curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add - && sudo apt-key fingerprint 0EBFCD88 && sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable" && sudo apt-get update && sudo apt-get install docker-ce docker-ce-cli containerd.io -y && sudo docker run hello-world

sudo curl -L "https://github.com/docker/compose/releases/download/1.23.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose && sudo chmod +x /usr/local/bin/docker-compose && docker-compose --version
```
# Glosario Big data

Glosario

|Concepto|¿Quién lo creo?|¿Cuándo?|Para qué sirve|Referencias
|:---:   |:---:          |:---:   |:---:         |:---:
|hadoop|  el ingeniero de software Doug Cutting |2004| describe en un documento técnicas para manejar grandes volúmenes de datos, desgranándolos en problemas cada vez más pequeños para hacerlos abordables.|(https://openwebinars.net/blog/que-es-hadoop/)
|ApacheFlume|Apache software fundation||es un servicio distribuido, fiable, y altamente disponible para recopilar, agregar, y mover eficientemente grandes cantidades de datos.|(https://bigdatadummy.com/2017/02/07/apache-flume/)
|MapReduce |Yahoo|2008| es un modelo de programación para dar soporte a la computación paralela sobre grandes colecciones de datos en grupos de computadoras|(https://es.wikipedia.org/wiki/MapReduce)
|Base de Daatos Estructuradas|Edgar Frank Codd|década de los setenta|	Base de datos que se puede percibir como un conjunto de tablas y se puede manipular según el modelo relacional de los datos|(https://www.ibm.com/support/knowledgecenter/es/SSFGJ4_7.6.0/com.ibm.mbs.doc/configur/r_ctr_db_structures.html)
|MongoDB |Geir Magnusson y Dwight Merriman.|11/02/2009|MongoDBes una base de datos orientada a documentos. Esto quiere decir que en lugar de guardar los datos en registros, guarda los datos en documentos. Estos documentos son almacenados en BSON, que es una representación binaria de JSON.|(https://www.mongodb.com/es/what-is-mongodb)
|Docker|Solomon Hykes|23/07/2013|puede usar los contenedores como máquinas virtuales extremadamente livianas y modulares. Además, obtiene flexibilidad con estos contenedores: puede crearlos, implementarlos, copiarlos y moverlos de un entorno a otro, lo cual le permite optimizar sus aplicaciones para la nube.|(https://www.redhat.com/es/topics/containers/what-is-docker)
|apache spark|Universidad de Berkeley|2008 |es un sistema de computación que se basa en Hadoop Map Reduce y que, principalmente, permite dividir o paralelizar el trabajo , ya que normalmente se instala en un clúster de máquina|(https://openwebinars.net/blog/que-es-apache-spark/)

