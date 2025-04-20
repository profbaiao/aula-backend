## Requisistos

* Node.js 22 ou superior

caso tenha problema com o comando npm por uma segurando do power shell digite o seguinte comando no prompt

Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser

## Como rodar o projeto baixado

Instalar todas dependencias do arquivo package

```
npm intall
```

Compilar o arquivo TypeScript
'''
npx tsc
'''

Executar o arquivo gerado com o Node.js
'''
node dist/index.js
'''



## Sequencia para criar projeto

Criar o arquivo package
```
npm init
``` 
Instalar o Expres para gerenciar as requisições, rotas e URLs, entre outras funcionalidade.
``` 
$ npm i express 
``` 

Instalar os pacates para suporte ao TypeScript
'''
npm i --save-dev @types/express
npm i --save-dev @types/node
'''

Instalar o compilador do projeto com TypeScript e reiniciar o projeto quando o arquivo é modificado
'''
npm i --save-dev ts-node
'''

Gerar o arquivo de configuração para o TypeScript
'''
npx tsc --init
'''

Compilar o arquivo TypeScript
'''
npx tsc
'''

Executar o arquivo gerado com o Node.js
'''
node dist/index.js
'''

## Como enviar e baixar os arquivos do Github

Baixar os arquivos do Git
'''
git clone -b <branch_name> <repository_url> .
'''

Verifica qual Branch vc esta no GitHub
'''
git branch
'''

Baixa todas as atualizações do projeto GitHub
'''
git pull
'''

Adiciona todos os arquivos modificados no staging area
'''
git add . 
'''