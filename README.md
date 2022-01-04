# Configuración base para una app con SASS, PUG Y Vanilla JS

## Scripts
```
    npm run dev-windows
```
```
    npm run dev
```

Permite trabajar en entorno de desarrollo donde podemos ver automáticamente los cambios al trabajar con PUG y SASS. Utiliza el comando dependiendo de tu sistema operativo.

```
    npm run prod
```
Permite compilar y minificar los archivos generados por PUG y SASS.

### Notas

* Los archivos generados .css se guardan en public/css
* los archivos generados .html se guardan en public/
* Evitar la eliminación de la carpeta public puesto que debe almacenar otros recursos como imágenes en public/assets y el archivo .htaccess.
* Eliminar dentro de la carpeta public a la carpeta css y los archivos .html cuando se necesite limpiar y volver a generar desde cero.

* Dependencias globales para que funcionen los scripts

```
    npm install -g sass

    npm install pug-cli -g
```
## Correr aplicación

Recuerde que debe haber generado los archivos .html y la carpeta css dentro de public.

### Opción 1: Si tiene Visual Studio Code (Para desarrollo)

Instale la extensión Live Server y ejecute el archivo public/index.html con dicha extensión.

### Opción 2: Si tiene abierto la carpeta en su sistema operativo

Clic derecho al archivo public/index.html y abrir con el navegador de su preferencia

