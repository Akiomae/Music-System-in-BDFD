
# Music System in BDFD v5.0

Un sistema avanzado para poder reproducir musica con tu bot de discord en Bot Desinger For Discord.


## Configuración

#### Solo necesitas crear 2 variables obligatoriamente


| nombre | valor     |
| :-------- | :------- |
| `TOKEN` | `El token de su bot de discord` | 
| `musicMS` | `Sin valor` | 

## Comandos
- !play
- !stop
- !vol
- !musicIA
- $onInteraction (2)


## Autor

- [Edgajuman](https://github.com/edgajuman)


## Soporte

https://discord.gg/RMSYrQCs2r

## Cosas añadidas en la versión anterior
- Se mejoro el sistema de premium para dar mas ventajas a los bots PREMIUM
- AHORA TU BOT PODRA REPRODUCIR MUSICAS DE YOUTUBE POR NOMBRE O URL
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

## Cosas añadidas en la nueva versión v5.0
- Ahora los botones se posicionaran siempre en la musica mas reciente añadida
- Se redujo lo mayor posible los errores que impedian añadir musicas
- Se soluciono errores de bots NO PREMIUM
- Se agrego sistema de IA (Este sistema dara recomendaciones y lo añadira automaticamente a la lista)
- Se cambio de libreria de busqueda para una mejor legibilidad y evitar la mayoria de errores posibles
- Coloreo de botones y nombres de acción añadido
- Se añadio sistema de descarga para descargar la musica actualmente sonando de la lista (Solo por 1 minutos, luego de eso no se podra descargar)

## Posibles bugs
El sistema es totalmente funcional, aunque tiene algunos bugs que luego se iran corrigiendo.
Algunos bugs pueden ser:
- No agregar musicas a la lista (rara vez, esto mas depende de la api de YouTube y los permisos de los videos)

## BotPanel
> Se ah desarrollado un panel para su bot que use este sistema de musica.
`Link:` https://edgabot.lucnodes.es/
### Video de demostración
https://vimeo.com/1077124656
