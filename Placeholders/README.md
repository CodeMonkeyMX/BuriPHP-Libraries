# Placeholders
###### Version 1.1.0
Esta librería se usa cuando se esta renderizando el layout.
Se envía en el constructor el buffer de la aplicación, para realizar los cambios que se establezcan en el método run().
Es útil para remplazar un flag en un layout y cargar a su vez un template o view establecido.
Debe retornar $this->buffer en el método run() para que la aplicacion tenga en cuenta los cambios realizados.
