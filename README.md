Juan Francisco Marapode - Joaquín Ignacio Ordoñez - 5°IB

- La interfaz del formulario la diseñamos con los conceptos que conocíamos del año pasado y tuvimos que investigar sobre focus, y queríamos que el fondo sea gradiante porque un color solo nos parecía aburrido.

- Implementamos varias validaciones, en este caso, hicimos cada una por separado, validando individualmente cada input. Obteniendo lo que se ingresó por el id de cada input con la función getElementById(""), y después hicimos las validaciones necesarias específicas que requería cada input. Además en cada validación agregamos una variable let que la usamos para asignar un booleano y con esto devolvíamos si la validación había funcionado o no (true or false). Con esto se lo mandábamos a otra función que validaba el formulario completo, para que no se envie si alguna validación era incorrecta (false).

- Desafíos que encontramos:
1. No sabíamos como validar el formulario completo para que no se enviara. Lo resolvimos pensando en agregar una nueva función que una todas las otras funciones que validan el input, para evitar que el formulario se envie si las validaciones eran falsas.
2. Tuvimos que investigar acerca de focus en css.

- Agregaríamos un registro de usuarios registrados.
