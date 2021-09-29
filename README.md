<h1 align="center">
  <img alt="Bravosul" src="https://i.ibb.co/2nRKbHt/Logo.png" height="40px" />
  <br>
  Full Stack Challenge!
</h1>

A aplicação consiste em um *"sistema"* para listar dados de um determinado **CEP** e que terá como base este [layout](https://www.figma.com/file/VqwjflsvfbxSs3qQsXwBxK/Bravosul-Challenge?node-id=802%3A19);


A ideia de estrutura da aplicação é utilizando o seguinte formato:
* Login/Cadastro (Público);
* Gerenciamento de Informações do CEP (Autenticado);
* README descrevendo como rodar a aplicação (Seja criativo);

> Qualquer funcionalidade extra é bem-vinda ao teste, fique a vontade para propor uma melhoria.


### Pontos que serão avaliados:
* Qualidade e Legibilidade do código;
* Criatividade;
* Modularidade;
* Entendimento do Problema;
* Proposta de Soluçao;


# :bookmark: Objetivos

Criar um usuário e logar no sistema, após logado, consultar dados de um determinado CEP.

Para isso, serão necessários:

* Front-end com base no [layout](https://www.figma.com/file/VqwjflsvfbxSs3qQsXwBxK/Bravosul-Challenge?node-id=802%3A19).
* Back-end para fazer a parte de Cadastro/Login;
* Integração com API do [BrasilAPI](https://brasilapi.com.br/) para listagem de dados do CEP.

> Caso preferir, pode utilizar uma API pública para a parte de Cadastro/Login;

# :hammer_and_pick: Stack

* Usar `React.js`;
* Qualquer `Biblioteca de UI` ou não usar bibliotecas para o layout;
* `Node.js` com `Express` para a parte de autenticaçao ou *API pública*. 

# :1st_place_medal: Extra points:

* Testes unitários;
* Código limpo e organização do projeto;
* Documentação;
  
# :date: Tempo de Entrega?
**48 horas**

# :mailbox_with_mail: Como deve ser entregue?
Através de um repositório público no Github/Gitlab.

# :tada: Endpoints
#### URL de Base
```sh
https://brasilapi.com.br/api
```

#### Listar Dados de um Determinado CEP
```sh
https://brasilapi.com.br/api/cep/v1/{cep}
```

Response do Endpoint
```sh
{
  "cep": "89010025",
  "state": "SC",
  "city": "Blumenau",
  "neighborhood": "Centro",
  "street": "Rua Doutor Luiz de Freitas Melro",
  "service": "viacep"
}
```

### :pushpin: Observações
> Qualquer dúvida que tiver entre em contato, **Boa Sorte!** 🍀
