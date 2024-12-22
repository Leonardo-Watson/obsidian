
#### Instalar bibliotecas

Separar as dependências de desenvolvimento das dependências de produção.
*Exemplo:*
```
npm install prettier --save-dev

ou

npm install prettier -D
```
![[Pasted image 20241221233853.png]]


#### Fazer um commit sem mensagem

```bash
git commit --allow-empty-message -m ''
```
![[Pasted image 20240924104627.png]]

----------------------------------------------------------------

```bash
git commit -m '.'
```
```bash
git commit -m.
```
![[Pasted image 20240924110603.png]]

#### Git ammend

Git ammend serve para alterar um commit upado anteriormente e emendar uma alteração nova sem criar um novo commit

```
git commit --amend
```

#### Git log

Mostra todos os commits feitos no projeto.

```
git log --stat
```

![[Pasted image 20241221170918.png]]

