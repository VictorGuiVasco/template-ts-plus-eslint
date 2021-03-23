# Template ESlint com Typescript
<p>
Estou usando este template que eu criei com base no modelo Standard
</p>

## Como usar?

<p>
Clique em "Use this template" para criar um repositório no seu perfil
</p>

<p>
Logo depois disso, faça um clone do repositório
</p>

```
git clone https://github.com/User/template-ts-plus-eslint.git
```

<p>
Depois de fazer o clone, entre na pasta e instale as dependências
</p>

```
cd template-ts-plus-eslint

npm install
  
  ou

yarn install
```

<p>
Pronto, agora é só você apagar a pasta .github e o README.md
</p>

## O que já tem instalado

* Typescript
* Express + @types/express
* Todas as dependencias sugeridas pelo eslint modelo standard

## VScode

<p>
Caso você use o Visual Studio Code, sugiro que instale as extensões ESlint e EditorConfig
</p>

## Não quero usar Standard
<p>
Caso queira mudar o modelo para Airbnb ou outro modelo, apague o arquivo .eslintrc.json, apague as dependecias do eslint no packege.json e use este comando na raiz do projeto

```powershell
npx eslint --init
```
</p>
