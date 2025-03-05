# proyecto_venta_videojuegos

Este proyecto analiza las ventas de videojuegos por región, plataforma y género para identificar patrones clave que permitan a la tienda online Ice **detectar proyectos prometedores** y **planificar campañas publicitarias efectivas**. Al entender las dinámicas de mercado en Norteamérica, Europa y Japón, se busca **optimizar estrategias de marketing**.

#### Herramientas y tipo de proyecto
![Python](https://img.shields.io/badge/python-357ebd?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23357ebd.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23357ebd.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Seaborn](https://img.shields.io/badge/Seaborn-357ebd?style=for-the-badge)
![SciPy](https://img.shields.io/badge/SciPy-%23357ebd.svg?style=for-the-badge&logo=scipy&logoColor=white)
![Limpieza de datos](https://img.shields.io/badge/Limpieza_de_datos-295F98?style=for-the-badge)
![Transformación de datos](https://img.shields.io/badge/Transformación_de_datos-295F98?style=for-the-badge)
![Análisis de datos](https://img.shields.io/badge/Análisis_de_datos-295F98?style=for-the-badge)
![Pruebas de hipótesis](https://img.shields.io/badge/Pruebas_de_hipótesis-295F98?style=for-the-badge)
![Visualización de datos](https://img.shields.io/badge/Visualización_de_datos-295F98?style=for-the-badge)

### Preguntas clave
1. ¿Cuantos juegos fueron lanzados en diferentes años, Son significativos los datos de cada período?
2. ¿Cuáles son las plataformas con mayores ventas globales y cómo varían estas por región?
3. ¿Qué géneros de videojuegos son más populares en Norteamérica, Europa y Japón?
4. ¿Cuánto tardan generalmente las nuevas plataformas en aparecer y las antiguas en desaparecer?
5. ¿Qué relación existe entre las puntuaciones de usuarios/críticos y las ventas globales de videojuegos?
6. ¿Existen diferencias significativas en las calificaciones promedio entre plataformas y géneros?


## Descripción de datos
— Name (Nombre)
— Platform (Plataforma)
— Year_of_Release (Año de lanzamiento)
— Genre (Género) 
— NA_sales (ventas en Norteamérica en millones de dólares estadounidenses) 
— EU_sales (ventas en Europa en millones de dólares estadounidenses) 
— JP_sales (ventas en Japón en millones de dólares estadounidenses) 
— Other_sales (ventas en otros países en millones de dólares estadounidenses) 
— Critic_Score (máximo de 100) 
— User_Score (máximo de 10) 
— Rating (ESRB)

### Conclusiones y recomendaciones

#### Dinámica de ventas por región:
- las plataformas con mas ventas en los ultimos 5 años son 3DS, DS, PS2, PS3, PS4, PSP, Wii, X360
- Norteamérica y Europa prefieren juegos de acción y disparos en consolas como Xbox y PlayStation.
- Japón, en cambio, favorece juegos de rol en plataformas portátiles como Nintendo 3DS.

#### Efecto de las reseñas:
- Las puntuaciones de usuarios presentan correlación casi nula, lo que sugiere que los consumidores priorizan otras métricas al elegir juegos.

#### Pruebas de hipótesis:
- Las calificaciones promedio de los usuarios para las plataformas Xbox One y PC son iguales.
- Las calificaciones promedio de los usuarios para los géneros de Acción y Deportes son diferentes.

#### Estrategias recomendadas:
- Dado que PS4 y Xbox One se mantienen relevantes en ventas globales, recomendamos enfocar campañas publicitarias en estas plataformas.
- Debido a las preferencias de usuarios en esta región, recomendamos enfocar promociones de RPG en Japón e impulsar títulos de acción y disparos en mercados occidentales.

### Visualizaciones destacadas
1. **Distribución de ventas por género:** Los géneros con mayores ventas son aquellos que pertenecen al género de acción, disparos, juegos de rol y deportes. Mientras que los géneros con menores ventas son los de rompecabezas y estrategia.
![Generos con mas ventas]({{ "/assets/Ventas%20por%20genero.png" | relative_url }})
3. **Comparación de reseñas y ventas:** Hay una correlación positiva mediana entre la puntuación de los críticos y las ventas de videojuegos. Esto podría significar que los usuarios toman en cuenta parcialmente las puntuaciones de los críticos para comprar o no un videojuego.
![Comparación de reseñas y ventas](https://github.com/monik719/Portafolio/blob/main/assets/Distribuci%C3%B3n%20ventas%20y%20critica.png)
4. **Ventas por plataforma:** 6 plataformas de las que mas vendieron desde el año de lanzamiento hasta desaparecer, es un promedio de 10 años.
![Diagrama de lineas](https://github.com/monik719/Portafolio/blob/main/assets/Ultimos%205%20a%C3%B1os.png)

**Explora más detalles del proyecto en el [repositorio completo](https://github.com/monik719/proyecto_venta_videojuegos).**
