1. Obtén los tokens de acceso de tu APP en la API de twitter.
   1. Añade esos valores a un archivo `config.cfg` que estará en el directorio Raíz de la aplicación
2. Instala dependencias en caso de que DirectAdmin las borre o el respaldo en Neubox elimine cosas:
   1. `pipenv install`
   2. `pipenv shell`
3. Inicia la app, modo desarrollo por cuestiones de seguridad, solo estará en línea cuando administrador así lo indique:
   1. `python3 ./twauth-web.py`; or
4. Python tiene un error en su versión 19.3.1, hasta que se arregle no es posible crear el archivo wheel de producción.
5. Usa la app en modo desarrollo cada vez que requieras ingresar un nuevo usuario, debe estar configurado el reenvio de puertos en el servidor virtual o el firewall en el servidor local.
