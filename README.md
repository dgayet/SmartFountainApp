<div align="center">

# 86.65 Sistemas Embebidos

## Repositorio para el Software (Kotlin code) del trabajo final de la materia: Smart Motion Activated Water Fountain

Video explicativo del proyecto: https://youtu.be/tSH6keEnLOM

</div>
En este proyecto se desarrolló una aplicación móvil para controlar de manera manual el dispositivo que se describe a continuación.


El dispositivo es un bebedero que tiene incorporado una bomba de agua, la cual se puede activar mediante proximidad, o controlar manualmente mediante la App. También se estima el nivel de agua para determinar si es suficiente para el correcto funcionamiento de la bomba. Existen tres casos:
Nivel de agua LOW: se bloquea la bomba. En la app se muestra que el bebedero está bloqueado y no se puede interactuar con los botones.
Nivel de agua OK: se indica en la app y se permite tanto el funcionamiento manual como el automático.
Nivel de agua MAX: se indica en la app y se bloquea el funcionamiento.
El control manual mediante la aplicación permite activar y desactivar la bomba, y bloquear el bebedero para que no pueda ponerse en funcionamiento.

La comunicación se realiza mediante MQTT, con un broker hosteado en mi PC. 
