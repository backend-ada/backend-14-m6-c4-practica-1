<h1 align="center"> API REST - PRÁCTICA I </h1>
<h4 align="center"> Persistencia de datos con Sequelize y PostgreSQL </h4>

Para este pequeño desafío les propongo que desarrollen una API REST que conste de sólamente dos endpoints:

-   **GET |** _'/users'_ para obtener todos los registros de la tabla **Users**.
-   **POST |** _'/users'_ para crear un nuevo registro en la tabla **Users**.

La idea del ejercicio es que armen una API REST muy simple y básica, respetando el patrón MVC, y SIN AYUDARSE de ningún ejercicio anterior. Esto es para practicar un poco leer la documentación, interpretarla, probar código, corregir errores, y todo lo que implica la dinámica normal de trabajo.

La entidad **User** tiene **id**, **name**, **email**, **password** y **birthdate**. Leer bien en la documentación de _Sequelize_ cómo establecer los tipos correspondientes a cada dato.

**YAPA -->** Cuando hago un **GET** a _'/users'_ me tiene que también retornar la edad actual.
