El programa pide ingresar la url del juego a "estudiar" si el juego da profit por comprarlo y luego obtener los cromos del mismo y venderlos en el mercado de steam,
Para que el programa funcione correctamente es recomendable obtener los links de los juegos desde el siguiente buscador de steam : 
https://store.steampowered.com/search/?sort_by=Price_ASC&category2=29&os=win&filter=topsellers 
el cual ya esta puesto para que filtre los juegos mas baratos y con cromos.
Si va a ingresar solo un juego no hace falta que ingrese una coma , si va a ingresar 2 o mas tiene que separarlo entre comas
El programa Informa del precio del juego.
Luego informa si hubo algun error al obtener los precios de todos los cromos , si hubo error informa sobre que cromo hubo error(esto puede ser causado o por un tema de steam que
tiene un limite a la cantidad de peticiones que se le puede hacer a los servidores (por eso esta lo de la espera de 10 segundos)(hay que resaltar que steam tiene un limite de 
peticiones diarias de unas 10000 , y cada cromo que el programa lee es una peticion(suponiendo el peor caso posible osea que cada juego que quieran leer tenga 15 cromos , podrian 
leer por dia hasta 666 juegos)) o por cromos con caracteres raros).
Luego informa el cromo de mayor valor y el de menor valor y la diferencia entre ellos (hay juegos que tienen algun cromo a 30ars pero el resto a 1ars entonces puede ser un falso 
positivo).
Luego informa lo que se obtendria vendiendo los cromos (ya incluidas las fees de steam por vender en el market (que son del 13%))
Luego el profit total (lo que se obtendria menos lo que cuesta el juego).
Luego informa sobre la cantidad de cromos que se vendieron en las ultimas 24hs (el volumen), para ver si ademas de ser profit , los cromos se venden rapido o no.
Luego va a resaltar los juegos que sean profit de los que no sean profit y va a poner algunas indicaciones dependiendo si se venden muchos o pocos cromos, como tambien 
advirtiendo de la diferencia de precio del cromo de mayor valor y el menor.