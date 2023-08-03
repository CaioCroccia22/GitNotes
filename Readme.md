Projeto para ensinar a usar o GIT

--Inicialização o GIT(criando um repositório para a pasta):
1- Abri a pasta
2- Botão direito
3- GitBash Here
4- git init (Inicialização dentro da Branch Master)

--Dando o primeiro Commit:
1- git add "nome do arquivo" (Manda os arquivos para a area de State)
2- git commit -m "mensagem do commit"

--Verificar o status do repositório (Area de state):
git status

*Mundaça de nomenclatura da Branch principal de master para main

-- Para mudar de master para main:
git branch -M "main"

--Criando a conexão do repositório local com o repositório do GitHub:
git remote add "nome dado para o repositório git" "link do repositório"

--Enviando arquivo para o github:
git push -U "nome dado ao repositório" "nome da branch principal"


*Após realizar alguma alteração nos arquivos

--Mandando todos os arquivos para a área de state:
git add .

--Criação de uma nova Branch e saida da main principal:
git checkout -b "nome da branch"


*Após a criação da nova branch segue o processo normal:
1- git add .
2- git commit -m "nome da nova branch"
3- git push origin "nome da nova branch"

--Para voltar para a branch principal
git checkout main

--Como juntar as duas branchs
git merge nome da branch que quer juntar


--Clonando repositório 
1- Copiar link do repositório
2- Criar nova pasta local
3- Botão direito gitbash here
4- No terminal -> git clone link do repositório

*Se após o clone tiver sido feito alguma alteração no repositório 

--Atualizar o projeto clonado
1- Entrar no projeto clonado -> cd nome do projeto 
2- git pull

