# Blackjack-Simulator-Project
Repositorio principal para la creación de proyecto de simulador del juego de naipes 21 BlackJack

Este proyecto tiene como objetivo construir un simulador de blackjack que permita a los usuarios jugar partidas de blackjack en tiempo real y probar diferentes estrategias. El proyecto se divide en tres fases.

## Fase 1: Lógica de juego

En esta fase, se desarrollará la lógica principal del juego. Esto incluirá la creación de las clases y reglas del blackjack. La salida de las partidas simuladas se imprimirá en la consola para facilitar la depuración y prueba.

Las clases principales a desarrollar incluyen:

- Carta
- Mazo
- Jugador
- Dealer
- Mesa

## Fase 2: API y base de datos

En esta fase, se creará una API REST que permitirá a los clientes interactuar con el juego. Las operaciones básicas que la API deberá soportar incluyen: iniciar partida, hacer apuesta, pedir carta, etc.

Además, se integrará Firebase como la base de datos para el proyecto. Se utilizarán los servicios de Firebase para gestionar los datos en tiempo real y almacenar los resultados de las partidas.

Dependiendo de las necesidades del proyecto, se podría considerar el uso de WebSockets para permitir actualizaciones en tiempo real.

## Fase 3: Interfaz de usuario

En esta fase, se desarrollará una interfaz de usuario con React. Esta interfaz permitirá a los usuarios interactuar con el juego en tiempo real.

Se utilizarán hooks de React y posiblemente el Context API de React o Redux para gestionar el estado global de la aplicación.

# Pruebas

A lo largo de cada fase, se dedicará tiempo a realizar pruebas. Esto incluirá pruebas unitarias en la Fase 1, pruebas de API en la Fase 2, y pruebas de interfaz de usuario en la Fase 3. Las pruebas son una parte integral del desarrollo de software y ayudarán a asegurar que la aplicación funcione como se espera.
