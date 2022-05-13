# Conhecendo Git e GitHub

Comandos trabalhados nas aulas e mais alguns que considero importantes, dúvidas respondidas, etc.


## Autor

- [PedroHTomaz - GitHub](https://github.com/PedroHTomaz)
- [PedroHTomaz - LinkedIn](https://www.linkedin.com/in/pedro-henrique-tomaz-vieira-ti/)


## Comandos Git

* *Criar um novo repositório*: `git init`

* *Verificar estado dos arquivos*: `git status`

* *Adicionar um arquivo específico* (staged area): `git add arquivo.txt`

* *Adicionar todos os arquivos*: `git add .`

* *Comitar informando mensagem*: `git commit arquivo.txt -m "mensagem de commit"`

* *Remover arquivo*: `git rm arquivo.txt`

* *Remover diretório*: `git rm -r diretorio`

* *Exibir histórico*: `git log`

* *Vincular repositório local a um repositório remoto*: `git remote add origin[repositório]`

* *Desvincular um repositório remoto*: `git remote rm[repositório]`

* *Enviar arquivos para o repositório remoto*:

   * Se for o primeiro push: `git push -u origin main`
   * Se não: `git push`

* *Trazer alterações/arquivos do repositório remoto para o local*: `git pull`

* *Clonar um repositório*: `git clone [repositório]`

* *Criar uma nova branch*: `git branch [nome da branch]`

* *Mudando para uma branch existente*: `git checkout [nome da branch]`

* *Fazer um merge*: `git merge [branch]`

* *Interface gráfica para resolução de conflitos*: `git mergetool`

* *Mudar de branch sem fazer commit e sem perder o trabalho*: `git stash`

* *Para ver as stashes guardadas*: `git stash list`


## FAQ

#### Qual a importância e para que serve o comando "git stash"?

Muitas vezes, quando você está trabalhando em uma parte do seu projeto, as coisas podem ficar confusas ou poderá aparecer uma demanda mais importante. Nessa situação você quer mudar de branch por um tempo para trabalhar em outra coisa. O problema é que você não quer fazer o commit de um trabalho incompleto somente para voltar a ele mais tarde. A resposta para esse problema é o comando git stash. Você fará o stash das modificações, deixando-as guardadas para continuar mais tarde. 

#### O que é e para que serve o GitHub desktop?

GitHub desktop é um aplicativo que nos permite interajir com o GitHub por meio de uma interface gráfica em vez de linha de comando, o que facilita muito o trabalho do dia a dia.