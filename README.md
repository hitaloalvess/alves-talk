# alves-talk

Real-time chat with basic features on the Discord app

## RF's (Requisitos funcionais)

- Deve ser possível se autenticar
- Deve ser possível que um usuário modifique seu perfil
- Deve ser possível que um usuário exclua seu perfil
- Deve ser possível obter o perfil do usuário logado
- Deve ser possível criar um servidor
- Deve ser possível listar todos os servidores disponíveis
- Deve ser possível excluir um servidor
- Deve ser possível enviar links de convites para um para pessoas se tornarem membros
- Deve ser possível buscar um servidor pelo nome
- Deve ser possível se tornar membro de um servidor
- Deve ser possível atribuir cargos dentro de um servidor
- Deve ser possível deixar de ser membro de um servidor
- Deve ser possível visualizar todas as pessoas participantes de um servidor
- Deve ser possível visualizar as informações de um membro do servidor
- Deve ser possível visualizar o status dos membros do servidor
- Deve ser possível excluir membros de um servidor
- Deve ser possível criar um canal
- Deve ser possível publicar mensagens em um canal
- Deve ser possível editar uma mensagem
- Deve ser possível exluir uma mensagem
- Deve ser possível criar amizades com usuários
- Deve ser possível desfazer amizade com usuários
- Deve ser possível listar todos os amigos
- Deve ser possível listar todos os convites de amizade pendentes
- Deve ser possível enviar mensagens privadas a amigos
- Deve ser possível bloquear um amigo
- Deve ser possível visualizar o status dos amigos


## RN's (Regras de negócio)

- O servidor não pode ser excluído por um membro que não seja o fundador
- Um membro do servidor só pode ser removido por um administrador
- Um cargo só pode ser atribuido por um membro com cargo superior ao que será atribuido 
- Um cargo só pode ser alterado por membros que possuem cargo superiores
- Um canal só pode ser criado por membros administradores
- Um canal só pode ser excluído por um membro administrador


## RNF's (Requisitos não funcionais)

- Os dados da aplicação precisam estar persistidos em um banco de dados PostgreSQL
- O usuário deve poder se autenticar com login social(Github e Google)
- Todas as listas de dados precisam estar paginadas com 20 itens por página
- A comunicação em tempo real deve ser criada utilizando a lib socket.io

