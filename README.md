BaseURL: https://caregiver-and-pets.herokuapp.com

* São os pontos obrigatórios para a API

POST: /register
 *Email/Password
  return: accessToken / user

Logar usuário 
POST: /login
 *Email/Password
  return: accessToken / user

Cadastrar pedido pendente 
** Necessita autenticação
POST: /request
 *type/name/userId/[lista de pets do dono]

Cadastrar pedido aceito 
** Necessita autenticação
POST: /accepted
 *type/name/userId/[lista de pets do dono]

Buscar Cargiver
** Necessita autenticação
GET: /users

Buscar Pedidos do Caregiver
** Necessita autenticação
GET: /users/{ID_DO_CAREGIVER}?_embed=request

Buscar Pedidos aceitos do Caregiver
** Necessita autenticação
GET: /users/{ID_DO_CAREGIVER}?_embed=acceptedBaseURL: https://caregiver-and-pets.herokuapp.com

* São os pontos obrigatórios para a API

POST: /register
 *Email/Password
  return: accessToken / user

Logar usuário 
POST: /login
 *Email/Password
  return: accessToken / user

Cadastrar pedido pendente 
** Necessita autenticação
POST: /request
 *type/name/userId/[lista de pets do dono]

Cadastrar pedido aceito 
** Necessita autenticação
POST: /accepted
 *type/name/userId/[lista de pets do dono]

Buscar Cargiver
** Necessita autenticação
GET: /users

Buscar Pedidos do Caregiver
** Necessita autenticação
GET: /users/{ID_DO_CAREGIVER}?_embed=request

Buscar Pedidos aceitos do Caregiver
** Necessita autenticação
GET: /users/{ID_DO_CAREGIVER}?_embed=accepted