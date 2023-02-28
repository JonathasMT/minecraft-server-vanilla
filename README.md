UM REPOSITÓRIO SIMPLES DE CONFIGURAÇÃO DE SERVIDOR DE MINECRAFT (VANILLA)

Passo a passo:
- baixe o java e instale;
https://www.java.com/pt-BR/download/manual.jsp
- baixe a versão que deseja no link oficial;
https://www.minecraft.net/pt-br/download/server
- coloque esse arquivo numa pasta (provavelmente o aqruivo se chama server.jar);
- execute o arquivo;
- ao executar deve surgir algumas pastas e aruivos:
	libraries
	logs
	versions
	eula.txt
	server.properties
- abra o arquivo eula.txt;
- altere "eula=false" para "eula=true";
- altere o arquivo server.properties de acordo com o que deseja para o seu servidor,
atente-se principalmente ao campo "server-ip=" que deve ser o ip da maquina que executa o servidor;
- execute novamente o arquivo server.jar;
- se ocorreu tudo bem, uma nova pasta chamada "world" será criada, e os arquivos "banned-ips.json",
"banned-players.json", "ops.json", "usercache.json" e "whitelist.json", podendo variar de acordo com 
a versão do servidor baixado, uma tela deve abrir com um console que mostrará o progresso de carregamento do mapa,
a ultima linha depois do carregamento deverá conter "Done", significando que o servidor está online;
- se tudo estiver correto você deve conseguir localizar o servidor dentro do jogo utilizando
a mesma rede do servidor.

	
