# Lista de tareas basica

Este repositorio presenta la **Especificación de Requerimientos de Software (SRS)** de una aplicación básica de notas, cuyo propósito es definir de forma clara las reglas de negocio y atributos de calidad mediante requerimientos funcionales y no funcionales, siguiendo un enfoque **agnóstico a la tecnología** e independiente de su implementación.

> [!IMPORTANT]
> El contenido de este repositorio se distribuye bajo la **Licencia Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)**.
> Todos los términos se rigen por lo establecido en el archivo [LICENSE](/LICENSE).

## Autor

**Carlos Daniel Menchaca Arauz**  
Ingeniero de Sistemas Informáticos <br />
Santa Cruz de la Sierra, Bolivia

Sitio web: https://iamcarlosdaniel.com  
GitHub: https://github.com/iamcarlosdaniel  
LinkedIn: https://www.linkedin.com/in/iamcarlosdaniel  
E-mail: contact@iamcarlosdaniel.com

<br />

> [!NOTE]
> This document is also available in its **english version** at [docs/en/README.md](/docs/en/README.md)

## Índice

- [Requerimientos funcionales](#requerimientos-funcionales)
  - [Módulo de tareas](#módulo-de-tareas)
    - [RF-TK-01: Obtener todas las tareas]()
    - [RF-TK-02: Obtener la información de una tarea]()
    - [RF-TK-03: Crear una tarea]()
    - [RF-TK-04: Editar la información de una tarea]()
    - [RF-TK-05: Eliminar una tarea]()
  - [Módulo de etiquetas](#módulo-de-etiquetas)
    - [RF-ET-01: Obtener todas las etiquetas]()
    - [RF-ET-02: Obtener la información de una etiqueta]()
    - [RF-ET-03: Crear una etiqueta]()
    - [RF-RT-04: Editar la información de una etiqueta]()
    - [RF-RT-05: Eliminar una etiqueta]()

## Requerimientos funcionales

### Módulo de tareas

#### RF-TK-01: Obtener todas las tareas

**Descripción**

El sistema deberá permitir al usuario la visualización de la totalidad de las tareas registradas.

**Criterios de aceptación**

- El sistema debe retornar el conjunto completo de registros existentes.

- El sistema debe informar al usuario en caso de que no existan registros disponibles.

- El sistema debe implementar mecanismos de filtrado para optimizar la búsqueda de información.

- El sistema debe implementar un mecanismo de paginación para optimizar la entrega de información.

---

#### RF-TK-02: Obtener la información de una tarea

**Descripción**

El sistema deberá permitir al usuario la recuperación de la información de una tarea específica mediante su identificador único.

**Criterios de aceptación**

- El sistema debe retornar la información completa del recurso solicitado.

- El sistema debe notificar al usuario en caso de que el identificador proporcionado no corresponda a un registro existente.

---

#### RF-TK-03: Crear una tarea

**Descripción**

El sistema deberá permitir al usuario la creación de nuevas tareas.

**Criterios de aceptación**

- El sistema debe validar que la información proporcionada cumpla con los formatos requeridos.

- El sistema debe asignar un estado inicial predeterminado al registro tras su creación.

- El sistema debe confirmar la creación exitosa del recurso tras su persistencia.

---

#### RF-TK-04: Editar la información de una tarea

**Descripción**

El sistema deberá permitir al usuario la actualización de los atributos de una tarea existente.

**Criterios de aceptación**

- El sistema debe verificar la existencia del registro antes de aplicar cualquier modificación.

- El sistema debe notificar al usuario en caso de que el identificador no corresponda a un registro existente.

- El sistema debe validar que la información proporcionada cumpla con los formatos requeridos.

- El sistema debe asegurar que los cambios realizados sean correctamente reflejados en el estado del registro.

- El sistema debe confirmar la edición exitosa del recurso tras su persistencia.

---

#### RF-TK-05: Eliminar una tarea

**Descripción**

El sistema deberá permitir al usuario la eliminación lógica o física de una tarea específica.

**Criterios de aceptación**

- El sistema debe verificar la existencia del registro antes de ejecutar la operación de eliminación.

- El sistema debe confirmar la eliminación exitosa del recurso una vez finalizado el proceso.
