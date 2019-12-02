# contribute
Flujo de trabajo para contribuir a los proyectos de Intello Idea.

**1.** Clonar el repositorio para tenerlo localmente.
```
git clone <repository_url>
```

**2.** Seleccionar la rama principal de desarrollo.
```
git checkout <rama>
```

**3.** Actualizar el repositorio local.
```
git pull
```

**4.** Crear una rama para trabajar en una nueva tarea.
```
git branch task#<numero_de_tarea>
```

**5.** Seleccionar la rama recien creada para trabajar sobre esta.
``` 
git checkout task#<numero_de_tarea>
```

**6.** Realizar el trabajo necesario

**7.** Hacer **commit** al trabajo realizado.
```
git commit -m "<mensaje_del_commit>"
```

**8.** Actualizar el repositorio local.
```
git fetch
```

**9.** Unir localmente la rama de trabajo con la rama principal de desarrollo.
```
git merge <rama>
```

**10.** Actualizar el repositorio remoto con los cambios anteriores.
```
git push
```

**11.** Hacer un **pull** **request** desde la rama de la nueva tarea hacia la rama principal de desarrollo.
Escribir en el comentario del **pull** **request** la descripcion de la tarea y su identificacion. "Task#<numero_de_tarea>"
Esta accion se realiza desde la pagina web del repositorio remoto.

