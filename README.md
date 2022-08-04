# Notas
Este es un RestServer en Node.js

No olvidar reconstruir la carpeta node_modules con el comando:
```
npm install
```

COMANDOS PARA EJECUTAR EN EL CMD:
```
node app.js    o bien     nodemon app.js 
```

VERIFICAR EN POSTMAN EL ENTORNO {{url}} YA SEA DESARROLLO O PRODUCCION:
```
http://localhost:8080/ <-- desarrollo
https://restserver-curso-node-alexande.herokuapp.com <-- produccion

usuarios get o post:   http://localhost:8080/api/usuarios/
usuarios get con limite de resultados por pagina http://localhost:8080/api/usuarios?limite=10
usuarios get o post en heroku: https://restserver-curso-node-alexande.herokuapp.com/api/usuarios/
usuarios put o delete: http://localhost:8080/api/usuarios/ID_MONGO
usuarios put o delete en heroku: https://restserver-curso-node-alexande.herokuapp.com/api/usuarios/ID_MONGO
(en put o post no olvidar los campos del body)

usuarios login: http://localhost:8080/api/auth/login
usuario login google: http://localhost:8080/api/auth/google
usuario login google en chrome: http://localhost:8080/

categorias get o post:   http://localhost:8080/api/categorias/
categorias get o post en heroku: https://restserver-curso-node-alexande.herokuapp.com/api/categorias/
categorias obtener categoria por getid: http://localhost:8080/api/categorias/ID_MONGO
categorias obtener categoria por getid en heroku: https://restserver-curso-node-alexande.herokuapp.com/api/categorias/ID_MONGO
categorias put o delete: http://localhost:8080/api/categorias/ID_MONGO
categorias put o delete en heroku: https://restserver-curso-node-alexande.herokuapp.com/api/categorias/ID_MONGO
(en put o post no olvidar los campos del body)

productos get o post: http://localhost:8080/api/productos/
productos get o post en heroku: https://restserver-curso-node-alexande.herokuapp.com/api/productos/
productos obtener producto por getid: http://localhost:8080/api/productos/ID_MONGO
productos obtener producto por getid en heroku: https://restserver-curso-node-alexande.herokuapp.com/api/productos/ID_MONGO
productos put o delete: http://localhost:8080/api/productos/ID_MONGO
productos put o delete en heroku: https://restserver-curso-node-alexande.herokuapp.com/api/productos/ID_MONGO
(en put o post no olvidar los campos del body)

buscar producto:  http://localhost:8080/api/buscar/productos/NOMBRE_DEL_PRODUCTO o ID_MONGO
buscar producto en heroku: https://restserver-curso-node-alexande.herokuapp.com/api/buscar/productos/NOMBRE_DEL_PRODUCTO o ID_MONGO
buscar producto-por-categoria: http://localhost:8080/api/buscar/producto-por-categoria/NOMBRE_DE_CATEGORIA
buscar producto por categoria en heroku: https://restserver-curso-node-alexande.herokuapp.com/api/buscar/producto-por-categoria/NOMBRE_DE_CATEGORIA
buscar usuario:   http://localhost:8080/api/buscar/usuarios/NOMBRE_DEL_USUARIO o CORREO
buscar usuario en heroku: https://restserver-curso-node-alexande.herokuapp.com/api/buscar/usuarios/NOMBRE_DE_USUARIO o CORREO
buscar categoria: http://localhost:8080/api/buscar/categorias/NOMBRE_DE_CATEGORIA
buscar categoria en heroku: https://restserver-curso-node-alexande.herokuapp.com/api/buscar/categorias/NOMBRE_DE_CATEGORIA

actualizar imagen usuarios:  http://localhost:8080/api/uploads/usuarios/ID_MONGO
actualizar imagen productos: http://localhost:8080/api/uploads/productos/ID_MONGO
obtener imagen de producto:  http://localhost:8080/api/uploads/productos/ID_MONGO

```