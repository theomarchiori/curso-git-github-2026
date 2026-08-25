# Curso TMW Git & GitHub 2026

Um curso para iniciantes aprenderem a trabalhar com versionamento
de código e repositórios remotos com GitHub.

## Fluxo de trabalho git local

1. git checkout -b <nova-branch>
2. cria ou atualiza arquivos
3. git status
4. git add .
5. git status
6. git commit -m "minha mensagem"
7. git checkout main
8. git merge nova_branch

## Fluxo de trabalho GitHub <> Local (projeto próprio ou da sua empresa)

01.git clone <endereço do projeto>
01.git checkout -b <nova_branch>
alterações de arquivos
git status
git add arquivos
git status
git commit -m "nova mensagem"
git push origin <nova_branch>
abrir Pull request no GitHub para main
excluir <nova_branch> origin
git checkout main
git branch -D <nova_branch>

## Fluxo de trabalho GitHub <> Local (projetos open source)

Fork do projeto para seu próprio github
git clone
git checkout -b <nova_branch>
alterações de arquivos
git status
git add arquivos
git status
git commit -m "nova mensagem"
git push origin <nova_branch>
abrir Pull request no GitHub da branch fork para a main do projeto original
excluir <nova_branch> origin
git checkout main
git branch -D <nova_branch>