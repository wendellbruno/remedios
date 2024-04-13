A API é protegida por spring security (JWT token). Tenha em mente a necessidade do cadastro de um usuário no banco de dados(Cadastre um usuário via postman ou swagger), para então com o usuário cadastrado poder fazer o login,e após isso pegar o token na devolução do login e autorizar o swagger com o token. Nessa fase todos os métodos estarão livres para acesso.

Uma Api rest para controle de funcionários e medicamentos em um ambiente hospitalar!

Ela tem suporte para:

Cadastrar remédios;

Cadastrar funcionários;

Cadastrar usuários do sistema;

Adicionar ou remover quantidade de medicamentos;

Exclusão direta ou exclusão lógica dependendo da regra de negócio exigida pelo cliente;

Controle de segurança com liberação de requisição só após o login ser realizado e então a requisição passar a possuir o token para enviar como autenticação;

Toda essa implementação possui uma criptografia de senha via Bcrypt visando a segurança da instituição e suas funções!

Tecnologias utilizadas:

-Java;

-SpringBoot;

-TokenJWT;

-Flyway;

-MySql;

-SpringSecurity;

-Bcrypto.
