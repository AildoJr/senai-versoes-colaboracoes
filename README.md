# senai-versoes-colaboracoes
Repositório de versões e colaborações

Comandos importantes para utilização do Git:

git config --global user.name "nome do usuário" /*Define o nome de usuário do git*/

git config --global user.email "usuario@email.com" /*Define o email do usuário do git*/

git init /*Cria a estrutura inicial do Git no computador*/

git add arquivo.txt /*Adiciona o arquivo.txt ao staging*/

git add . /*Adiciona todos os arquivos ao staging*/

git status /*Verifica o status das alterações realizadas no repositório*/

git commit -m "descrição das alterações realizadas pelo commit" /*Salva as alterações feitas*/

git log /*Exibe todas alterações feitas no repositório. Aperte 'q' para encerrar*/

git show 4a83ec015a4dae8693e8b62c45c8a4e644bf91f1 /*Exibe as alterações feitas pelo commit de nome "4a83ec015a4dae8693e8b62c45c8a4e644bf91f1"*/

git remote add origin https://github.com/usuario/repositorio.git /*Liga o repositório local ao repositório online do usuário*/

git remote -v /*Visualiza as informações do repositório online*/

git push -u origin master /*Publica as alterações no repositório remoto*/

git pull /*Baixa as alterações de um repositório remoto*/

git clone https://github.com/usuario/repositorio.git /*Clona o repositório do usuário*/

git checkout -b tarefa /*Cria uma branch nova chamada tarefa*/

git checkout master /*Retorna a master*/

git merge tarefa /*Mescla a branch atual com a branch tarefa*/

git pull origin tarefa /*Baixa as alterações da branch tarefa*/

git tag –a v1.0 –m "minha primeira tag" /*Cria uma tag*/

git tag /*Visualiza as tags criadas*/

git push origin --tags /*Publica tags no repositório remoto*/
