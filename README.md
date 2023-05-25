CIAO
per scrivere un file README uso "vim", per salvare il file uso "esc + :w", per uscire uso ":wq". The "echo" command is used to add a new line with the file, we have to put >> to add it like:
echo "Adding another line on monday" >> READ.ME md

With > we can create the file

While echo, prints the file of the terminal

If I print echo with the symbol >, Linux recognize ">" grab the characters that I put to the terminal and put them where I told him.

For instance

eco "I am just printing a line on the terminal" > this_is_a_new_file.txt

(In this way we created a new file in the directory called this is a new file.txt containint the characters " I am just printing a line on the terminal)

Push mi permette di sincronizzare i miei local changes con il "server di git hub"

Branches are diverging versions of the same repository, they can contain many variants of the repository itself. Basically, it allows people to allows to different part of a project working in sub directories of the main directory (which is the same).

Gli steps sono:

1- GIT ADD      CREIAMO UN FILE
2- GIT COMMIT   COMMITTIAMO IL FILE
3- GIT PUSH     SINCRONIZZIAMO IL FILE CON IL "SERVER" DI GITHUB

Gli step sono:

1- GIT ADD      CREIAMO UN FILE
2- GIT COMMIT   COMMITTIAMO IL FILE
3- GIT PUSH     SINCRONIZZIAMO IL FILE CON IL "SERVER" DI GITHUB

Lista di alcuni comandi che possono essere utili:

Per aggiornare/refreshare GIT, esegui: <git push origin>
Per rinominare una cartella su Linux, esegui: <mv vecchio-nome nuovo-nome>
Per passare a un branch diverso, utilizza il comando git checkout seguito dal nome del branch. Ad esempio, per passare al branch "feature/nuova-funzionalità", esegui: <git checkout feature/nuova-funzionalità>

