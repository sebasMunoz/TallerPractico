# TallerPractico
 Taller práctico plan variable de entretenimiento
Andres Maya Rico y Sebastian Muñoz Vasquez
Version de Unreal 4.18.3

YBulletBP y RBulletBP: En estos blueprints encontramos las físicas de la bala y la destrucción después de pasar algunos segundos.

ConeRBP y ConeYBP (originalmente eran conos XD): Se reconoce el objeto con el que esta colisionando y se comparan las variables de color con las de las balas, si estas coinciden los objetos proceden a destruirse ambos, en caso de la bala ser de color contrario solo se destruye la bala, también se le agrega el impulso al objeto y depende de la destruccion de los objetos se le implementaron particulas al final, las particulas utilizadas son las predeterminadas de unreal pero con modificaciones de algunos parametros.
				 
FirstPersonCharacter: En este blueprint se implementó la selección de los colores de las balas con los numeros 1 y 2, y que el disparo fuera con espacio; también se le implementó un delay entre los disparos. Al seleccionar el tipo de bala se reproduce el anim montage que se llama ChangeBullet y hace un emitter con el color de la bala seleccionada, cuando se realiza el disparo se ejecuta el emitter del disparo que muesra humo. Tambien se hace la logica del Timer y se aplica el cast al instance de game over.
		      
FirstPersonExampleMap (Level Blueprint): Se implementa el spawn aleatorio de los objetos desde 4 puntos diferentes en el mapa y que se siga generando cada 4 segundos.

El modelado que se uso fue descargado de mixamo junto con las animaciones X Bot.
Se creo un instance para poner el Game Over
Todos las particulas son las basicas de unreal con valores modificados.
Disparo con espacio, Ctrl para saltar, cambiar balas con 1 y 2.