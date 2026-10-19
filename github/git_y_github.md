Vamos a trabajar con:

1. Creación de Repo
2. Clonar Repo
3. Forkear Repo (PR)
4. Gitflow

---

Git: Software local que permite el versionamiento de proyectos

GitHub: Plataforma web donde se almacena los proyectos

_Ambos trabajan en flujo_

1. Working Directory: Hace referencia a un proyecto sin seguimiento de versión.
2. Staging Area: Versionamiento local del proyecto (pc)
3. Repositorio: Versionamiento en la nube (Github, bitbokect, aws, etc....)

ejm: |Proyecto| -> Working Directory
|
git add . <-------> git init
| | |
|Proyecto| -------------------> Staging Area
|
git commit| -> git remote| -> git push|
|
|Proyecto| -> Repositorio

---

Equipos Publicos Equipo privado

1. Limpieza de credenciales | 1 Configuración de usuario y correo
2. Eliminar la autenticación | 2 Versionamos el proyecto
3. Configurar usuario y correo |
4. Versionamos el proyecto |

U: untraked ) Working
A: Added ) Staging Area
M: Modify ) Staging

cd= change directory
cd.../ salir de la carpeta
cd nombre de la carpeta

_Comandos_
averiguar los comando para trabajar en la terminal

_iniciamos limpiando credenciales en equipo publico_
git config --global credential.helper ""

_luego colocamos nuestro usuario_
git config --global user.name
git config --global user.email

_Para crear carpetas y archivos_
mkdir --> Carpetas mkdir -- extensión
touch --> Archivos touch -- extensión

docs: Referente a todo lo que sea documentación
feature: Referente a todo cambio visualmente represente un cambio
fix: referente a los ajustes o cambios en errores de codigo
chore: Referente a cualquier cambio de código que no representa un resultado final

git checkout -b (crear rama nueva)
git branch (para saber cuantas ramas hay - listar ramas)
git checkout (cambiar de rama)


code . (abre la carpeta que muestra la terminal)
code "nombre de la carpeta sin comillas" (abre la carpeta de github o del proyecto en VScode)

