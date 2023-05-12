# spotify_clone

Exámen práctico para el puesto de Desarrollador Frontend - PID Electronics

## Creación de un repositorio

Primero que nada, es necesario tener _git_ instalado en el equipo.

Una vez que está instalado se crea un directorio en el que queramos trabajar:

```bash
mkdir spotify_clone
cd spotify_clone
```

Dentro de la carpeta de trabajo, es necesario inicializar el repositorio para el
control de versiones:

```bash
git init
```

Después, será necesario tener un repositorio en Github, por ejemplo.

Cuando lo tengamos, necesitaremos agregar un origen remoto con el comando
`git remote add <nombre> <url>`. Esto permite que podamos subir los
cambios que realicemos

En el caso de este proyecto:
```bash
git remote add origin https://github.com/VCAngel/spotify_clone.git
```

> En caso de que se tengan cambios existentes en un repositorio, podemos "traerlos" a nuestro repositorio local con ```git pull <remote> <rama remota>```

Una vez hecho esto, podemos realizar los cambios en el proyecto. Cuando hayamos terminado, necesitaremos agregarlos al seguimiento del control de versiones:

```bash
git add <archivos>
```

Y después será necesario realizar un *commit* para confirmar nuestros cambios realizados, y agregarlos a la línea de tiempo del proyecto. Por ejemplo:

```bash
# git commit -m <mensaje> -m <descripción>
git commit -m "refactor: Reestructura de index.html" -m "Se cambiaron las etiquetas genericas (div) por más específicas..."
```

Una vez que decidamos "subir" los avances que tengamos al repositorio usamos:
```bash
# git push <remote> <rama remota>
git push origin master
```