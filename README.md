## Arquitectura monolítica

Toda la aplicación (interfaz, lógica y acceso a datos) está en un único bloque de código que se despliega junto.

- Es más fácil de desarrollar y probar al principio.
- Si crece mucho, cuesta mantenerla.
- Un fallo o un cambio puede afectar a todo el sistema.

## Microservicios

La aplicación se divide en servicios pequeños e independientes (por ejemplo, usuarios, pagos y pedidos). Cada uno tiene su propia función y se comunica con los demás por red, normalmente mediante APIs.

- Se pueden desarrollar, desplegar y escalar por separado.
- Facilita trabajar con diferentes partes de la aplicación de forma independiente.
- Aumenta la complejidad general del sistema.

## Frontend vs. Backend

### Frontend

Es la parte que ve y utiliza el usuario en su dispositivo, como el diseño, los botones y los formularios.

- **Tecnologías:** HTML, CSS y JavaScript.
- **Frameworks:** React y Angular.

### Backend

Es la parte que trabaja por detrás, en el servidor. Procesa la lógica, gestiona la base de datos y responde a las peticiones del frontend.

- **Lenguajes:** Java, Python y PHP.
- **Funciones:** procesar datos, aplicar la lógica de la aplicación y comunicarse con la base de datos.