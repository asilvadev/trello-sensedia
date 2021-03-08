<div align="center"><img src="https://d2k1ftgv7pobq7.cloudfront.net/meta/u/res/images/brand-assets/Logos/0099ec3754bf473d2bbf317204ab6fea/trello-logo-blue.png" title="trello" alt="trello" width="350" height="100" />

![GitHub](https://img.shields.io/github/license/asilvadev/QA-automacao-RockLov?style=flat-square)
![Made](https://img.shields.io/badge/Made_with-Coffee-red?logo=coffeescript&style=flat-square)
<br/>
<br/>
<a href="https://www.linkedin.com/in/asilvadev/">
<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" height="25"/>
</a>

</div>
<br/>

## 👨🏽‍💻 Technologies

<p align="left">
<img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/85ec92b476b9e9ef1d1e18cb42f894b6124cee88/icons/ruby.svg" title="ruby" alt="ruby" width="25" height="25" />
<br/>
<img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/85ec92b476b9e9ef1d1e18cb42f894b6124cee88/icons/cucumber.svg" title="cucumber" alt="cucumber" width="25" height="25" />
<img src="https://avatars.githubusercontent.com/u/983927?s=200&v=4" title="selenium" alt="selenium" width="24" height="24" />
<img src="https://img.stackshare.io/service/2595/capybara.png" title="capybara" alt="capybara" width="24" height="24" />
<img src="https://raw.githubusercontent.com/vscode-icons/vscode-icons/1120bad531c928642d2ee49942be079a9fb0519b/icons/file_type_rspec.svg" title="rspec" alt="rspec" width="25" height="25" />
<br/>

<img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/85ec92b476b9e9ef1d1e18cb42f894b6124cee88/icons/gemfile.svg" title="gemfile" alt="gemfile" width="25" height="25" />
<img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/85ec92b476b9e9ef1d1e18cb42f894b6124cee88/icons/yaml.svg" title="yaml" alt="yaml" width="25" height="25" />

</P>
<br/>

## ⚠️ Informação importante

```
Os testes foram feitos com as credenciais abaixo.
Caso deseje realizar os testes com uma conta pessoal, gere sua key e token pelo link: https://trello.com/app-key
(Siga os passos e substitua nas credenciais abaixo dentro do projeto)

key: a86ac064d1b4a80abf11f70f3732bf0d
token: 4f6f133e61aefbeb0b247cbf0a7162916c112b36579fa449cfe038ea5362cd7c
```

```
Por padrão os testes rodam via cucumber em chrome_headless

https://chromedriver.chromium.org/downloads
```

```
Desafio:
→ O usuário deve realizar a autenticação no Trello APIs (obter token de acesso).
→ O usuário deve criar um card e editar esse card.
→ O usuário deve excluir esse card e também as sujeiras geradas por esta automação.
```

## 🛠️ Steps

![image](_/steps.svg)

```
git clone https://github.com/asilvadev/trello-sensedia.git
```

## 📷 Screenshots

```
A imagem mostra o requisição feia por um software de testes de API
~Então o Token Trello é necessario ser gerado manualmente
```

![token](_/trelloAPItoken.png)

```
↓ Cucumber output via terminal ↓
```

![terminal](_/terminal.png)

↓ Para gerar o resport no Allure ↓

```ts
allure serve logs\
```

![allure](_/reportAllure.png)

##
