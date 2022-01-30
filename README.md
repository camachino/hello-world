# hello-world

Un repositorio para empezar a usar Github y Github Actions con Java

## ¿Como probar en el cloud?

[![](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/camachino/hello-world/)

##Desde aquí se puede acceder a mi gitpod desde donde se han probado los siguientes comandos:
Me gustaría destacar la creacion de los tokens para el acceso y la gestión necesaria de permisos para poder acceder y enlazar al proyecto

## Comandos git básicos utilizados en la práctica

```
git clone https://github.com/gitt-3-pat/hello-world
git status
git add .
git commit -m "TU MENSAJE"
git push

git checkout -b feature/1
git checkout main
```
## Aquí se pueden ver los mensajes de retorno tras haberlos probado en la terminal del gitpod

## gitpod /workspace/hello-world $ git clone https://github.com/gitt-3-pat/hello-world
Cloning into 'hello-world'...
remote: Enumerating objects: 38, done.
remote: Counting objects: 100% (38/38), done.
remote: Compressing objects: 100% (23/23), done.
remote: Total 38 (delta 1), reused 31 (delta 0), pack-reused 0
Receiving objects: 100% (38/38), 58.97 KiB | 6.55 MiB/s, done.
Resolving deltas: 100% (1/1), done.

## gitpod /workspace/hello-world $ git add .

warning: adding embedded git repository: hello-world
hint: You've added another git repository inside your current repository.
hint: Clones of the outer repository will not contain the contents of
hint: the embedded repository and will not know how to obtain it.
hint: If you meant to add a submodule, use:
hint: 
hint:   git submodule add <url> hello-world
hint: 
hint: If you added this path by mistake, you can remove it from the
hint: index with:
hint: 
hint:   git rm --cached hello-world
hint: 
hint: See "git help submodule" for more information.
 
## gitpod /workspace/hello-world $ git commit -m "Soy Ignacio"
 
[main 0a1a48a] Soy Ignacio
 1 file changed, 1 insertion(+)
 create mode 160000 hello-world
 
 
## gitpod /workspace/hello-world $ git push
 
 
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 276 bytes | 276.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/camachino/hello-world.git
   48fe276..0a1a48a  main -> main

 
 ## gitpod /workspace/hello-world $ git checkout -b feature/1
 
 
Switched to a new branch 'feature/1'
gitpod /workspace/hello-world $ git checkout main
Switched to branch 'main'
## Referencias

- https://git-scm.com/
 
 
 ![Captura de pantalla 2022-01-30 183628](https://user-images.githubusercontent.com/46677129/151713489-e76c0639-9799-4df1-abfa-39d5237f8931.png)

Y aquí se puede ver las descargas que se han realizado con el fin de establecer el entorno de trabajo para el resto de la asignatura.
 
 
