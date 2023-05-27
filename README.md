# Curso Digital: Git/versionamento

Neste repositório serão abordados comandos básicos para jogar seus projetos no Git Hub. 
Nele são revisados apenas comandos básicos. (git diff, git commit e git push). 
Não serão abordados toda a funcionalidade e básico do Git que deverá ser de forma mais clara em outro repositório. 
Lá serão abordados criação de conta no Git Hub, autenticação e criação de chave SSH. Será ainda abordado sobre a criação de repositórios no Git Hub, inicar um projeto com "git init", adicionando o projeto e atualizações com "git add", e verificando modificações e estado com "git diff" e "git status". Será abordado ainda sobre a criação de clone de um repositório já criado, e trazê-lo para a máquina local com o "git pull". 
Não esquecer do comando "git remote" para remontar um trabalho lançado no Git Hub



## Gravando mudanças no repositório GitHub

Conhecendo o comando "git diff", que mostra exatamente as linhas que foram modificadas. 
No terminal do VSCode a exemplo, as linhas que aparecem em vermelho, indicam que foram modifcadas. As que aparecem em verde, foram adicionadas. 


git push
git pull
git fetch

Trbalhando com branches 

comandos para desenvolver códigos em paralelo, com equipes por exemplo

git branch
git checkout master -> ir para a branch master
git checkout testing -> ir para a branch testing
git checkout main -> irt para a branch main



Trabalhando com merge

Arquivos .
gitignore  usados para ignorar arquivos específicos. 

Para adicionar itens que se encontram em branches diferentes 
trazer arquivos da branch testing para a brach master usa-se os comandos: 

git checout master (entrar na branch master)
git merge testing (trazer aarquivos da branch testing para a branch master)