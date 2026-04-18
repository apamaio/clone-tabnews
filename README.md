# clone-tabnews
Implementação do https://www.tabnews.com.br para o http://curso.dev. Um projeto para aprender de fora a fora um projeto do zero.
* **Aluno:** Adriano P. de Azevedo
* **Ambiente de SO:** Kubuntu (KDE Plasma) + VSCode
* **Ambiente de Estudo/Desenvolvimento:** Github + Codespaces (VSCode)


## Comandos terminal utilizados nas aulas 

### Dia 3 - Aula 2 
  * `node -v`   
  Enter em todos os questionamentos, e "license" preencher como MIT
  * `nvm ls`
  * `nvm install lts/hydrogen`
  * `nvm --help`
  * `nvm alias default lst/hydrogen`
  * `touch .nvmrc` 
  Criar um arquivo para RunCommands, com instruções de inicialização. Neste arquivo foi adicionado a linha com o texto "lts/hydrogen" mais uma linha em branco.
  * `nvm install` 
  Este comando vai fazer a instalação do nvm com  versão definida no arquivo .nvmrc
### Dia 3 - Aula 3 
  * `npm init`   
  Enter em todos os questionamentos, e "license" preencher como MIT
  * `npm install next@13.1.6`
  * `npm install react@18.2.0`
  * `npm install react-dom@18.2.0`
### Dia 4 - Aula 2 
  * Alterar o package.json, em "scripts" alterar o remover a linha "test" e incluir "dev" como abaixo:   
    `"dev": "next dev"`
  * `npm run dev`
### Dia 4 - Aula 3
  * `mkdir pages ` 
  * `cd pages `
  * `touch index.js`
  * `npm run dev`
### Dia 5 
  * `$ git log` Lista de commits do projeto 
  * `$ git log --stat` Status do projeto dentro no GitHub 
  * `$ git status` Compara o status local com Github e lista o que não foi commitado 
  * `$ git log --oneline` Lista os commits com informações em uma linha 
  * `$ git status` Compara o status local com Github e lista o que não foi commitado 
  * `$ git add .gitignore` Adiciona o arquivo '.gitignore' na fase staged, ou seja em fila de commit  
  * `$ git commit --amend` O git pega tudo que estiver na fase staged, ou seja em fila de commitar, e adiciona ao ultimo commit feito 
### Dia 6 
  * `$ comando` Explicação 
  * `$ git commit -m "mensagem"` Atalho para fazer novos commits.
  * `$ git push` Empurrar alterações locais para o origin.
  * `$ git push --force` Empurrar de forma forçada alterações locais para o origin.
  * `$ git push -f` A forma comprimida do comando anterior.