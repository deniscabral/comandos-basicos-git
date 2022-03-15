# Comandos Básicos do Git

### Descrição

Esta é uma anotação de comandos básicos do Git. <br>

<p> O Git é um sistema de controle de revisão distribuído, rápido, escalável, e com um conjunto de comandos incomumente rico que oferece operações de alto nível e acesso completo aos seus recursos. (Fonte: https://git-scm.com/docs/git/pt_BR) </p>

Os comandos citados nesta anotação fazem parte da Documentação (Referência) do site https://git-scm.com/docs/git/pt_BR. <br>

Este guia é recomendado para iniciantes no uso do Git. <br>

Bom estudo e aproveite para colaborar com esta anotação!  <br>



**Primeiros comandos:**

- Imprime a versão do pacote Git instalada exibindo a sua origem. <br>
  	**git --version** <br>

- Imprime a sinopse e uma lista dos comandos mais usados. <br>
  	**git --help** <br>



**OS COMANDOS DO GIT**

<p>Dividimos o Git em comandos de alto nível ("porcelana") e de baixo nível ("encanamento").

Separamos alguns comandos porcelana nos comandos principais e em alguns utilitários auxiliares do usuário. </p>

Alguns dos principais comandos porcelana: <br>

- Cria um repositório vazio para o Git ou reinicializa um repositório já existente. <br>
  	**git init nome-do-repositório** <br>

- Adiciona o conteúdo dos arquivos ao índice. <br>
  	**git add .** <br>

- Grava as alterações para o repositório e adiciona uma mensagem. <br>
  	**git commit -m "mensagem"** <br>

- Atualiza os repositórios remotos através da associação dos objetos, na branch main. <br>
  	**git push origin main** <br>

- Capture do repositório remoto e o integre com um outro repositório local. <br>
  	**git pull** <br>