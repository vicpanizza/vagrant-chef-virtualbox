# Vagrant y Chef para Aprovisionar Entornos de Desarrollo

El proyecto busca demostrar el uso de Vagrant, Chef y Virtual Box para el aprovisionamiento rapido y estandar para entornos de desarrollo. 

Este proceso puede ser replicado para permitir la facil adopción de los estandares de entornos de desarrollo mediante la estandarización de los procesos de aprovisionamiento.

## Getting Started

Estas instrucciones ayudaran a obtener una copia del proyecto y ejecutarlo en el ambiente local.

El proyecto esta constituido de los siguientes archivos:

#### Archivos

```
/Vagrantfile: 
```

```
/cookbooks/tomcat/recipes/default.rb: 
```

```
/cookbooks/tomcat/recipes/directories.rb: 
```

#### Archivos


### Prerequisitos

Para poder iniciar, es necesario descargar e instalar los siguientes prerequisitos

```
1) git --> https://git-scm.com/downloads
```

```
2) Virtualbox --> https://www.virtualbox.org/wiki/Downloads
```

```
3) Vagrant --> https://www.vagrantup.com/downloads.html
```

### Instalación

Una vez descargados e instalados los prerequisitos, debemos seguir los siguientes pasos

```
git clone https://github.com/vicpanizza/vagrant-chef-solo.git
```


```
vagrant up
```
	

## Authors

* **Victor Panizza** - *Initial work* - [vicpanizza](https://github.com/vicpanizza)

See also the list of [contributors](https://github.com/vicpanizza/vagrant-chef-solo/graphs/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details