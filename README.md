# Technical_tests

Aplicacion de Blog para Posts

## Características
Registro de usuarios: Permite a los usuarios crear una cuenta de manera rapida para acceder a la aplicación.
Inicio de sesión: Permite a los usuarios iniciar sesión en sus cuentas existentes.
Publicación de contenido: Permite a los usuarios crear y publicar contenido, texto o enlaces.
Dar likes: Permite a los usuarios dar "me gusta" a las publicaciones de otros usuarios.
Comentar: Permite a los usuarios dejar comentarios en las publicaciones de otros usuarios.
Explorar contenido: Permite a los usuarios descubrir nuevas publicaciones de otros usuarios.

## Requisitos
Entorno de desarrollo de Django: Configura un entorno virtual de Python con Django instalado para facilitar el desarrollo y la ejecución de la aplicación.
Autenticación de usuarios: Implementa un sistema de registro de usuarios y autenticación para permitir que los usuarios creen cuentas y accedan a la aplicación.
Modelos de datos: Define los modelos de Django necesarios para representar los posts, los perfiles, los likes, los comentarios, etc.
Formularios: Crea formularios de Django para permitir a los usuarios crear publicaciones, dejar comentarios, etc.
Plantillas: Diseña las plantillas HTML que se utilizarán para presentar la interfaz de usuario de tu aplicación.
Rutas (URLs): Configura las rutas (URLs) de Django para mapear las solicitudes de los usuarios a las vistas correspondientes.
Dar likes y comentarios: Agrega la lógica necesaria para permitir a los usuarios dar likes a las publicaciones y dejar comentarios en ellas.

## Instalación

1. Clona el repositorio: `git clone https://github.com/tu-usuario/tu-repositorio.git`
2. Ve al directorio del proyecto: `cd Technical_tests`
3. Inicializa el entorno virtual 'source .venv/bin/activate'
4. Instala las dependencias: `pip install -r requirements.txt'.
5. Inicializa Mysql 'sudo service mysql start'.
6. Ingresa con tus credenciales 'mysql -u root -p', si no has configurado o creado un usuario solo debes presionar enter cuando la terminal te pida la clave.
7. Crea la siguiente base de datos 'CREATE DATABASE technical_test;'.
8. En la terminal a raiz de repositorio y con el entorno virtual encendido 'Technical_tests' corre el comando 'python3 manage.py makemigrations' si no agrega los modelos completos corre el comando 'python3 manage.py makemigrations blog'.
9. Corre el comando 'python3 manage.py migrate' para finalizar de ejecutar las migraciones.
10. Corre el comando 'python3 manage.py createsuperuser', deberas ingresar el 'username', 'email', 'password' y confirmar la 'password' para crear un super usuario (OPCIONAL).
11. Corre el comando 'python3 manage.py runserver'.
12. Crea un usuario dando click en 'Registrarse' y cuando fialices ingreas con el 'USERNAME' y la 'PASSWORD' que registraste, Nota: tambien puedes entrar con el SuperUsuario.
13. Dirigete a la direccion 'http://127.0.0.1:8000/admin/' y gestiona permisos para usuarios, posts, likes, comentarios y perfiles de usuario. 

## Uso

Una vez estes dentro de la aplicacion en la parte izquierda de tu pantalla estara disponible la informacion del usuario, en el centro derecha observaras los Posts que se han creado por ti y otros usuarios, podras agregar un titulo y un contenido, presionas en crear y creas un nuevo Post, en esa misma pantalla podras ver tu Post, cada post tiene fecha de publicacion nombre del auto y el contenido, seguido de los comentarios y likes que otras personas pueden hacer.
puedes presionar en likes para dar like y ver como se suma o resta tu like al Post, puedes presionar en comentar o si ya comentaste te aparecera un enlace que dice editar, el cual te lleva a una nueva vista y te permite editar el comentario.
En la parte superior derecha de 'TUS PROPIOS POSTS' podras ver el boton de 'Eliminar' y el de 'Editar', esos botones afectan directamente al Post.

Nota: Solo podras editar 'TUS' transacciones realizada con cada 'Post' ,'Comentarios' y 'Likes'.

```bash
comando-de-ejemplo
