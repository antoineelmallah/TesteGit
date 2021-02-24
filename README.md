# Testes com git

## Comandos mais usados:

- ```$ git help```
- ```$ git help <comando>```
- ```$ git init```
- ```$ git status```
- ```$ git log```
- ```$ git add <lista de arquivos>```
- ```$ git add .```
- ```$ git commit```
- ```$ git commit - m "<mensagem>"```
- ```$ git config --global core.editor gedit``` (Alterar editor de texto padrão para gedit)
- ```$ git remote -v```
- ```$ git remote add origin <endereço repositório remoto>```
- ```$ git push -u origin master``` (primeira vez)
- ```$ git push``` (demais vezes)
- ```$ git push <remote> <branch>``` (todas as vezes, caso o comando "git push -u origin master" não tenha sido executado)
- ```$ git diff ``` (diferenças entre a)
- ```$ git checkout <commit>``` (voltar o repositório local para o commit selecionado)
- ```$ git checkout <commit> <file>``` (voltar o arquivo para o commit selecionado)

## Estados dos arquivos 

- Untracked: não monitorado
- Modified: modificado
- staged: preparado
- commited: consolidado

![Image](./git_estado_arquivos.PNG?raw=true)
