# Help Pet - Onboarding

## Sobre o projeto

## Objetivo

## Práticas git e github
É aconselhado utilizar o padrão **Conventional Commits**, que consiste dos tipos recomendados abaixo e falar de forma **imperativa** (ex: add, make no lugar de added, made).

### Tipos e descrições principais

- `feat`- Commits do tipo feat indicam que seu trecho de código está incluindo um **novo recurso**.

- `fix` - Commits do tipo fix indicam que seu trecho de código commitado está **solucionando um problema** (bug fix).

- `docs` - Commits do tipo docs indicam que houveram **mudanças na documentação**, como por exemplo no Readme do seu repositório, (Não inclui alterações em código).

- `style` - Commits do tipo style indicam que houveram alterações referentes a **formatações de código**, indentação,  (Não inclui alterações em código).

- `refactor` - Commits do tipo refactor referem-se a mudanças devido a **refatorações que não alterem sua funcionalidade**, como por exemplo, uma alteração no formato como é processada determinada parte da tela, mas que manteve a mesma funcionalidade, ou melhorias de performance devido a um code review.

- `chore` - Commits do tipo chore indicam **atualizações de tarefas** de build, configurações de administrador, pacotes... como por exemplo adicionar um pacote no gitignore. (Não inclui alterações em código)

### Pull requests
Siga os mesmos padrões mencionados acima, apenas com o tipo de pull request em letra maiúscula e entre colchetes.

 - Exemplos:
    - [FEAT] Add CRUD methods to user.
    - [HOTFIX] issue #13 <- hotfix é um tipo específico para pull requests, sendo para problemas no código que precisam de conserto imediato.

## Estrutura das branchs
A princípio serão duas branchs:
- **main** - Branch que contém código estável e pronto para merge ao repositório forkado.
- **qa/test** - Branch onde ocorrerem testes para garantir o funcionamento correto do código antes de ser feito o merge na main.


Tendo essas duas branchs também haverá branchs para features, baseadas na main para merges na branch qa para testes. Exemplos:
- feat/header
- fix/user-login-endpoint
  
Sendo no front ou back end, **não se deve fazer alterações diretamente na branch main**, para isso se deve criar outra branch com base no que será alterado como indicado acima.

## Como começar a contribuir
> Siga os passos abaixo e leia a seção como contribuir da documentação dos repositórios front e back do seu grupo para saber exatamente como contribuir ao projeto.

### Equipes
Equipes são uma forma de organizar repositórios de uma forma que cada grupo terá visibilidade de todos os repositórios mas apenas controle total dos seus próprios.

### Workflow (fluxo de trabalho)
1. Ao entrar nos repositórios da sua equipe você deve clonar o repositório na sua máquina.
2. Criar uma branch baseado no que você pretende contribuir como nos exemplos na seção acima.
3. Ao finalizar, por exemplo, uma feature nesta branch faça um merge na branch **qa/test** onde serão feitos testes.
4. O seu **tech lead** deverá realizar o merge na branch **main** através de uma pull request.


## Como rodar o projeto

### Front-end
1. Clone o repositório. 
2. Abra o terminal dentro da pasta.
3. Instale as dependências do projeto com o comando `` npm install ``.
4. Inicie o projeto com o comando `` npm run dev `` para rodar localmente.

### Back-end
1. Clone este repositório.
2. Entre na pasta utilizando Intellij para que a dependência **lombok** funcione corretamente.
3. Verifique que o banco de dados está configurando corretamente em `` application properties ``.
4. Rode o arquivo `` HelpPetApplication.java ``.

### Como conectar
É possível testar a resposta do endpoint no front utilizando fetch.

Exemplo:
```jsx
fetch("http://localhost:3000/api/users")
  .then(res => res.json())
  .then(data => console.log(data));
```
**É aconselhado testar os endpoints no postman antes de fazer esta integração.**


## Tecnologias utilizadas

### Front-end
![alt text](../assets/icons/html-logo.svg)
![alt text](../assets/icons/css-logo.svg)
![alt text](../assets/icons/javascript-logo.svg)
![alt text](../assets/icons/react-logo.svg)
![alt text](../assets/icons/vite-logo.svg)

### Back-end
![alt text](../assets/icons/java-logo.svg)
![alt text](../assets/icons/spring-logo.svg)

### Banco de dados
![alt text](../assets/icons/my-sql-logo.svg)

## Licença
Este projeto é de uso acadêmico e não possui fins comerciais.
