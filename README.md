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



## Observações
Cada etapa foi realizada por apenas um integrante por vez, respeitando a ordem de commits e a integridade do código.

