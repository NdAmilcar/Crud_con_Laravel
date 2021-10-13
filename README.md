![This is an image](https://github.com/NdAmilcar/Crud_con_Laravel/blob/main/img/Sin%20t%C3%ADtulo.png)

# Crud  con Laravel
Crud sencillo con Laravel.
Para crearlo desde cero solo hay que usar los comandos:
Dentro de htdocs( si es que usamos Xampp):

composer create-project laravel/laravel nombreDelProyecto
composer require livewire/livewire

Dentro de VisualStudioCode (en mi caso):
Abrimos la paleta de comandos y escribimos:
Artisan make migration

(con el comando anterior, vamos a poder crear las especificaciones de nuestro proyecto)
Ej: Este proyecto es de un "Crud de empleados" por lo que la base de datos se va llamar "empleados" y las tablas "empleados",
luego edité dentro de: database->migrations (y en el último archivo con la extención .php está la "migración" que hicimos anteriormente).
En la parte de:
public function up()
agragamos "nombre" y "correo" (en mi caso)
Luego de hacer todo esto ejecutamos el comando:
php artisan migrate
composer require flightsadmin/livewire-crud
php artisan crud:install
yes 
yes
php artisan crud:generate empleados

Para ver en pantalla lo que hicimos:

php artisan serve

Los códigos que utilicé están en:

https://github.com/flightsadmin/livewire-crud/blob/main/README.md


#Bienvenidos a mi repositorio


### Los invito a aprovechar de todos los códigos que iré subiendo a lo largo de mi vida como desarrollador.
    Espero sea de ayuda, si tienen algún problema con el código o alguna duda, sin ningún problema pueden contactarme,
    voy a hacer todo lo posible por responder a todas sus dudas, dejo mis redes sociales para que puedan hacerlo.

# Things to do
Lista de tareas, todo se aloja en local.


### Por [Amilcar](https://www.instagram.com/ndamilcar/?hl=es)
### [Diseño y Desarrollo Web](http://www.NdAdventure.com)
### [Correo] (NdAmilcar@gmail.com)

### La programación es un mundo en el que el camino es difícil si lo hacemos solos, pero hay una comunidad ¡GIGANTE! Dispuesta a ayudar, no tengas miedo, todos empezamos de abajo, animate a compartir tu experiencia y tus pasos por este maravilloso mundo.

## El límite es solo la imaginación.
  
 # Muchos éxitos!
