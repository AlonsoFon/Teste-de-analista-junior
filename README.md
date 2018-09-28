# Teste-de-analista-junior
Projeto de testa para uma vaga de analista junior

O projeto foi desenvolvido em laravel 5.6, com o uso do template da wrappixel pois tem varios itens do front end
prontos e julgo ser tempo desperdiçado pensar em uma nova solução sendo que já existe algo pronto.

Instruções para rodar o projeto:

1- Tenha o ambiente laravel 5.6 com php 7.1 ou superiores instalados em sua maquina

2- Tenha o wamp ou xamp em pleno funcionamento na sua maquina

3- Faça o download do projeto de descompacte no local de sua preferencia

4- Apos descompactar, acesse a pasta pelo terminal, e na raiz do projeto execute o comando "composer update"

5- Ainda na pasta raiz do projeto, encontre o arquivo ".env" e verifique se os dados de conexão com o banco mysql conferem com seu local host.

6- Ainda na pasta raiz do projeto, execute os comandos "php artisan migrate" e "php artisan serve"

7- Apos esses comando serem executados, será criado no banco as tabelas necessarias para pleno funcionamento do sistema
e o site estará pronto no "http://localhost:8000/" ou "http://localhost:8000/login", acesse!.

8- Ao acessar irá visualizar a tela de login onde tem a opção de recuperação de senha que não foi implementada (para projeto futuro).

9- Também terá o link para acessar a pagina de cadastro e os campos para informar seu login e senha caso já possua um cadastro,
como você não possui cadastro, clique em cadastrar-se.

10- A pagina de cadastro será carregada, nessa pagina terá de preencher todos os campos com (*) que são as informações principais de seu cadastro

11- Não foi implementado o retorno de valores para os campos endereço e filmes, caso você clique em cadastrar e alguma das informações requeridas
estejam incorretas. 

12- Não foi implementado o verificador de telefones (pelo fato de atrapalhar o usuario a se cadastrar nesse momento de teste).

13- Não foi implementado o verificador de rg para saber se é valido.

14- O verificador de CPF validos foi implementado, então caso deseje se cadastrar terá que inserir um cpf valido.

15- Você pode inserir nenhum ou varios endereços (considerei que obrigar o usuario a inserir um endereço seria desperdicio);

16- Você pode inserir nenhum ou varios filmes.

17- Para inserir novos campos de filme e endereços é necessario que todos os campos referentes a esses elementos estejam preenchidos e clicar no 
botao + e para excluir basta clicar no botao -

18- Apos todos os dados inseridos corretamente clique em cadastrar, o cadastro será efetuado e você redirecionado para tela de login
com um alerta de que foi tudo um sucesso.

19- Projeto futuro permitir que o usuario suba uma imagem de perfil.

20- Agora que você já possui um login, efetue o login e sejá redirecionado para a pagina index.

21- No topo da pagina index você verá alguns elementos não implementados.

22- Tem um carrosel que o sentido dele seria o usuario mandar um email para o adm do sistema com duvidas, sugestões ou reclamações
mas não esta implementado.

23- Tem uma aba de notificações para usuario ver novidades do sistema (não implementado).

24- Tem uma aba de mensagens para que o adm possa mandar msgs para os usuarios (não implementado).

24- Tem uma opção de escolha de linguagem caso queira fazer o site para mais de um idioma (não implementado).

25- Tem a foto do usuario, ao clicar nela é possivel ver novos menus e as informações do usuario email e nome.

26- Os menus na foto do usuario são editar perfil, alterar senha e logout.

27- Ao clicar em logout a sessão é destruida e o usuario volta a tela de login.

28- Ao clicar em editar perfil, o usuario será redirecionado para a pagina de edição do perfil onde pode alterar todas as infos do seu cadastro
(seria ideal ter feito a alteração de endereços e filmes em outra pagina, mas não tive tempo).

29- Ao clicar em alterar senha o usuario será redirecionado para a pagina de alteração de senha onde pode mudar sua senha.

30- Na dashboard abaixo do header temos 3 abas, pagina inicial, adicionar novos filmes e adicionar novos endereços.

31- Clicando na aba pagina inicial o usuario será redirecionado para pagina index.

32- Ao clicar em adicionar novos filmes o usuario será redirecionado para pagina de adição de novos filmes
onde poderá, se preencher as informações corretamente, adicionar mais filmes ao seu cadastro.

33- Ao clicar em adicionar novos endereços o usuario será redirecionado para pagina de adição de novos endereços
onde poderá, se preencher as informações corretamente, adicionar mais endereços ao seu cadastro.

34- No corpo da pagina index (inicial) temos duas tabelas respectivamente: Usuarios do sistema e meus filmes.

35- Na tabela usuarios do sistema eu trago as informações de nome, email, endereço principal e dois botões, visualizar mais endereços
e visualizar filmes. não coloquei demais informações por achar ser algo confidencial do usuario, apesar de considerar
o endereço confidencial também.

36- Ao clicar em visualizar mais endereços é aberto um modal com os demais endereços daquele usuario (tirando o principal).

37- Ao clicar em visualizar mais filmes é aberto um modal com todos os filmes daquele usuario. 

38- A tabela Seus filmes tem apenas o intuido do usuario visualizar seus filmes (poderia ser feito uma seus endereços caso fosse necessario
mas não foi implementado).

39- Ambas as tabelas tem um elemento pesquisar fornecido pelo template, o qual filtra as linhas que possuem elementos semelhantes a da pesquisa.

40- Tem muitas funcionalidades e questões de front end que poderiam ser melhoradas ou implementadas, mas devido ao pouco tempo de projeto não foi possivel.

