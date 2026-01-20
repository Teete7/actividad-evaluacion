COMANDOS USADOS:

cd Desktop/actividad-evaluacion

git init

git config user.email

git config user.name

touch index.html

touch secreto.txt

cd .git

touch .gitignore

echo "secreto.txt" >> .gitignore

echo "README.txt" >> .gitignore

cd ..

git add index.html

git status

git commit

git checkout -b incluir-estilos

touch estilos.css

git add estilos.css

git add index.html

git status

git commit

git log --oneline

git checkout main

git log --oneline

git checkout incluir-estilos

git status

git commit

git checkout main

git remote add origin https://github.com/Teete7/actividad-evaluacion.git

git push origin main

git branch --set-upstream-to=origin/main main

git status

git pull origin main

git add README.md

git commit

git push origin main

1. ¿Para qué sirve el comando git init?¿Qué carpeta oculta se crea automáticamente para rastrear los cambios?.

Sirve para inicializar un repositorio de git, Se crea una carpeta oculta .git

2. ¿Qué comando has usado para confirmar que tu identidad es la correcta antes de empezar?

git config user.name
git config user.email

1. ¿Por qué es importante el uso de .gitignore en proyectos profesionales?

Yo pienso que es importante para no subir todos los archivos que tengamos que no sean necesarios subir a github

2. Si un archivo está "preparado" (staged), ¿en qué área de Git se encuentra y cuál es el comando para ver esta diferencia antes de confirmar?.

Se encuentra en la segunda area o area de preparacion, y el comando verlo es git status.

1. ¿Qué ocurre con los archivos de tu carpeta local cuando saltas de una rama a otra?

Se ven solo los archivos que esten en esa rama

2. ¿Cuál es la principal ventaja de trabajar con ramas independientes en lugar de hacer todo en la rama main?.

Que puedes hacer pruebas y demas sin afectar a la rama main.

1. Al clonar un repositorio, ¿qué nombre recibe por defecto el servidor remoto en nuestra configuración local?.

origin

2. ¿Qué comando usarías para ver la URL del servidor remoto que acabas de configurar?

git remote -v

1. ¿Qué comandos has utilizado para comprobar si el repositorio local está actualizado?
   git status

2. ¿Cuál es la diferencia fundamental entre ejecutar un git fetch y git pull según lo que acabas de experimentar?.

es como una especie de git add, es como para verificar los cambios. Y git pull directamente fusiona las ramas.

Indica los tres comandos que más te ha costado entender y explica por qué.

Los que mas me ha costado entender son:

git branch --set-upstream-to=origin/main main: este no lo entendia ya que no sabia que existia

git fetch: este no lo entendia ya que al no hacer nada en la linea de comandos no entendia bien pero despues ya vi que hacia
