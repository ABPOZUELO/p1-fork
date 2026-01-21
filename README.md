# Práctica 1 - Documentación de Git

### 1. git clone
**Definición:** Este comando nos va a permitir clonar un repositorio dentro de nuestro ordenador
para poder editarlo sin editar el original.

**Log de consola:**
```bash
Cloning into 'p1-fork'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.
```




### 2. git status
**Definición:** Nos realiza un informe sobre los documentos dentro de nuestro repositorio (si se
han producido cambios).

**Log de consola:**
```bash
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   git.txt

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   git.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .idea/
```


### 3. git add .
**Definición:** Añade los cambios realizados en la fase de preparación. Con el punto . le indicamos que
añada todos los archivos modificados a la vez, dejándolos listos para ser confirmados.

**Log de consola:**
```bash
PS C:\Users\jorge\IdeaProjects\p1-fork> git add .
PS C:\Users\jorge\IdeaProjects\p1-fork>
```

### 4. git commit -m "texto"
**Definición:** Confirma los cambios preparados y los guarda permanentemente en el historial local de 
nuestro ordenador. El mensaje -m etiqueta ese cambio para saber qué hicimos.

**Log de consola:**
```bash
[main f58fc49] Explicando comandos basicos
 6 files changed, 49 insertions(+)
 create mode 100644 .idea/.gitignore
 create mode 100644 .idea/misc.xml
 create mode 100644 .idea/modules.xml
 create mode 100644 .idea/p1-fork.iml
 create mode 100644 .idea/vcs.xml
 create mode 100644 git.txt
```

### 5. git push
**Definición:** Sube (empuja) los cambios confirmados desde mi repositorio local al repositorio remoto
en GitHub.
**Log de consola:**
```bash
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 16 threads
Compressing objects: 100% (9/9), done.
Writing objects: 100% (9/9), 1.64 KiB | 420.00 KiB/s, done.
Total 9 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To [https://github.com/ABPOZUELO/p1-fork.git](https://github.com/ABPOZUELO/p1-fork.git)
   07720b5..f58fc49  main -> main
```

### 6. git checkout
**Definición:** Este comando sirve para cambiar de rama. Nos permite salir de la rama en la que estamos 
(por ejemplo, 'feature/1') y regresar a la rama principal ('main'), recuperando el estado de los archivos 
tal y como están en esa línea principal.
**Log de consola:**
```bash
Switched to a new branch 'feature/1'
Switched to branch 'main'
```
### Evidencias y Capturas Originales
Para cumplir con los requisitos de entrega (evidencias de entorno y capturas de imagen), adjunto los siguientes ficheros:

* 📄 **Evidencia del entorno (Java/Git):** [entorno.txt](entorno.txt)
* 📷 **Documento con capturas de pantalla:** [practica1.docx](practica1.docx)