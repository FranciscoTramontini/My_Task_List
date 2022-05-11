# My Task List

  Aplicacion de servidor local que organiza un lista de tareas.
  
  Trabaja con Angular (TypeScript, HTML, CSS) y json-server para hacer cambios.
  
  Puedes:
  
    * Agregar.
    * Eliminar.
    * Marcar como hechas.
  
# Preparativos

  Tener instalado Angular y json-server
  
# Funcionamiento
  * Descargar el repositorio,
  * Entrar a la app con Angular.
  * Abrir dos terminal:
      * En una correr el json-server (json-server --watch db.json), ver que URL local te da.
        
        Entrar al archivo task.service.ts y comprobar la URL de ahi con la que te da el servidor, si son distintas cambiar, siempre dejando el /tasks. Guardar los cambios.
      
      * En la otra correr el server de angular (ng serve -o).

  * Luego de esto, se te va a abrir solo el navegador con la URL local y vas a ver un boton para agregar tareas.
