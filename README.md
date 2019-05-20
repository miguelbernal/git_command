# Comandos de Git
* Working directory --> Staging area --> Repository
* Fuente actual --> Archivos elegidos --> Registo de todo
* git add --> git commit -->                
## Ayuda
1. git help add
## Configuración
2. git config --global user.name "Nombre Usuario"
3. git config --global user.email "usuario@mail.com"
4. git config --global color.ui true
5. git config --global --list
## Inicializar nuestro proyecto
6. git init
## Estado de nuestro proyecto
7. git status
## Agregar archivos
8. git add
9. git add index.html
10. git add -A
## Guardar los cambios que hicimos
11. git commit -m "Mensaje"
## Viajar en el tiempo
12. listar todos los commit -> git log 
13. ir a un determinado commit -> git checkout d462223344464646464646321326
14. ir al último commit -> git checkout master
## Eliminar commits
15. eliminar commit -> git reset
16. no le pasa nada a nuestro codigo (no toca el Working Area) -> git reset --soft d461643213
17. borra el Staging Area, sin tocar el Working Area -> git reset --mixed d461313165
18. borra absolutamente todo lo que hay en el commit -> git reset --hard d4546467878
## Github
19. clonar repositorio --> git clone
## Repositorios locales (Nuestra computadora) y remotos (Github)
20. vincular nuestro repositorio local al remoto --> git remote add origin https://github.com/...
21. quitar vinculo --> git remote remove origin
22. ver los repositorios remotos --> git remote -v
23. pasar al repositorio remoto --> git push origin master
## create a new repository on the command line
   ```sh
    echo "# git_command" >> README.md
    git init
    git add README.md
    git commit -m "first commit"
    git remote add origin https://github.com/miguelbernal/git_command.git
    git push -u origin master
   ```