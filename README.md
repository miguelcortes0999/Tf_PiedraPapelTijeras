# Tf_PiedraPapelTijeras
Machine learning para ganar superior a un 60% de las 1000 veces de partidas jugadas en juego de piedra papel o tijera a 4 algoritmos de estrategias de juego,
el problema estaba creado en replit, sin embargo al no poder usar tenorflow, traslado las funciones a un notenook y asi poder resolverlo con Machien Learning.

En el archivo RPS.pyse le proporciona una función llamada player. La función toma un argumento que es una cadena que describe el último movimiento del oponente ("R", "P" o "S"). La función debe devolver una cadena que represente el próximo movimiento para que se reproduzca ("R", "P" o "S").

Una función de jugador recibirá una cadena vacía como argumento para el primer juego en un partido ya que no hay un juego anterior.

El archivo RPS.pymuestra una función de ejemplo que deberá actualizar. La función de ejemplo se define con dos argumentos ( player(prev_play, opponent_history = [])). La función nunca se llama con un segundo argumento, por lo que uno es completamente opcional. La razón por la que la función de ejemplo contiene un segundo argumento ( opponent_history = []) es porque esa es la única forma de guardar el estado entre llamadas consecutivas de la playerfunción. Solo necesita el opponent_historyargumento si desea realizar un seguimiento de la historia del oponente.

Sugerencia: para derrotar a los cuatro oponentes, es posible que su programa deba tener múltiples estrategias que cambien según las jugadas del oponente.

Desarrollo
No modificar RPS_game.py. Escribe todo tu código en RPS.py. Para el desarrollo, puede usar main.pypara probar su código.

main.pyimporta la función del juego y los bots de RPS_game.py.

Para probar su código, juegue un juego con la playfunción. La playfunción toma cuatro argumentos:

dos jugadores para jugar uno contra el otro (los jugadores son en realidad funciones)
el número de juegos a jugar en el partido
un argumento opcional para ver un registro de cada juego. Configúrelo Truepara ver estos mensajes.
play(player1, player2, num_games[, verbose])
Por ejemplo, así es como llamarías a la función si quieres jugar 1000 juegos entre sí playery quincyquieres ver los resultados de cada juego:

  <play(player, quincy, 1000, verbose=True)>
Haga clic en el botón "ejecutar" y main.pyse ejecutará.

Pruebas
Las pruebas unitarias para este proyecto están en formato test_module.py. Importamos las pruebas de test_module.pya main.pypara su conveniencia. Si descomentas la última línea en main.py, las pruebas se ejecutarán automáticamente cada vez que presiones el botón "ejecutar".
