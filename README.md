# TallerPractico
 Taller práctico plan variable de entretenimiento
Andres Maya Rico y Sebastian Muñoz Vasquez
Version de Unreal 4.18.3

YBulletBP y RBulletBP: En estos blueprints encontramos las físicas de la bala y la destrucción después de pasar algunos segundos.

ConeRBP y ConeYBP (originalmente eran conos XD): Se reconoce el objeto con el que esta colisionando y se comparan las variables de color con las de las balas, si estas coinciden los objetos proceden a destruirse ambos, en caso de la bala ser de color contrario solo se destruye la bala, también se le agrega el impulso al objeto.
				 
FirstPersonCharacter: En este blueprint se implementó la selección de los colores de las balas con los numeros 1 y 2, y que el disparo fuera con espacio; también se le implementó un delay entre los disparos.
		      
FirstPersonExampleMap (Level Blueprint): Se implementa el spawn aleatorio de los objetos desde 4 puntos diferentes en el mapa y que se siga generando cada 4 segundos.

El modelado que se uso fue descargado de mixamo junto con las animaciones.
Se creo un instance para poner el Game Over
Reload es el anim montage y se reproduce dentro del personaje al presionar 1 y 2.
