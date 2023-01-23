![image](https://user-images.githubusercontent.com/110189994/214001435-314f2b1f-36f4-478d-b828-dc8a21c90cda.png)

Proyecto Final del bootcamp dedicado a la asistencia a mujeres víctimas de violencia de género para la Cruz Roja Sierra Norte, en el que trabajamos las diferentes verticales (UX/UI, data science, ciberseguridad, full-stack, marketing y cloud) de manera conjunta para desarrollar una web responsive que ayuda a cubrir las necesidades informativas y de recursos que pueden tener las mujeres víctimas de este tipo de violencia.

Por parte de data se desarrolló un mapa de Madrid, y específicamente de la Sierra Norte, donde encontrar puntos de interés como asociaciones dedicadas a este tipo de mujeres, puntos de cuarteles de la guardia civil, etc.

Así mismo, incorporamos un chatbot donde la propia mujer (o un familiar/amigo de la misma) pudiera expresar sus sentimientos o necesidades de manera anónima y se le diera una respuesta apropiada acorde con su duda o comentario.
El principal problema que nos encontramos para la realización de esta tarea fue la inexistencia de una base de datos con registros de respuestas, por lo que decidimos crear datos sintéticos con la API de OpenAI a través del chat GPT3. En total unos 10000 registros fueron creados, los cuales fueron filtrados y limpiados de tal manera que se les eliminó los signos de puntuación, las preposiciones, el género, etc para posteriormente por medio de un modelo de SVC dar la predicción.
Se creó una API con Flask y finalmente el modelo fue desplegado por medio de AWS.

https://thebridgecampus.slack.com/files/U0406LV3JEQ/F04LTD5C3MW/cruz_roja_sara.mp4
