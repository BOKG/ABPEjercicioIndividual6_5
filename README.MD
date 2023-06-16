# EJERCICIO 6_5 - LOGIN/LOGOUT GUIDO SAAVEDRA

# REQUERIMIENTOS:

Continuando con el trabajo anterior. Desarrollen la funcionalidad de login/logout en su página web.
Recuerde incorporar los contenidos de las cápsulas. Desarrolle un template para el login y un template
que debe mostrarse luego de que el usuario ha iniciado sesión.
El template que se muestra luego del inicio de sesión debe indicar el nombre del usuario. El nombre
debe estar formateado en un mensaje de bienvenida.

Realice al menos dos tipos de restricciones de acceso. En un archivo README.txt debe indicar todas las
características de estas restricciones.
Trabaje en el archivo README, con la finalidad de describir de forma detallada el funcionamiento de su
aplicación, su objetivo y toda la información que considere relevante.
Personalice los aspectos que considere necesarios del Login.
Actualice su proyecto en GITHUB.
Suerte!

# APLICACION

Debido a haberme extendido en el ejercicio anterior se cumple los requerimientos de el ejercicio actual a mi parecer
por ende no habria modificaciones en el codigo pero si se realiza el readme solicitado


#  ESPECIFICACIONES

En un principio mi aplicacion esta enfocada principalmente en cubrir los requerimientos de la practica, por ende se basa en 
un login y un logout, en el cual se puede acceder a la pagina principal de la aplicacion, en la cual se puede ver un mensaje de bienvenida personalizado
para el usuario que se logueo, con el debido loguout, se aplicaron tambien las correctas practicas, para el redireccionamiento de las paginas, y el uso de los templates

De igual manera se aplicarion metodos de seguridad, para que el usuario no pueda acceder a las paginas sin estar logueado, y que no pueda acceder a paginas que no le corresponden a su rol, por ende se aplicaron los decoradores de login_required y roles_required, para que el usuario pueda acceder a las paginas que le corresponden, y que no pueda acceder a las que no le corresponden

El enfoque a futuro de la aplicacion es un sitio publicitario, en el que se puedan manejar usuarios de la aplicacion, visitantes y facturacion de los mismos se podran manejar links de pago y desgloses al finalizar ciclos predeterminados por el administrador de esta


