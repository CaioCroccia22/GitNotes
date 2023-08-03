Projeto para ensinar a usar o GIT

--Inicialização o GIT(criando um repositório para a pasta)
1- Abri a pasta
2- Botão direito
3- GitBash Here
4- git init (Inicialização dentro da Branch Master)

--Dando o primeiro Commit 
1- git add "nome do arquivo" (Manda os arquivos para a area de State)
2- git commit -m "mensagem do commit"

--Verificar o status do repositório (Area de state)
git status

*Mundaça de nomenclatura da Branch principal de master para main

-- Para mudar de master para main
git branch -M "main"

--Criando a conexão do repositório local com o repositório do GitHub
git remote add "nome dado para o repositório git" "link do repositório"

--Enviando arquivo para o github
git push -U "nome dado ao repositório" "nome da branch principal"


*Após realizar alguma alteração nos arquivos
--Mandando todos os arquivos para a área de state
git add .