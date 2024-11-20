# League of Legends Stats Tracker

![Logo del Proyecto](https://upload.wikimedia.org/wikipedia/commons/d/d8/League_of_Legends_2019_vector.svg)

Bienvenido a **League of Legends Stats Tracker**, una herramienta web diseñada para mostrar y analizar las estadísticas de jugadores de **League of Legends** en tiempo real. ¡Ahora podrás ver tu rendimiento en cada partida, además de obtener estadísticas detalladas sobre tus partidas ganadas, perdidas, ranking y mucho más!

## 📸 Captura de Pantalla

![Captura de pantalla del Tracker](https://github.com/bait-py/nyoloqchallenge/blob/main/images/leaguestats.jpg) 
*Así se ve el tracker de estadísticas en acción.*

## 🚀 Características

- **Visualización en tiempo real** de las estadísticas de jugadores de **League of Legends**.
- **Análisis detallado** de estadísticas de clasificación como **Ranking, Winrate, Partidas Ganadas y Perdidas**.
- **Estadísticas de rol** personalizadas para cada jugador (JUNGLE, ADC, TOP, MID, SUP).
- **Enlace directo a OP.GG** para ver más detalles de cada jugador.

## 🔧 Tecnologías Utilizadas

Este proyecto utiliza las siguientes tecnologías:

- **HTML5** y **CSS3** para el diseño y estilo del tracker.
- **JavaScript (ES6)** para la interacción con la API de Riot Games y la manipulación del DOM.
- **API de Riot Games** para obtener las estadísticas de los jugadores.
- **Fetch API** para realizar solicitudes HTTP a la API de Riot.

## 📦 Instalación

1. Clona el repositorio:
    ```bash
    git clone https://github.com/tu-usuario/league-of-legends-stats-tracker.git
    ```

2. Navega hasta el directorio del proyecto:
    ```bash
    cd league-of-legends-stats-tracker
    ```

3. Abre `index.html` en tu navegador para ver el tracker en acción.

> **Nota:** Asegúrate de tener una clave API de Riot Games válida para que las estadísticas de los jugadores se carguen correctamente.

## 📝 Instrucciones de Uso

1. **Agregar Jugadores**: Agrega los jugadores en el archivo `script.js` dentro del arreglo `jugadores`, con el nombre del jugador y su **Riot ID**.
   
   Ejemplo:
   ```javascript
   const jugadores = [
       { nombre: 'Bruno', rol: 'JUNGLE', riotId: 'Smooth Criminal#009' },
       { nombre: 'Alex', rol: 'TOP', riotId: 'pacarde66#EUW' },
       ...
   ];
   ```

2. **Ver Resultados**: Al cargar la página en tu navegador, verás una tabla con las estadísticas de los jugadores agregados, incluyendo su ranking, winrate y más.

3. **Interactividad**: Haz clic en los encabezados de la tabla para ordenar los resultados por columnas como **Winrate**, **Partidas Ganadas**, etc.

## 💻 Contribuciones

Si deseas contribuir a este proyecto, por favor sigue estos pasos:

1. Haz un fork de este repositorio.
2. Crea una nueva rama para tu feature (`git checkout -b feature/nueva-feature`).
3. Realiza tus cambios y haz commit (`git commit -am 'Añadir nueva feature'`).
4. Haz push a tu rama (`git push origin feature/nueva-feature`).
5. Abre un Pull Request.

## 💬 Contacto

- **Autor**: [Bruno Alonso](https://github.com/bait-py)
```
