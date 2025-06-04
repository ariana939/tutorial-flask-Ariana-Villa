# tutorial-flask-Ariana-Villa
<!--notas
'gitignore' sirve para ignorar ciertos archivos
'g' es unico y permite separar, es unico para cada usuario y cuando termina el usuario se tira (esta g)(esta en el tutorial).
'gitdb' ejecuta el archivo.
'with' abre, pone nombre, ejecuta el codigo y lo cierra(se cierra solo, es automatico).
'blueprint'organiza un grupo de vistas(por abecedario, a,b,c,)y codigos relacionados.
'prefix'es una pedazo que se agrega a la ruta 

28-5
cookis informacion que el servidor guarda en el navegador
g para guardar variables existe hasta que termina es request 
la sesion existe hasta que se deslogea
que pasa si borro de la base de datos el usuario que esta logeado??
pregunta trampa: porque cuanod borro la cookies sigue apareciendo como logeado?,
porque el navegador no se entra y hay que recargar la pagina
pregunta trampa: si no estoy logeando puedo ver la pagina?,  
que queda en g.user si borro el usuario de la base de datos? devuelve una lista vacia, none
que pasa si alguien borra el usuario y alguien crea un usuario con el mismo id? no se reusan los id,
asi que queda borrado
como deslogeo al usuario? session.clear()
para que sirve una plantilla? datos estaticos y dinamicos 
que hace el extends? se basa en la anterios pero agrega cosas
estructura: 3 puntos va a poder cambiar el contenido, titulo y header
la plantilla principal debe difinir los bloques donde se puede rellenar codigo
paso a paso de un render post:
title pone ponst
link..
ruta de index url /barra
if...
/auth/logout
agarra block header y ignora el block title
div no pone niguno(for esta vacio, no hay nada que mostrar)
si hay uno solo post 
base copia, reemplazo
>
04/06
explico la pagina de git y los cuadros del archivo
tutorial flask:
un protocolo dns, ruta  
200 todo bien
302 una reedireccion
304 no modifcado css no modificado
404 no encontrado, algo esta mal
500 algo mal en el servidor 

