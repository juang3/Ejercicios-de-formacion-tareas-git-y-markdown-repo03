# Ejercicio 3: FAST FORWARD

3.1. Crea un directorio llamado repo03 (tu decides como lo haces) con un fichero readme.md vacío, haz un commit súbelo a un repositorio rmoto que tendrá el mismo nombre repo03.


__Repositorio local__
~~~
    git init repo03
    cd repo03
    touch readme.md
    git add readme.md
    git commit -m "readme.md vacío"
~~~

__Repositorio remoto__
~~~
    1. Entrar a GitHub
    2. Crear nuevo repositorio
    3. Añadir nombre al nuevo repositorio
        "Ejercicios-de-formacion-tareas-git-repo03"
    4. Copiar la dirección del repositorio remoto
        (se utilizará para vincular con el repositorio local)
~~~

__Repositorio local__
~~~
    git branch -M main
    git remote add origin https://github.com/juang3/Ejercicios-de-formacion-tareas-git-y-markdown-repo03.git
    git push -u origin main
~~~