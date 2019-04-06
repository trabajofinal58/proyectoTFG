Aqui podemos ir poniendo los cambios/avances que vayamos haciendo en la aplicación.

---------------------------------------------

Insertados cambios en las activities de alojamiento y usuarios.  
Ya funcionan los intent.  
Guarda, borra y consulta de hoteles.  
Guarda y borra usuarios (aunque no haga falta).  
Hay ejemplos válidos de casteo de fecha (Date) a string.  
Sigue sin funcionar la autentificación.  
Hay que revisar el autoincrementado del código de usuario, porque siempre pone 0 y no se incrementa.  
Hay un Navigation hecho (aunque falta por poner los intent para que salgan las pantallas correspondientes) pero no se como sacar ese menu deslizando desde el emulador.  
**24/03/2019**  

Hecha la actividad de insertar actividades (que de poco sirve, porque es para añadirlas, no para consultarlas).  
Preparadas actividades de viajes, consulta de hoteles e interfaz (una que muestre un ejemplo de como sería la interfaz presentable).  
Parece que la mejor opción para la interfaz como tal, sería tres grandes ImageButton donde poner los accesos a hoteles, actividades y esas cosas.  
Pero con todo eso tenemos numerosos ejemplos de cosas que podemos ir implementando.  
R: Sigue sin funcionar la autentificación.  
R: Hay que revisar el autoincrementado del código de usuario, porque siempre pone 0 y no se incrementa.  
R: Hay un Navigation hecho (aunque falta por poner los intent para que salgan las pantallas correspondientes) pero no se como sacar ese menu deslizando desde el emulador.  
El ratingBar (lo de las estrellitas para la valoración de algo, sería interesante implementarlo en los hoteles) siempre toma valor 5 tenga el valor que tenga realmente, lo tengo puesto en el de actividades.  
Interesaría poner el tipo de actividades como un combobox, nos sería útil para la búsqueda cuando la tengamos.  
Queda hacer lo de movimientos también.  
**28/03/2019**  
  
Hecha la actividad de consulta de hoteles (falta poner los if para cuando se dejen campos vacíos, pero funcionar funciona).  
R: Sigue sin funcionar la autentificación.  
R: Hay que revisar el autoincrementado del código de usuario, porque siempre pone 0 y no se incrementa.  
R: Hay un Navigation hecho (aunque falta por poner los intent para que salgan las pantallas correspondientes) pero no se como sacar ese menu deslizando desde el emulador.  
Interesaría poner el tipo de actividades como un combobox, nos sería útil para la búsqueda cuando la tengamos.  
Queda hacer lo de movimientos también, pero esto es lo que menos prisa nos corre.   
Solucionado el tema de las estrellas (tanto para estrellas como para valoración), ya coge el valor que debería.  
**29/03/2019**  
  
Hecho el inicio de sesión  
Hecha la activity de registro, pero falta programarla  
R: Hay que revisar el autoincrementado del código de usuario, porque siempre pone 0 y no se incrementa.  
R: Hay un Navigation hecho (aunque falta por poner los intent para que salgan las pantallas correspondientes) pero no se como sacar ese menu deslizando desde el emulador.  
R: Queda hacer lo de movimientos también, pero esto es lo que menos prisa nos corre. 
Preparada actividad de insertar viajes (después pasaría a ser la de consulta), es otro de los objetivos de la próxima tutoría  
**05/04/2019**  
  
Hecha la actividad de registro  
R: Hay que revisar el autoincrementado del código de usuario, porque siempre pone 0 y no se incrementa. (Estoy por descartarlo)  
R: Hay un Navigation hecho (aunque falta por poner los intent para que salgan las pantallas correspondientes) pero no se como sacar ese menu deslizando desde el emulador.  
R: Queda hacer lo de movimientos también, pero esto es lo que menos prisa nos corre.  
R: Preparada actividad de insertar viajes (después pasaría a ser la de consulta), es otro de los objetivos de la próxima tutoría  
Arreglada la consulta de hoteles (si metéis más y no son hoteles (y no tienen estrellas, obviamente), no dejeis lo de estrellas sin nada, poned un 0. Si no lo ponéis, luego falla la consulta a la base de datos).  
Ya está hecho el linear layout de la interfaz, ya se reparten el espacio igual los tres imageButtons.  
Cambios menores en el diseño.  
**06/04/2019**  
