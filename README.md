# Contribute to Intello Idea
Flujo de trabajo para contribuir a los proyectos de Intello Idea.

**1.** Replique el repositorio remoto de Intello Idea en su cuenta individual.
Desde la pagina web del provedor del repositorio remoto, seleccione **_fork_**. 
Ahora podra ver este repositorio en su cuenta.


**2.** Clonar el repositorio para tenerlo localmente.
```
git clone <repository_url>
```


**3.** Sincronice el repositorio local con el remoto.
```
git fetch
git pull
```


**4.** Localmente, cree una rama para trabajar en una nueva tarea.
```
git branch task#<numero_de_tarea>
```


**5.** Seleccione la rama recien creada para trabajar sobre esta.
``` 
git checkout task#<numero_de_tarea>
```


**6.** Realizar el trabajo necesario


**7.** Adicione el trabajo realizado al versionamiento de _Git_ en la rama del repositorio local.
```
git add .
```


**8.** Haga **_commit_** localmente de todos los cambios realizados.
```
git commit -m "<mensaje_del_commit>"
```


**9.** Una la rama de trabajo con la rama principal de desarrollo en el repositorio **local**.
```
git merge <rama>
```


**10.** Haga un **_push_** para subir los cambios locales al repositorio que esta en su cuenta individual.
```
git push
```


**11.** Solicite un **_pull_** **_request_** desde el repositorio de su cuenta individual hacia el repositorio de Intello Idea.
Escribir en el comentario la descripcion de la tarea y su identificacion. "Task#<numero_de_tarea>"
Esta accion se realiza desde la pagina web del repositorio remoto.

