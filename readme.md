## Erros para corrigir:
 - [x] hould be able to find user by username in header and pass it to request.user
 - [x] should not be able to find a non existing user by username in header
 - [x] checksCreateTodosUserAvailability › should be able to let user create a new todo when is in free plan and have less than ten todos
 - [x] Should not be able to let user create a new todo when is not Pro and already have ten todos
 - [x] checksTodoExists › should be able to put user and todo in request when both exits
 - [x] Should be able to let user create infinite new todos when is in Pro plan
 - [x] Should be able to put user and todo in request when both exits
 - [x] Should not be able to put user and todo in request when user does not exists
 - [x] Should not be able to put user and todo in request when todo id is not uuid
 - [x] Should not be able to put user and todo in request when todo does not exists
 - [x] Should be able to find user by id route param and pass it to request.user
 - [x] Should not be able to pass user to request.user when it does not exists

 Restaram alguns problemas mas relacionas aos testes não listados, aparentemente estavam dando timeout, mas por no notion informar que não era necessário modificar as rotas mantive esses testes!