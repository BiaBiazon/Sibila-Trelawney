**Configurando o Git**

♦️Para início de partida, é bom tomar nota de que para vizualizar e definir váriaveis de configuração do Git usamos o comando ($git config).

Váriaveis de configuração essas que ficam armazenadas princípalmente em:
--global (referente a configurações no usuário);
--system(referente a configurações do sistema como um todo, que abriga todos os usuários);
--local(referente a configuração de um repositório em específico)

♦️Agora tendo tudo isso em mente, podemos partir para as configurações iniciais de usuário.

Para **configurar o nome de usuário** é usado o comando (git config --global user.name "username") 
**Confirmação:** (git config --global user.name)Caso o seu nome de usuário tenha sido configurado o Git vai retornar o nosso username.

Já para **configurar o nosso email** usamos um comando muito parecido (git config --global user.email "user.email")
**Confimaçãi:**(git config --global user.email) Caso o seu email tenha sido configurado ele vai ser retornado.

♦Visto isso, vejamos agora um comando para retornar a nossa branch padrão, e logo defronte como mudar seu nome.
-(git config init.defaultBranch)
Para alterar nossa branch, vamos utilizar desse mesmo comando, apenas adicionando o nome desejado.
(git config init.defaultBranch "nome-exemplo")
