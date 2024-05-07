# DIO | Resumos Git e Github

Repositório para armazenar resumos sobre Git e Github do curso Versionamento de Códigos com Git e Github da [Digital Innovation One](https://www.dio.me/users/dsanmike12).

## 📚 Documentação

- [Documentação Git](https://git-scm.com/doc)
- [Documentação Github](https://docs.github.com).

## 💻 Resumo das Aulas

```
 
 Git é um sistema de Controle de versão Distribuido
Version Control System - VCS [Sistema de Controle de Versão]

 O que é Versionamento de código? 
O versionamento de código, também conhecido como controle de versão, é uma prática que consiste em acompanhar e registrar todas as 
alterações feitas nos arquivos de código-fonte de um projeto ao longo do tempo
```
```
 {...} Gratuito e Open Source (Codigo Aberto)
```
- Site Oficial do Git -> [Git](https://git-scm.com/)

| Comandos | Resumos |
|------|----------|
|mkdir | Criar pastas -> mkdir nome-da-pasta|
| git clone | Clone o projeto -> git clone https://link-para-o-projeto|
| git clone URL name| Clone o projeto com um nome desejado para a pasta -> git clone https://link-para-o-projeto nome-da-pasta|
| cd | Entre no diretório do projeto -> cd my-project|
| cd .. |Voltar para a pasta anterior (uma pasta) -> cd ..|
|git config -- global user.name|Para configurar o nome do desenvolvedor do projeto -> git config -- global user.name "nome-do-desenvolvedor" |
|git config -- global user.email|Para configurar o email do desenvolvedor do projeto -> git config -- global user.email "email-do-desenvolvedor" |
|git config user.name|Para verificar se foi configurado tudo certo. -> git config user.name |
|git config user.email|Para verificar se foi configurado tudo certo. -> git config user.email |
|git config init.defaultBranch | Para verificar qual a branch padrao -> git config init.defaultBranch |
|git config --global init.defaultBranch main |Para alterar a Branch para main -> git config --global init.defaultBranch main|
|git config --global credential.helper cache|Para salvar a senha token(Chave) temporariamente -> git config --global credential.helper cache|
|git config --global credential.helper store|Para salvar a senha token(Chave) Permanentemente -> git config --global credential.helper store|
|git config --global --show-origin credential.helper | Saber onde o Git Bash armazena essas chaves. -> git config --global --show-origin credential.helper|
|cat .gitconfig| Saber o que tem dentro dos arquivos -> cat .gitconfig|
|cat .git-credential| Ver as senhas(chaves) tokens armazenadas -> cat .git-credential|
|npm install | Instale as dependências -> npm install | 
| npm run start | Inicie o servidor -> npm run start| 
| . | Para abrir o editor do proprio Github utilizar o . (ponto) do proprio teclado.| 


## Instalação

Instale my-project com npm

```bash
  npm install my-project
  cd my-project
```
    

## 🔍 Referências
- [Digital Innovation One](https://www.dio.me)
