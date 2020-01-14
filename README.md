# FPOO-ActividadPrimaria-U1-2
Descripción de la práctica 2 de la Unidad 1.

Se necesita un sistema informático para la gestión e inventario de los bienes materiales de la UPV. Para lo cual se tienen las siguientes restricciones:
  * Existen 2 tipos de usuario final
    * Usuario administrador: Será el encargado de la gestión (alta, baja, actualización, etc) de los bienes materiales.
    * Usuario secundario: sólo se le permitirá la visualización y búsqueda de recursos materiales.
  * Cada recurso material tiene una categoria y/o sub-categoria: moviliario, equipo de laboratorio, equipo de cómputo, las cuales serán gestionadas por el administrador.
  * Cada recurso material tiene una descripción, un número de serie único a la universidad.
  * Cada recurso material puede tener asociados a 2 personas: un propietario y un usuario.
  * Cada recurso material tiene asignado una localización.
  * Cada recurso material tiene registrada una fotogafía para su identificación.
 
El sistema informático deberá permitir la generación de una etiqueta con la siguiente información del recurso material:
  * Nombre y descripción corta
  * número de inventario
  * código QR con la información.
Dicha etiqueta podrá ser guardada en PDF para su posterior impresión.

Se deberá realizar un proyecto maven con interfaz gráfica en JavaFX con diseño profesional.

Se deberán realizar por lo menos un conjunto de test unitarios.

Se deberá entregar evidencia de la visita y entrevista con el jefe de departamento de recursos materiales/inventario de la UPV y el análisis de los requerimientos funcionales y no funcionales para el sistema.

Se entregará el código fuente de la solución, así como un reporte con el manual de usuario y ténico en formato markdown adjunto a este repositorio en una carpeta llamada manuales.
