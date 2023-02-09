# git_1_daw
Tarea 3 de Git y github en Entornos de Desarrollo

### COMANDOS UTILIZADOS - PUSH INICIAL
```
git clone git@github.com:arodmor789/git_1_daw.git
cd git_1_daw
nano README.md
git add README.md
git commit -am "commit inicial"
```

### COMANDOS UTILIZADOS - GITIGNORE
```
touch privado.txt
mkdir privada
touch .gitignore
nano .gitignore
```

### COMANDOS UTILIZADOS - fichero 1.txt y tag v0.1
```
touch 1.txt
git add 1.txt
git tag v0.1
git commit -am "añadido fichero 1.txt y tag"
git push
```

### COMANDOS UTILIZADOS - Creación de tabla
```
nano README.md
git add README.md
git commit "Añadida tabla al readme
git push
```

### Tabla de cuentas GitHub

| NOMBRE | CUENTA |
| ------ | ------ |
| Abraham | arodmor789 |
| Antonio | anuncar621508 |
| Alex | asecval523 |
| Pablo | pamadob |
| David R. | davrey |
| Jose P. | josepeca |
| Iván | ibarrom693 |
| Andres | andresgilr |
| Juanfri | juanfri18 |

### COMANDOS UTILIZADOS - Creación de una nueva Rama
```
git branch v0.2
git checkout v0.2
touch 2.txt
git add 2.txt
nano README.md
git add README.md
git commit "Añadida rama v0.2 y 2.txt”
git push
```

### COMANDOS UTILIZADOS - Fusión de master y v0.2
```
git checkout main
git merge v0.2
```

### COMANDOS UTILIZADOS - Merge con conflicto
```
nano 1.txt
git add 1.txt
git commit -am “Añadido hola en 1.txt”
git checkout v0.2
nano 1.txt
git add 1.txt 
git commit -am “Añadido adios en 1.txt”
git checkout main
git merge v0.2
nano 1.txt
git commit -am “Solución conflicto en 1.txt”
git push
git checkout v0.2
git push
```

### COMANDOS UTILIZADOS - Crear tag, borrar rama y listar cambios
```
git tag v0.2
git branch -d v0.2
git log --graph
```

### COMANDOS UTILIZADOS - Crear archivo equipo.md
```
touch equipo.md
nano equipo.md
git add equipo.md
nano README.md
git add README.md
git commit -am "añadido equipo.md"
git push
```

