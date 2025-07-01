Configuração inicial
1- Configurar nome de usuário e e-mail (identidade do autor):

git config --global user.name "Seu Nome"

git config --global user.email "seuemail@exemplo.com"

2- Verificar configurações atuais:

git config --list

Fluxo básico de uso do Git
1. Inicializar um repositório Git

git init

2. Verificar o status dos arquivos

git status

3. Adicionar arquivos para o commit (staging)

git add nome_do_arquivo

git add .

4. Criar um commit (salvar alterações localmente)

git commit -m "Mensagem descritiva do commit"

5. Ver o histórico de commits

git log

6. Trabalhando com branches (ramificações)
Criar uma branch nova:
git branch nome_da_branch

Criar uma branch nova:
git branch

Mudar para outra branch:
git checkout nome_da_branch

Criar e mudar para uma branch nova diretamente:
git checkout -b nome_da_branch

Renomear a branch atual:
git branch -M novo_nome

7. Conectar repositório local com remoto (ex: GitHub)
Adicionar o remoto:
git remote add origin URL_DO_REPOSITORIO

Enviar commits locais para o repositório remoto:
git push -u origin nome_da_branch

8. Puxar alterações do repositório remoto (atualizar local)

git pull origin nome_da_branch



