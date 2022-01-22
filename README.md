# DBA

O banco poderá ser criado em qualquer formato desde que SQL, desde que possa ser integrado em sites como heroku, netlify etc. Vocês deverão definir se os dados serão passados via api ou via chamada para o banco de dados.
Vocês deverão criar o banco de dados e as strings SQL para serem passadas para a squad de backend.

Usuário: id (int), name (string), email (string) e password (string).
Tarefa: user_id (int), content (long string), finished (tinyint: 0 ou 1).


Criar SQL para cada item:

*Cadastro*
- Checar se o email está cadastrado.
- Inserir: name, email e password.

*Login*
- Checar se o email está cadastrado.
- Retornar id, email e senha baseado no email passado.

*Dashboard*
-Retornar id, name e email pelo id do usuário passado.
-Retornar todas as tarefas desse usuário.
- Cadastrar tarefa
  - Inserir: user_id, content e finished.
