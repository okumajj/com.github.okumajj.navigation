Primeiro commit eu fiz a parte de passar parâmetros na navegação e criei uma rota dinâmica "perfil/(nome}"-
Também ajustei o botão da tela de menu pra navegar já enviando um nome pela URL (usei um valor mockado mesmo) -
A PerfilScreen agora pega esse valor e mostra na tela-

Segundo commit eu implementei o envio de um parâmetro opcional pra tela de pedidos.
Criei a rota "pedidos cliente-(cliente}" usando navArgument e deixei um valor padrão como "Cliente Genérico".
A PedidosScreen foi alterada pra receber esse parâmetro e exibir na tela.