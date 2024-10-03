# Clase 06- Bootcamp


## Repaso GIT   

````sh
git init
````
# Listo el estado de los archivos

````sh
git status
````
# Haciendo un commit
1. Agrego al área de staging, los archivos que necesito que formen parte del commit
````sh
git add <nombre archivo>
git add <nombre archivo> <nombre-archivo> <nombre-archivo>
git add . # Agrega todos los rvhicos que tengo en el working directory (WD)
```` 
2. Hago el commit

````sh
git commit -m "Mensaje descriptivo"
````

# Cambiar el editor por nano
````sh
git config --global core.editor nano
git config --global core.editor "code --wait"
````
# Ver listado de comits que hice en el repo
````sh
git log # version larga
git log --oneline #version corta
````

# Pare ver si se agrego el repo remoto
````sh
git remote -v
````
# Repositorio
```` sh
git remote add origin <url-al-repo-remoto>
git remote add origin https://github.com/po1son3/Repaso-ramas.git
````
# Subo al remoto el repositorio local 
````sh
git push -u origin main # La primera vez
git push
````
# Para recuperar mi codigo luego de una catastrofe
Ir al repositorio de github, hacer click sobre el boton code y copiar la url a mi repositoiro
````sh
git clone <url-al-repositorio>
git clone https://github.com/po1son3/Repaso-ramas.git ./ # clona el directorio actual
git clone https://github.com/po1son3/Repaso-ramas.git # crea una carpeta (repaso-ramas) y clona el repositorio remoto al local.
````

