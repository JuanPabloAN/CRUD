# CRUD
CRUD Juan Pablo Aboytes Novoa

IMPORTANTE!

Se necesita crear la base de datos antes con un registro.

Al crearlo con código no se guardaba la base de datos por lo que tuve que crear y agregar un registro a mano. 

Aprovechando que una de las tareas era crear un usuario decidí crearlo en consola para que no se borrara la base de datos. El usuario creado a mano es con la siguiente informacion:
●id: 1
●name: John
●last_name: Doe
●age: 30
●email: john_doe@example.com
●active: true

COPIAR Y PEGAR PARA CREAR LA BD Y EL PRIMER REGISTRO

use crud;
db.usuarios.insert({id:1, name: 'John', lastname: 'Doe', age: 30, email: 'john_doe@example.com', active: 'true'});
