# comandos utilizados

** Andres Felipe Portilla Perez **

- git cofig --global --list
- git config --global user.name andresfp97
- git config --global user.email 123andresportilla@gmail.com
- git clone https://github.com/warllensteven/landing-page-calzado.gitt status
- git branch
- git branch formulario
- git checkout formulario
- git status
- git add .
- git commit -m
- git push origin formulario
- git pull origin desarrollo
- git status
- git add .
- git commit -m
- git push origin formulario
- git pull origin desarrollo

# comandos en github

- pull request
- merge request

* git cofig --global --list
* git config --global user.name andresfp97
* git config --global user.email 123andresportilla@gmail.com
* git clone https://github.com/warllensteven/landing-page-calzado.gitt status
* git branch
* git branch formulario
* git checkout formulario

## Acciones de Warllen Romero

### Creacion de repositorio

- Conexion a github

git remote add origin https://github.com/warllensteven/landing-page-calzado.git

### Primer commit (Estructura de proyecto)

- Comprobacion de enlace

git remote -v

- Comprobacion de archivos

git status

- Agregar archivos al commit

git add .

-Nombre del commit

git commit -m "Estructura inicial del proyecto"

- Push a la rama main

git push -u origin main

- Cambio a rama de funcionalidad

### Creacion de ramas

Tendremos la rama **Main** y la rama de **desarroll** la main sera la final y la de desarrollo de prueba,las demas ramas tendran nombre segun su funcionalidad

- Rama **master** renombrada a Rama **main**

git branch -m main

- Creacion rama de prueba **desarrollo**

git branch desarrollo

### Segundo commit

git status

git add .

git commit -m "Diseño y estructura de inicio terminado"

git push origin inicio

### Pull request de las funcionalidades a la rama de desarrollo

- Solicitamos la fusion de la rama de inicio y la rama de formulario

### Tercer commit

- En este commit conectamos los enlaces de a el formulario

git status

git add .

git commit -m "Conexion de enlaces"

git push origin inicio

### Merge de desarrollo a main

-Finalmente fusionamos la rama de desrrollo a la main, incluso este readme esta siendo escrito en desarrollo despues de hacer el merge, a continuacion los comandos del merge de desarrollo a main despues de agregar todas las funcionalidades sin errores a la rama desarrollo

git checkout main

git merge desarrollo
