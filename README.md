# Artista: Taylor Swift 
## Base de datos de Spotify.

Este conjunto de datos consiste en datos de la API de Spotify sobre todos los álbumes listados en Spotify para Taylor Swift. Configuré el conjunto de datos para actualizarse mensualmente, de modo que si se agregan nuevos álbumes, también se agregarán al conjunto de datos. Al principio, puede parecer que hay duplicados de canciones, pero verifiqué y todas las ID de canciones son únicas.

Las columnas en este conjunto de datos son:
• name: el nombre de la canción.

• album: el nombre del álbum.

• release_date: el día, mes y año en que se lanzó el álbum.

• track_number: el orden en el que aparece la canción en el álbum.

• id: el identificador de Spotify para la canción.

• uri: el URI de Spotify para la canción.

• acousticness: una medida de confianza de 0.0 a 1.0 que indica si la pista es acústica. 1.0 representa alta confianza de que la pista es acústica.

• danceability: la capacidad de baile describe qué tan adecuada es una pista para bailar en función de una combinación de elementos musicales que incluyen el tempo, la estabilidad del ritmo, la fuerza del ritmo y la regularidad general. Un valor de 0.0 es el menos adecuado para bailar, y 1.0 es el más adecuado.

• energy: la energía es una medida de 0.0 a 1.0 que representa una medida perceptual de intensidad y actividad. Típicamente, las pistas energéticas se sienten rápidas, ruidosas y ruidosas. Por ejemplo, el death metal tiene alta energía, mientras que un preludio de Bach tiene una puntuación baja en la escala. Las características perceptuales que contribuyen a este atributo incluyen el rango dinámico, la percepción de la intensidad, el timbre, la tasa de inicio y la entropía general.

• instrumentalness: predice si una pista no contiene vocales. Los sonidos "ooh" y "aah" se tratan como instrumentales en este contexto. Las pistas de rap o palabra hablada son claramente "vocales". Cuanto más cercano sea el valor de instrumentalidad a 1.0, mayor probabilidad hay de que la pista no contenga contenido vocal. Los valores por encima de 0.5 representan pistas instrumentales, pero la confianza es mayor a medida que el valor se acerca a 1.0.

• liveness: detecta la presencia de una audiencia en la grabación. Valores más altos de liveness representan una mayor probabilidad de que la pista se haya interpretado en vivo. Un valor por encima de 0.8 proporciona una fuerte probabilidad de que la pista sea en vivo.

• loudness: el volumen general de una pista en decibelios (dB). Los valores de volumen se promedian en toda la pista y son útiles para comparar el volumen relativo de las pistas. El volumen es la cualidad de un sonido que es el correlato psicológico principal de la fuerza física (amplitud). Los valores típicamente oscilan entre -60 y 0 dB.
speechiness: detecta la presencia de palabras habladas en una pista. Cuanto más similar sea la grabación al habla exclusivamente (por ejemplo, un programa de entrevistas, un audiolibro, poesía), más cercano será el valor del atributo a 1.0. Los valores por encima de 0.66 describen pistas que probablemente están compuestas completamente de palabras habladas. Los valores entre 0.33 y 0.66 describen pistas que pueden contener música y habla, ya sea en secciones o en capas, incluidos casos como la música de rap. Los valores por debajo de 0.33 probablemente representan música y otras pistas no habladas.

• tempo: el tempo estimado general de una pista en beats por minuto (BPM). En la terminología musical, el tempo es la velocidad o el ritmo de una pieza determinada y se deriva directamente de la duración promedio del latido.

• valence: una medida de 0.0 a 1.0 que describe la positividad musical transmitida por una pista. Las pistas con un alto valor de valencia suenan más positivas (por ejemplo, felices, alegres, eufóricas), mientras que las pistas con un bajo valor de valencia suenan más negativas (por ejemplo, tristes, deprimidas, enojadas).

• popularity: la popularidad de la canción de 0 a 100.

• duration_ms: la duración de la pista en milisegundos.
