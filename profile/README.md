# Help Pet - Onboarding

## Sobre o projeto

## Objetivo

## Práticas Git
É aconselhado utilizar o padrão **Conventional Commits**, utilizandos os tipos recomendados abaixo e falando de forma **imperativa**(ex: add, make no lugar de added, made).

### Tipos e descrições principais

- `feat`- Commits do tipo feat indicam que seu trecho de código está incluindo um **novo recurso**.

- `fix` - Commits do tipo fix indicam que seu trecho de código commitado está **solucionando um problema** (bug fix).

- `docs` - Commits do tipo docs indicam que houveram **mudanças na documentação**, como por exemplo no Readme do seu repositório. (Não inclui alterações em código).

- `style` - Commits do tipo style indicam que houveram alterações referentes a **formatações de código**, indentação,  (Não inclui alterações em código).

- `refactor` - Commits do tipo refactor referem-se a mudanças devido a **refatorações que não alterem sua funcionalidade**, como por exemplo, uma alteração no formato como é processada determinada parte da tela, mas que manteve a mesma funcionalidade, ou melhorias de performance devido a um code review.

- `chore` - Commits do tipo chore indicam **atualizações de tarefas** de build, configurações de administrador, pacotes... como por exemplo adicionar um pacote no gitignore. (Não inclui alterações em código)

## Estruturas das branchs
A princípio serão duas branchs:
- **main** - Branch que contem código estável e pronto para merge ao repositório forkado.
- **qa/test** - Branch que contem onde ocorrerem testes para garantir o funcionamento correto antes de fazer merge na main.


Tendo essas duas branchs também haverá branchs para features, baseadas na main para merges na branch qa para testes. Exemplos:
- feat/header
- fix/user-login-endpoint
  
Sendo no front ou back end **Não se deve fazer alterações diretamente nas branchs main e qa**, para isso se deve criar outra branch com base no que será alterado como indicado acima.

## Como rodar o projeto

## Como começar a contribuir

## Tecnologias utilizadas
![alt text](../assets/icons/html-logo.svg)
![alt text](../assets/icons/css-logo.svg)
![alt text](../assets/icons/react-logo.svg)

![alt text](../assets/icons/my-sql-logo.svg)
![alt text](../assets/icons/spring-logo.svg)

## Licença

Este projeto é de uso acadêmico e não possui fins comerciais.
