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
- ```$ git diff ``` (lista as diferenças de todos os arquivos alterados localmente)
- ```$ git diff <path> ``` (lista as diferenças do arquivo especificado pelo path)
- ```$ git diff HEAD~1 ``` ('HEAD' é um ponteiro para o último commit da branch corrente. 'HEAD~N' faz referência ao Nésimo commit antes do HEAD. 'HEAD~1', portanto, é o penúltimo commit do branch corrente.)
- ```$ git clone <URL> ``` (Baixa uma cópia do repositório remoto.)
- ```$ git checkout <commit>``` (voltar o repositório local para o commit selecionado)
- ```$ git checkout <commit> <file>``` (voltar o arquivo para o commit selecionado)
- ```$ git checkout -- <file>``` (desfaz todas as alterações que não estejam no stage desde o último commit)
- ```$ git checkout HEAD -- <file>``` (desfaz todas as alterações, incluindo o stage, desde o último commit)
- ```$ git revert <commit>``` (cria um novo commit desfazendo as alterações do commit especificado. Util para desfazer commits antigos)

## Estados dos arquivos 

- Untracked: não monitorado
- Modified: modificado
- staged: preparado
- commited: consolidado

![Image](./git_estado_arquivos.PNG?raw=true)
