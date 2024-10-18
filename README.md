# Proyecto Taller

## Descripción
Este proyecto es una API REST para gestionar productos. Está desarrollado utilizando Java y Spring Boot.

## Configuración
1. Clona el repositorio:
   ```sh
   git clone https://github.com/Vero-nica22/conexion_intellij_mysql.git

### Configura la base de datos
- Asegúrate de tener MySQL instalado y ejecutándose.

- Crea una base de datos llamada proyectodemodb.

### Configuración de archivo conexión
- Configura el archivo application.properties con tu usuario y contraseña

## Endpoints

GET /api/productos: Lista todos los productos.

POST /api/productos: Agrega un nuevo producto.

GET /api/productos/{id}: Obtiene un producto por su ID.

DELETE /api/productos/{id}: Elimina un producto por su ID.

# Uso de Postman

## Configuración de Postman

### gregar un Producto
1. Abre Postman.
2. Selecciona el método **POST**.
3. Ingresa la URL: `http://localhost:8080/api/productos`.
4. Ve a la pestaña `Body`, selecciona `raw` y `JSON`.
5. Pega el siguiente JSON:
   ```json
   {
       "nombre": "Producto 3",
       "precio": 200.0
   }
### Agregar un Producto
1. Abre Postman.

2. Selecciona el método GET.

3. Ingresa la URL: http://localhost:8080/api/productos/{id}, reemplazando {id} con el ID del producto que deseas obtener.

4. Haz clic en Send para enviar la solicitud y ver el producto.

