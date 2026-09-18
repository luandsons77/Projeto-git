# projeto-git-laboratorio

Laboratório prático da disciplina Back-end Frameworks.

## Participantes
- Participante 1: PREENCHER NOME
- Participante 2: PREENCHER NOME

## Comandos da atividade

```bash
git --version
git config --global user.name "SEU NOME"
git config --global user.email "SEU EMAIL"

git init
git status
git add .
git commit -m "Criação inicial do projeto"
git log --oneline

git status
git add .
git commit -m "Adiciona nova seção ao projeto"

git status
git add .
git commit -m "Atualiza estrutura do projeto"

git diff
git add .
git status
git diff --staged
git commit -m "Atualiza conteúdo do projeto"

git log --oneline
git show ID_DO_COMMIT
git revert ID_DO_COMMIT
git status
git log --oneline

git remote add origin URL_DO_REPOSITORIO
git remote -v
git branch
git branch -M main
git push -u origin main
```

## Observação sobre o revert

O `git revert` não apaga o commit original. Ele cria um novo commit que desfaz as alterações do commit escolhido.
