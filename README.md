# git-code-education
Aula de git da code education

##Comandos Essenciais


###Inicializando Repositório
`git init` 

###Adicionar arquivo para commit
`git add {nome do arquivo}` 

###Comitar com mensagem
`git commit -m '{mensagem}'`

###Criando novo Branch
`checkout - b {nome_branche}`

###Pra ver os branches locais 
`git branch`

###Prara ver os branches locais e remotos###
`git branch -a`

>Quando se clona um repositório ele só baixa o branch master.

###Para baixar outro branch para a maquina local:
`git checkout -b {nome_branch} origin/{nome_branch}`

###Sincronizar com repositório remoto 
_tanto para arquivos como branch - não baixa arquivo, mas atualiza as referências_ 

`git pull`

###Enviar alterações para repositório remoto
`git push origin master`

###Baixar posiveis alterações do repositório remoto, do branch master
`git pull origin master`

###Enivar novo brach local para repositório 
_mesmo quando o banch não existe no repositório_ 

`git push origin {nome_do_branch}`

###Remover branch remoto
`git push origin :{nome_do_branch}`

#### Envio para repositorio Remoto
`git push origin master`
