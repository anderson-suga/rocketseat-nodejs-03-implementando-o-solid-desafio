# Desafio 03

Desafio referente ao módulo: API Node.js com SOLID

## Introdução

Faaala Dev,

Nesse desafio você reforçará de forma prática os **conceitos** que aprendemos nesse módulo.

Como se trata de um desafio, ele necessita de alguns conhecimentos além dos abordados nesse módulo, então é importante ter autonomia para conseguir pesquisar essas coisas caso não saiba como resolver. Por isso, lembre-se, t**enha calma** e **acredite no seu processo.**

O aprendizado daqui é muito importante e com certeza você conseguirá sair com muito conhecimento bacana 💜

## Sobre o desafio

<aside>
⚠️ Como dissemos anteriormente, <b>não</b> vamos mais informar detalhadamente rotas e propriedades dos registros a serem criadas, mas sim, as regras e requisitos que a API deve ter.
</br></br>
O motivo disso é para vocês <b>também</b> exercitarem o desenvolvimento e a estruturação dessa parte.
</br></br>
</aside>

Nesse desafio desenvolveremos uma API para a adoção de animais, a FindAFriend API, utilizando SOLID e testes.

### Regras da aplicação

- Deve ser possível cadastrar um pet
- Deve ser possível listar todos os pets disponíveis para adoção em uma cidade
- Deve ser possível filtrar pets por suas características
- Deve ser possível visualizar detalhes de um pet para adoção
- Deve ser possível se cadastrar como uma ORG
- Deve ser possível realizar login como uma ORG

### Regras de negócio

- Para listar os pets, obrigatoriamente precisamos informar a cidade
- Uma ORG precisa ter um endereço e um número de WhatsApp
- Um pet deve estar ligado a uma ORG
- O usuário que quer adotar, entrará em contato com a ORG via WhatsApp
- Todos os filtros, além da cidade, são opcionais
- Para uma ORG acessar a aplicação como admin, ela precisa estar logada

### Contexto da aplicação

É comum ao estar desenvolvendo uma API, imaginar como esses dados vão estar sendo utilizados pelo cliente web e/ou mobile.

Por isso, deixamos abaixo o link para o layout da aplicação que utilizaria essa API.

https://www.figma.com/community/file/1220006040435238030
