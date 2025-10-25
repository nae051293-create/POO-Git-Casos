1. Configuración inicial
Antes de empezar, asegúrate de tener Git instalado.
Puedes verificarlo con:

git --version

Luego, configura tu nombre de usuario y correo (solo la primera vez):

git config --global user.name "Tu Nombre"
git config --global user.email "tuemail@dominio.com"

2. Crear un repositorio local

Para iniciar un nuevo proyecto en tu computadora:

mkdir POO-Git-Casos
cd POO-Git-Casos
git init

Esto crea una carpeta con control de versiones local.

3. Clonar un repositorio desde GitHub

Si el repositorio ya existe en GitHub:

git clone https://github.com/nae051293-create/POO-Git-Casos.git
cd POO-Git-Casos

4. Navegación básica

Verifica el estado del repositorio:

git status


Consulta el historial de commits:

git log


Para una vista más resumida:

git log --oneline

5. Primer commit

Crea o modifica un archivo (por ejemplo, guia_git.md).

Agrega los cambios al área de preparación:

git add .


Guarda los cambios en el repositorio:

git commit -m "Primer commit: se agrega guia_git.md en el proyecto"

6. Visualización del historial de commits

Puedes ver el historial detallado de tus cambios con:

git log


O una versión más compacta y gráfica:

git log --oneline --graph --decorate

7. Crear y cambiar de ramas

Crear una nueva rama:

git branch develop


Ver las ramas disponibles:

git branch


Cambiarte a una rama:

git checkout develop


Crear y cambiar en un solo paso:

git checkout -b develop

8. Fusionar ramas

Para integrar los cambios de una rama en la rama principal (main o master):

Cambia a la rama principal:

git checkout main


Fusiona la otra rama:

git merge develop

9. Publicar en un repositorio remoto

Primero, conecta tu repositorio local con el de GitHub:

git remote add origin https://github.com/nae051293-create/POO-Git-Casos.git


Sube tu rama principal al repositorio remoto:

git push -u origin main


Para subir cambios posteriores:

git push

10. Estructura sugerida del repositorio
POO-Git-Casos/
├── caso1/
│   └── UsuarioSimple.java
├── caso2/
│   └── EstudianteInteractivo.java
├── caso3/
│   └── CuentaBancaria.java
├── guia_git.md
├── informe_final.pdf
└── README.md

11. Buenas prácticas

Realiza commits pequeños y con mensajes claros.

Usa ramas para nuevas funciones o casos de prueba.

Mantén actualizado tu repositorio local con git pull.

Verifica tus cambios antes de subirlos con git status.

12. Reporte final

Al finalizar los casos:

Guarda tu documentación en informe_final.pdf.

Verifica que todo esté en la estructura correcta.

Realiza un último commit y push:

git add .
git commit -m "Entrega final del proyecto POO-Git-Casos"
git push