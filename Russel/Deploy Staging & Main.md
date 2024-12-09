
### Deploy de teste staging
Após testar a funcionalidade na staging e caso não vá subir ainda para produção é preciso fazer um ``````
```
git checkout main
git branch -D staging

# Criar uma nova branch staging baseada na main atual.
git checkout -b staging main

# Faz um push force para deixar a staging igual a main.
git push -f --set-upstream origin staging

# Fazer um Create Deployment manual na vercel baseado na nova staging do github.
```

### Deploy para main
```
git checkout main
git merge staging

# Adicionar a versão e a mudança que foram feitas ao CHANGELOG
git add CHANGELOG.md

git commit -m ":books: docs: CHANGELOG"

# Adicionar a tag ao commit
git tag -a v4.0.2 -m "Resumo do CHANGELOG" HEAD

# Fazer o push do CHANGELO e das tags
git push origin main
git push --tags
```
