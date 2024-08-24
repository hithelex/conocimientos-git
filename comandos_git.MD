COMANDOS DE GIT Y SU USO
========================

Lista de comandos git
----------------------

| Basico | 
| ------ | 
| git init | 
| git add *file* | 
| git add . | 
| git commit -m *mensaje* | 
| git status | 
| git branch | 
| git branch *nombre* |
| git checkout *nombre-rama* |
| git merge *nombre-rama* |
| git clone *url* | 



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

Fusiona la rama especificada (*nombre*) con la rama actua.

```bash
    git merge <nombre-rama>
```

Clona un repositorio existente desde una URL a tu máquina local.

```bash
    git clone <url>
```

