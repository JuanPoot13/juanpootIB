

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

