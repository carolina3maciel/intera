# # Jogadores do Flamengo
> Esse código tem como objetivo demonstrar algumas informações sobre os atuais jogadores do flamengo. Entre elas:
  - Nome
  - Posição
  - URL da foto


  ## Terminal

Windows:

```sh
Node.js Command Prompt
```



## Instruções

1. Abra o Node.js Command Prompt e crie uma nova aplicação Node 
```sh

  mkdir [insira o nome de uma pasta aqui]
  cd [insira o nome de uma pasta aqui]
  npm init
  npm i --save scrape-it
  ```
  
2. Copie o código presente no arquivo "jogadores_flamengo" (https://github.com/carolina3maciel/intera/blob/main/jogadores_flamengo)
3. Abra o Sublime Text ou qualquer outro aplicativo similar
4. Cole o código copiado e salve como index.js
4. Retorne ao Node.js Command Prompt e digite o comando "node index.js" para que todas as informações dos jogadores apareçam no próprio terminal

## Raciocínio Lógico

```sh
Partindo de um conhecimento nulo sobre o tema, o código foi desenvolvido através de três cenários:
- Extensão Web Scraping do Chrome (necessário para entendimento de CSS das informações requeridas)
- Criação do código em json a partir das alterações de um modelo já disponibilizado no github (https://github.com/IonicaBizau/scrape-it)
- Utilização do aplicativo ParseHub como tentativa de automação

```

```sh
# Considerações Finais
A partir de testes realizados, é possível inferir que o código é capaz de entregar os dados solicitados. 
Como forma de aprimoramento do projeto, poderia ser utilizada uma função para replicação automática, 
utilizando como base a página que contém o link de todos os jogadores 

```
