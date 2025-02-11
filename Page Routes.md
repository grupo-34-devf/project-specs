| Ruta                  | Pública | Parámetros                       | Descripción                                                                          |
| --------------------- | ------- | -------------------------------- | ------------------------------------------------------------------------------------ |
| /                     | x       | N/A                              | Página principal (homepage)                                                          |
| /surveys              | x       | N/A                              | Encuestas publicadas                                                                 |
| /surveys/:id          | x       | id: id de encuesta               | Página para responder encuesta si no se ha respondido o resultado si ya se respondió |
| /login                | x       | N/A                              | Iniciar sesión formulario                                                            |
| /register             | x       | N/A                              | Registrarme formulario                                                               |
| /verify?token=""      |         | token: token para validar correo | Link enviado al correo                                                               |
| /app                  |         | N/A                              | Mis encuestas                                                                        |
| /app/create           |         | N/A                              | Crear nueva encuesta                                                                 |
| /app/surveys/:id      |         | id: id de encuesta               | Ver datos de encuesta                                                                |
| /app/surveys/:id/edit |         | id: id de encuesta               | Editar encuesta                                                                      |
| /profile              |         | N/A                              | Mis datos de perfil                                                                  |
