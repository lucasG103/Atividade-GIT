# Atividade Avaliativa - Git Colaborativo com Portugol

## Integrantes do grupo
- Lucas Eduardo da Silva
- Rafael Dalpozo Bruza Alves   


## Objetivo
Desenvolver colaborativamente um algoritmo em Portugol de…..

## Etapas realizadas por cada membro

### Lucas Eduardo da Silva 
- Criou o repositorio
- configurei o repositorio , criando a chave ssh
- criei o arquivo algoritmo.por
- adicionei o codigo em portugol no arquivo algoritmo.por
- fiz a parte do número inteiro no codigo em portugol
### Rafael Dalpozo Bruza Alves  
- fiz a parte do qual o seu nome no codigo em portugol
- clonei o repositorio
- fiz as commits 
- Fiz o README
 
 

## Comandos utilizados
Todos os comandos foram executados via terminal utilizando chave SSH:
### Comandos do Lucas 

compuni@LAB04M34 MINGW64 ~
$ git config --global user.name

compuni@LAB04M34 MINGW64 ~
$ git config --global user.email

compuni@LAB04M34 MINGW64 ~
$ git config --global --unset user.name

compuni@LAB04M34 MINGW64 ~
$ git config --global --unset user.email

compuni@LAB04M34 MINGW64 ~
$ ls -al ~/.ssh
ls: cannot access '/c/Users/compuni/.ssh': No such file or directory

compuni@LAB04M34 MINGW64 ~
$ rm -f ~/.ssh/id_rsa*

compuni@LAB04M34 MINGW64 ~
$ git config --global lucasG103
error: key does not contain a section: lucasG103

compuni@LAB04M34 MINGW64 ~
$ git config --global user.name"lucasG103"

compuni@LAB04M34 MINGW64 ~
$ git config --global user.email"lucasedubr1@gmail.com"

compuni@LAB04M34 MINGW64 ~
$ ssh-keygen -t rsa -b 4096 -C "lucasedubr1@gmail.com"
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/compuni/.ssh/id_rsa):
Created directory '/c/Users/compuni/.ssh'.
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/Users/compuni/.ssh/id_rsa
Your public key has been saved in /c/Users/compuni/.ssh/id_rsa.pub
The key fingerprint is:
SHA256:wCQpu5oaRWtvYWCDa6rluG+YDa9192EWC4Wpq+wXrWI lucasedubr1@gmail.com
The key's randomart image is:
+---[RSA 4096]----+
|    ...          |
| .. .+ o         |
|. =o  = .        |
| +.+ . o         |
|..+.+.. S        |
|+o.o.o.. o       |
|oOo =o. =        |
|*BE+o. + .       |
|BB*o    .        |
+----[SHA256]-----+

compuni@LAB04M34 MINGW64 ~
$ eval "$(ssh-agent -s)"
Agent pid 944

compuni@LAB04M34 MINGW64 ~
$ ssh-add ~/.ssh/id_rsa
Identity added: /c/Users/compuni/.ssh/id_rsa (lucasedubr1@gmail.com)

compuni@LAB04M34 MINGW64 ~
$ clip < ~/.ssh/id_rsa.pub

compuni@LAB04M34 MINGW64 ~
$ ssh -T git@github.com
The authenticity of host 'github.com (20.201.28.151)' can't be established.
ED25519 key fingerprint is SHA256:+DiY3wvvV6TuJJhbpZisF/zLDA0zPMSvHdkr4UvCOqU.
This key is not known by any other names
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added 'github.com' (ED25519) to the list of known hosts.
Hi lucasG103! You've successfully authenticated, but GitHub does not provide shell access.

compuni@LAB04M34 MINGW64 ~
$ git clone git@github.com:usuario/Atividade-GIT
Cloning into 'Atividade-GIT'...
ERROR: Repository not found.
fatal: Could not read from remote repository.


### Comandos do Rafael 

compuni@LAB6M28 MINGW64 ~
$ git config --global user.name
RafaelBruza

compuni@LAB6M28 MINGW64 ~
$ git config --global user.email
rafaelbruza@hotmail.com





git config --global user.email rafaelbruza@hotmail.com

compuni@LAB6M28 MINGW64 ~
$ git config --global --unset user.name

compuni@LAB6M28 MINGW64 ~
$ git config --global --unset user.email

compuni@LAB6M28 MINGW64 ~
$ ls -al ~/.ssh
total 33
drwxr-xr-x 1 compuni 1049089    0 Apr 11 20:16 ./
drwxr-xr-x 1 compuni 1049089    0 Apr 11 20:19 ../
-rw-r--r-- 1 compuni 1049089 3389 Apr 11 20:16 id_rsa
-rw-r--r-- 1 compuni 1049089  746 Apr 11 20:16 id_rsa.pub
-rw-r--r-- 1 compuni 1049089  828 Mar 28 19:56 known_hosts
-rw-r--r-- 1 compuni 1049089   92 Mar 28 19:56 known_hosts.old

compuni@LAB6M28 MINGW64 ~
$ rm -f ~/.ssh/id_rsa*

compuni@LAB6M28 MINGW64 ~
$ git config --global user.name RafaelBruza

compuni@LAB6M28 MINGW64 ~
$ ^C

compuni@LAB6M28 MINGW64 ~
$ git config --global user.email "rafaelbruza@hotmail.com"

compuni@LAB6M28 MINGW64 ~
$ ssh-keygen -t rsa -b 4096 -C "rafaelbruza@hotmail.com"
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/compuni/.ssh/id_rsa):
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/Users/compuni/.ssh/id_rsa
Your public key has been saved in /c/Users/compuni/.ssh/id_rsa.pub
The key fingerprint is:
SHA256:pLSC7Qyt4ZrMwyy4iuWo+xH4yhaeGGJsZJHhX3PhHMs rafaelbruza@hotmail.com
The key's randomart image is:
+---[RSA 4096]----+
| .o    o         |
|.o    + +        |
| ..  o.E.        |
| +.+..o+         |
|= =.+ o S        |
|oB B .           |
|X.O o            |
|O# .             |
|/B+              |
+----[SHA256]-----+

compuni@LAB6M28 MINGW64 ~
$ eval "$(ssh-agent -s)"
Agent pid 748

compuni@LAB6M28 MINGW64 ~
$ ssh-add ~/.ssh/id_rsa
Identity added: /c/Users/compuni/.ssh/id_rsa (rafaelbruza@hotmail.com)

compuni@LAB6M28 MINGW64 ~
$ clip < ~/.ssh/id_rsa.pub

compuni@LAB6M28 MINGW64 ~
$ git clone git@github.com:lucasG103/Atividade-GIT.git
Cloning into 'Atividade-GIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (6/6), done.

compuni@LAB6M28 MINGW64 ~
$ cd Atividade-GIT

compuni@LAB6M28 MINGW64 ~/Atividade-GIT (main)
$ git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Turn this message off by running
hint: "git config advice.addEmptyPathspec false"

compuni@LAB6M28 MINGW64 ~/Atividade-GIT (main)
$ git add.
git: 'add.' is not a git command. See 'git --help'.

The most similar command is
        add

compuni@LAB6M28 MINGW64 ~/Atividade-GIT (main)
$ git add .

compuni@LAB6M28 MINGW64 ~/Atividade-GIT (main)
$ git commit -m "criado o arquivo algoritmo.por"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

compuni@LAB6M28 MINGW64 ~/Atividade-GIT (main)


## Observações
Cada etapa foi realizada por apenas um integrante por vez, respeitando a ordem de commits e a integridade do código.

