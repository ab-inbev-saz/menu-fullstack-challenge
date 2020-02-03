<p align="center">
  <img src="https://menu.com.vc/media/store/logo/websites/1/Imagem1.png" width="200">
</p>

# Desafio Full Stack

Esse desafio tem como objetivo testar seu domínio sobre Desenvolvimento Full Stack: organização, boas práticas, APIs, conhecimento em frameworks e suas tecnologias.

## Regras

- Para expôr seus endpoints utilize de preferência um framework web simples e leve;
- Não utilize boilerplates, gostamos de ver como você organiza seu código;
- Fique a vontade para escolher o banco de dados que achar melhor;
- Utilize uma das seguintes linguagens no back-end: PHP, Python ou NodeJS;
- Utilize um dos seguintes frameworks no front-end: ReactJS ou VueJS;
- Dockerize seu ambiente. Isso facilitará para quem está corrigindo seu teste.

## O desafio

### Front-end

- O front-end deve conter 3 telas simples para exibição reativa dos dados (Dashboard, Pedidos e Clientes). Não se preocupe com a estilização, não será um critério de avaliação. Certifique-se apenas que as informações estejam legíveis e as ações necessárias estejam disponíveis. Sugerimos utilizamos algum framework CSS (ex.: Bootstrap, Bulma, Tailwind, etc.) para facilitar o trabalho. **Exemplo** de tela para Dashboard:

<p align="center">
  <img src="https://i.imgur.com/qHPJ8NO.png" width="600">
</p>

### Back-end

- **API Rest**

  - /pedidos (GET, POST)
  - /pedidos/:id (GET, PUT, DELETE)
  - /clientes (GET, POST)
  - /clientes/:id (GET, PUT, DELETE)

- **Contratos:**

  - O recurso de "pedidos" deve conter:

    - Data do pedido
    - Status do pedido
    - Cliente correlacionado do pedido
    - Valor do pedido

  - O recurso de "clientes" deve conter:
    - Primeiro nome
    - Último nome
    - E-mail

## Como avaliaremos?

- Seu código é fácil de ler e entender;
- Seu código utiliza boas práticas de desenvolvimento de software;
- Seu código possui testes automatizados incluindo testes unitários, testes integrados e testes end-to-end;
- Seu código retona códigos de erros claros e descritivos;
- Conseguimos subir o ambiente com as instruções no README.

Não é obrigatório ter todos os itens concluídos na entrega.

## Como entregar?

Não faça um fork desse projeto. Crie um repositório no seu perfil do GitHub e nos envie a URL.