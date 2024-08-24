COMANDOS DE GIT Y SU USO
========================

Lista de comandos git
----------------------

| Basico | 
| ------ | 
| [git init](./git-init.md) | 
| [git add *file*](./git-add.md) | 
| [git add .](#tres) | 
| [git commit -m *mensaje*](#cuatro) | 
| [git status](#cinco) | 
| [git push](#seis) | 
| [git branch](#siete) | 
| [git branch *nombre*](#ocho) |
| [git checkout *nombre-rama*](#nueve) |
| [git merge *nombre-rama*](#diez) |
| [git clone *url*](#once) | 
| [git pull](#doce) | 



Inicializa un nuevo repositorio Git en el directorio actual.

```bash
    git init 
```

Añade el archivo especificado al área de preparación.

```bash
    git add <file>
```

Añade todos los cambios en los archivos del directorio actual al área de preparación.

```bash
    git add .
```

Crea un commit con los archivos en el área de preparación y un mensaje descriptivo.

```bash
    git commit -m <mensaje>
```

Muestra el estado de los archivos en el directorio de trabajo y el área de preparación.

```bash
    git status
```

Sube los commits de la rama actual al repositorio remoto.

```bash
    git push
```

Lista todas las ramas locales en el repositorio.

```bash
    git branch
```

Crea una nueva rama llamada *nombre*.

```bash
    git branch <nombre>
```

Cambia a la rama especificada *nombre*.

```bash
    git checkout <nombre-rama>
```

Fusiona la rama especificada (*nombre*) con la rama actual.

```bash
    git merge <nombre-rama>
```

Clona un repositorio existente desde una URL a tu máquina local.

```bash
    git clone <url>
```

Descarga y fusiona los cambios del repositorio remoto en la rama actual.

```bash
    git pull
```

