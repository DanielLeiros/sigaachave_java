# SigaAChave

## Urls Suportadas

#### Usuário

GET - Retorna todos usuários  
`ip:port/sigaachave/usuarios`

GET - Retorna usuario {id}  
`ip:port/sigaachave/usuarios/{id}`

GET - Retornar reservas do Usuario {id}  
`ip:port/sigaachave/usuarios/{id}/reservas`

POST - Adiciona usuario  
`ip:port/sigaachave/usuarios/adicionar/{nome}+{senha}+{papel}`

PUT - Atualiza usuario {id}  
`ip:port/sigaachave/usuarios/{id}/atualizar/{nome}+{senha}+{papel}`

DELETE - Exclui usuario {id}  
`ip:port/sigaachave/usuarios/{id}/excluir`

#### Reservas

GET - Retorna todas reservas  
`ip:port/sigaachave/reservas`

GET - Retorna reserva {id}  
`ip:port/sigaachave/reservas/{id}`

POST - Adiciona reserva  
`ip:port/sigaachave/reservas/adicionar/{sala}+{data}+{isFixo}`

PUT - Atualiza reserva {id}  
`ip:port/sigaachave/reservas/{id}/atualizar/{sala}+{data}+{status}`

PUT - Atribui reserva {id} a usuario {usuarioId}  
`ip:port/sigaachave/reservas/{id}/usuario/{usuarioId}`

DELETE - Exclui reserva {id}  
`ip:port/sigaachave/reservas/{id}/excluir`
