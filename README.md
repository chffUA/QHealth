# qHealth

Carlos Ferreira n. 80180
Daniel Silva n. 81724

-------

Para manter as alterações efetuadas na base de dados entre sessões (fechar a app), comentar a linha 33 em LoginActivity.java:

if (Globals.checkIfFirstTime) new DBHandler(this).fakeDB();

No entanto, a aplicação não irá funcionar se esta linha estiver comentada na primeira vez que ela correr nesse dispositivo Android.

-------

Logins:

User: test
Pass: p

(cliente, já tem treinador e plano definidos com todos os tipos de exercício)

User: testetr
Pass: p

(treinador, tem vários clientes)

User: test7
Pass: p7

(cliente sem treinador, tem plano vazio e deve aparecer em Client Approval)

-------

Outros logins:

User: test2
Pass: p2

User: test3
Pass: p3

User: test5
Pass: p5

User: supertrainer
Pass: ps
