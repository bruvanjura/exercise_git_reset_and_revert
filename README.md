# exercise_git_reset_and_revert
Este repositório contém os exercícios de Git reset e Git revert da Aula 3 de Git.

Nesse exercício iremos praticar tanto o `git reset` quanto o `git revert`. Como apresentado na aula, eles são utilizados principalmente para corrigir erros de código presente em commits. 

- **Git Revert**

Nesse repositório o PENÚLTIMO commit introduziu um erro fazendo com que o `div.py` parasse de funcionar. Seu primeiro objetivo e utilizar o git revert para adicionar um commit revertendo as alterações realizadas por aquele commit em específico.

Você deve utilizar o `git log` para encontrar qual commit estou me referindo e depois utilizar o `git revert`.

- **Git Reset**

Agora vamos reverter a correção que vocês fizeram usando o `git reset` apagando completamente o commit gereado pelo `git revert` consequentemente voltando o repositório para seu estado anterior.

Agora vocês devem utilizar o `git reset` para resolver o problema do penúltimo commit. Para isso utilizem o reset que mantém as alterações dos arquivos use `git restore` para restaurar o arquivo `div.py` e refaça o último commit.