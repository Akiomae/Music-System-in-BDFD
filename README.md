
# Music System in BDFD v4.1 (PARCHE)

Un sistema avanzado para poder reproducir musica con tu bot de discord en Bot Desinger For Discord.


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

## Posibles bugs
El sistema es totalmente funcional, aunque tiene algunos bugs que luego se iran corrigiendo.
Algunos bugs pueden ser:
- No agregar musicas a la lista (rara vez, esto mas depende de la api de YouTube y los permisos de los videos)

## BotPanel
> Se ah desarrollado un panel para su bot que use este sistema de musica.
`Link:` https://edgabot.lucnodes.es/
### Video de demostración
<div style="padding:51.56% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/1077124656?h=e5af1e0cd6&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture; clipboard-write; encrypted-media" style="position:absolute;top:0;left:0;width:100%;height:100%;" title="BotPanel demostración"></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>
