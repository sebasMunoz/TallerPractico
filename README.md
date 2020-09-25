# TallerPractico
 Taller practico plan variable de entretenimiento
Andres Maya Rico y Sebastian Muñoz Vasquez
Version de Unreal 4.18.3

YBulletBP y RBulletBP: En estos blueprints encontramos las fisicas de la bala y la destruccion despues de pasar algunos segundos.

ConeRBP y ConeYBP (originalmente eran conos XD): Se reconoce el objeto con el que esta colisionando y se comparan las bariables de color con las de las balas si estas coinciden los objetos proceden a destruirse ambos, en caso de la bala ser de color contrario solo se destruye la bala, tambien se le agrega el impulso al Objeto.
				 
FirstPersonCharacter: En este blueprint se implemento la seleccion de los colores de las balas con los numeros 1 y 2 y que el disparo fuera con espacio, tambien se le implemento un delay entre los disparos.
		      
FirstPersonExampleMap (Level Blueprint): Se implementa el spawn aleatorio de los objetos desde 4 puntos diferentes en el mapa y que se siga generando cada 4 sgundos.