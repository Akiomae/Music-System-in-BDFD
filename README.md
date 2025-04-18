
# Music System in BDFD v4.0

Un sistema para poder reproducir musica con tu bot de discord en Bot Desinger For Discord.


## Configuración

#### Solo necesitas crear 1 variable


| name | value     |
| :-------- | :------- |
| `TOKEN` | `El token de su bot de discord` | 

## Comandos
- !play
- !stop
- !vol
- $onInteraction (2)


## Autor

- [Edgajuman](https://github.com/edgajuman)


## Soporte

https://discord.gg/RMSYrQCs2r

## Nuevas cosas y actualizaciones
- Se mejoro el sistema de premium para dar mas ventajas a los bots PREMIUM
- Función de Pause y Resume
- Función de Skip
- Botones de acciones
- Lista de reproducción
- Se soluciono la carga de acciones, ahora responden mas rapido, excepto el !play, ya que realiza la busqueda de la musica
- Se agregaron verificaciones si el usuario esta en un canal o no
- Se añadieron los nombres de las musicas en reproducción
- Se añadio sistema de volumen
- Se añadió sistema de retroceso
- Se arreglo el error que hacia repetir toda la lista completa para cargar la nueva musica
- Se agrego una Music Card para una vista atractiva de la musica en el !play
- Se implemento mas verificaciones necesarias (gracias a esto ya no se necesitara la variable "play")
- Ahora cuando desconecten tu bot del canal de voz sin el !stop se eliminara automaticamente la lista (esto para mejorar la experiencia y no tener una reproducción bugeada)

## Posibles bugs
El sistema es totalmente funcional, aunque tiene algunos bugs que luego se iran corrigiendo.
Algunos bugs pueden ser:
- No agregar musicas a la lista (rara vez, esto mas depende de la api de descarga de las músicas)

## Proximamente
- Se esta desarrollando un panel de usuario para que controle el sistema de musica de su bot desde una dashboard en la web
