// 1. Se inicializó "git" y se trajeron los archivos desde el repositorio del curso.

alumno@huayra:~$ git init
Initialized empty Git repository in /home/alumno/.git/

alumno@huayra:~$ git clone https://github.com/wtpc/HOdebug-profile.git
Cloning into 'HOdebug-profile'...
remote: Counting objects: 103, done.
remote: Total 103 (delta 0), reused 0 (delta 0), pack-reused 103
Receiving objects: 100% (103/103), 60.39 KiB | 32.00 KiB/s, done.
Resolving deltas: 100% (27/27), done.
Checking connectivity... done.
alumno@huayra:~$ git fetch
fatal: No remote repository specified.  Please, specify either a URL or a
remote name from which new revisions should be fetched.
alumno@huayra:~$ git fetch https://github.com/wtpc/HOdebug-profile.git
remote: Counting objects: 103, done.
remote: Total 103 (delta 0), reused 0 (delta 0), pack-reused 103
Receiving objects: 100% (103/103), 60.39 KiB | 26.00 KiB/s, done.
Resolving deltas: 100% (27/27), done.
From https://github.com/wtpc/HOdebug-profile
 * branch            HEAD       -> FETCH_HEAD

// 2. Se abrieron los correspondientes files "README.md" a fin de leer las consignas que se debían seguir y, a continuación, se abrió el primer script ("profile_me_1.c") en el editor de texto "pluma" para revisarlo, previo a su compilación.

alumno@huayra:~$ ls
Compartido  Documentos  HOdebug-profile  Música      Videos
Descargas   Escritorio  Imágenes         Plantillas
alumno@huayra:~$ cd HOdebug-profile
alumno@huayra:~/HOdebug-profile$ ls
debug  profile  README.md
alumno@huayra:~/HOdebug-profile$ gedit README.md
bash: gedit: no se encontró la orden
alumno@huayra:~/HOdebug-profile$ cd README.md
bash: cd: README.md: No es un directorio
alumno@huayra:~/HOdebug-profile$ gedit README.md
bash: gedit: no se encontró la orden
alumno@huayra:~/HOdebug-profile$ pluma README.md
alumno@huayra:~/HOdebug-profile$ cd profile
alumno@huayra:~/HOdebug-profile/profile$ ls
C  FORTRAN  internal_profiling.txt  README.md
alumno@huayra:~/HOdebug-profile/profile$ pluma README.md
alumno@huayra:~/HOdebug-profile/profile$ cd C
alumno@huayra:~/HOdebug-profile/profile/C$ ls
profile_me_1.c  profile_me_2.c
alumno@huayra:~/HOdebug-profile/profile/C$ pluma profile_me_1.c


