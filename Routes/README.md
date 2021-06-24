# Routes
###### Version 1.1.0
Esta librería establece dos metodos on_change_start() y on_change_end().
on_change_start() se ejecuta al inicio de la carga del layout. Mucho antes de pedir un controlador.
Es útil para hacer comprobaciones antes de cargar un controlador. AVISO: No se puede modificar el controlador cargado.

on_change_end() se ejecuta una vez cargado el controlador.
