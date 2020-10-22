# 2.2 Spring Boot Secure API

### Codigo de honor:
Debes seguir el Código de honor del ingeniero de sistemas para defender el estándar de integridad académica de la ECI:

* Tus respuestas a tareas, cuestionarios y exámenes deben ser tu propio trabajo (excepto para las tareas que permiten explícitamente la colaboración).

* No puedes compartir tus soluciones de tareas, cuestionarios o exámenes con otra persona a menos que el instructor lo permita explícitamente. Esto incluye cualquier cosa escrita por ti, como también cualquier solución oficial proporcionada por el docente o el monitor del curso.

* No puedes participar en otras actividades que mejorarán de manera deshonesta tus resultados o que mejorarán de manera deshonesta o dañarán los resultados de otras personas.

## Prerrequisitos

### Git

```
> git --version

git version 2.21.0.windows.1
```

### npm

```
> npm -version

6.14.4
```

## Descarga

Para descargar localmente el repositorio se utiliza el comando como sigue:
```
> git clone https://github.com/Diego23p/IETI_8.git
```

## Instalación

### Para el BackEnd (Consola en la carpeta principal)

```
> gradle bootRun
```

### Para FrontEnd (Consola en la  carpeta FrontEnd)

```
> npm install

> npm start
```

## Part 1: Implement the API

- Consumir el post con Token

![](/img/1.jpg)

- GET-Task en el path ```/api```

![](/img/2.jpg)

- POST-Task en el path ```/api```

![](/img/3.jpg)

## Part 2: Consume the API from ReactJS project

- Almanecar el token en Local Storage

![](/img/4.jpg)

### Ejecutar axios con conseña incorrecta

![](/img/5.jpg)

![](/img/6.jpg)

- No accede a la página principal:

![](/img/7.jpg)

### Ejecutar axios con conseña correcta

![](/img/8.jpg)

![](/img/9.jpg)

- Accede a la página principal y se muestra el Token en Local Storage:

![](/img/10.jpg)
