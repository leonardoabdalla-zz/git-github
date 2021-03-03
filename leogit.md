<!DOCTYPE html>
<html lang="pt-br">
   <head>
       <meta charset="utf-8"/>
       <title><h1>Comandos para git/github</h1></title>
   </head>
   <body>
	<table border="1">
	<tr>
		<td>Windows</td>
		<td>Unix</td>
	</tr>
	<tr>
		<td>-cd</td>
		<td>-cd</td>
	</tr>
	<tr>
		<td>-dir</td>
		<td>-is</td>
	</tr>
	<tr>
		<td>-mkdir</td>
		<td>-mkdir</td>
	</tr>
	<tr>
		<td>-del/rmdir</td>
		<td>-rm-rf</td>
	</tr>
	<tr>
		<td>-cls</td>
		<td>-cls</td>
	</tr>
	<p><h2>Para verificar SHA1</h2><br>
	<h3>TOUCH TEXTO.TXT <! SALVANDO DOCUMENTO NO TERMINAL //-><br>
	OPENSSL SHA1 <! NOME DO DOCUMENTO SALVO //-> TEXTO.TXT</h3><br>
	<h2>Criar um repositório</h2><br>
	<h3>GIT INIT</h3><br>
	<h2>Acessar git</h2>
	<h3>$ git add*</h3><br>
	<h2>Criar commit</h2><br>
	<h3>$ GIT COMMIT -M "COMMIT INICIAL"<br>
	<! SE DER ERRO //-> GIT CONFIG --GLOBAL USER. EMAIL "LEONARDOABDALLADEVELOPER@GMAIL.COM"<br>
	GIT CONFIG --GLOBAL USER.NAME"LEONARDO"<br>
	<! CASO TENHA SIDO NECESSÁRIO REALIZAR A ETAPA DO ERRO, APÓS REALIZAR O PROCESSO, RETORNAR AO COMMIT INICIAL //->
	GIT STATUS</h3><br>
	<h2>enviar para o github</h2><br>
	<h3>$ GIT REMOTE ADD ORIGIN HTTPS://_________<! DIGITAR O LINK DO NOVO DOCUMENTO NO GITHUB //-><br>
	$ GIT PUSH ORIGIN MASTER<br>
	FUNÇÃO $ GIT REMOTE -V<br>
	<br>
	<h2>Conflitos no github</h2><br>
	<h3>Quando um projeto está em linha, sendo alterado por mais de uma pessoa ao mesmo tempo é necessário puxar aquele código para só depois commitar<br>
	$ GIT PULL ORIGIN MASTER
<! DAÍ PRECISA INTEGRAR OS PROJETOS //-><br>
	$GIT STATUS
<! VAI MOSTRAR OS DOIS MODIFICADOS //-><br>
	$GIT ADD*
<! PARA ADICIONAR A STAGE //-><br>
	$GIR COMMIT -M<br>
	$GIT PUSH ORIGIN MASTER</h3><br>
	<h2>Clonar um projeto</h2>
	<h3>$ GIT CLONE HTTPS://.....<br>
	$ LS -A
<! MOSTRAR REPOSITÓRIOS OCULTOS //-><br>
	$ GIT REMOTE -V
<! PARAVERIFICAR A ORIGEM //-></h3></p>
	
   </body>
</html>