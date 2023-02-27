# actividad3

### Inconveniente.

### Para evitar un error HTTP 404 realizamos lo siguiente.

### Para resolver estoy, hay que agregar lo siguiente a la configuracion nginx.

### location / {
###    root   /usr/share/nginx/html; // Carpeta en donde está la web
###    try_files $uri /index.html;
### }

### Root es una directiva de nginx la cual sirve para definir el directorio para resolver llamadas.

### try_files file......url;

### try files es otra directiva de nginx la cual verifica la existencia de uno o mas archivos y si no lo encuentra,
### nginx hace una redireccion interna a uri.
