*Micro-tarea:*
Validador de e-mail.

*Pilar 1 — Herramienta:*
Claude Code con Sonnet 4.6 y esfuerzo Medio, es la herramienta que tengo disponible y el modelo para una tarea tan básica parece suficiente.

*Pilar 2 — Contexto:*
El lenguaje a utilizar será JavaScript y el resultado debe ser una clase en un fichero con extensión .js que se pueda usar como librería, utilizando nomenclatura camelCase con nombres en castellano sin tildes. Cualquier decisión que no se adapte a lo solicitado debe ser consultada.

*Pilar 3 — Prompt:*
Quiero implementar un método en JavaScript que realice la validación sintáctica de una dirección de correo. El método deberá formar parte de una clase y los nombres a utilizar deben estar en castellano, sin usar tildes ni caracteres especiales, con nomenclatura camelCase. El resultado debe escribirse en un archivo que pueda ser usado como librería. Además deberá haber un fichero HTML para testeo del método, con varias pruebas de direcciones válidad e inválidas. Ambos ficheros (librería y test html) deben residir en la carpeta "tareas.2". Cualquier decisión que no se adapte a lo solicitado debe ser consultada.

*Resultado:*
La expresión regular para validar las direcciones ha sido simplificada y permite algún caso de dirección incorrecta, por lo que ha habido que matizar que se debe ser estricto en la validación. Quizás el prompt debería haber indicado esto, aunque a priori no esperaba que el modelo usara una validación simplificada.
