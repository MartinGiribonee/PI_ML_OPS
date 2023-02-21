![ML_OPS](src/mlops-versionado-de-modelos_0.png)

<h1 align=center> HENRY’S LABS </h1>

<h2 align=center>PROYECTO INDIVIDUAL I -- ML_OPS <br>
    _Ingeniero y Data Scientist: Martín Mariano, Giribone_</h2>

> Encontraran información sobre el trabajo de ETL, la API que se me solicito hacer, el EDA y el modelo de recomendación.

## Arquitectura del proyecto
![Arquitectura](src/Diapositiva1.JPG)


:red_circle: **INICIO** :red_circle:

* **MLOpsReviews**: _Bases de datos recibidas_
* **detaAPI**: _Dentro encontraran un archivo main.py que contiene todo el codigo de la API. Requierements.txt que contiene las dependencias necesarias para que funcione y el csv utilizado para realizar todas las consultas_
* **Consignas.md**: _Repositorio recibido con todo el contenido y tareas ha realizar_
* **Trasformacion de datos**:  _Paso a paso detallado del proceso de ETL_
* **Purebas_1**: _Cuaderno con las pruebas para las consultas pedidas_
* **Analisis_exploratorio_de_datos**: _Paso a paso del proceso de EDA y el modelo de recomendación_

:blue_circle: **Funciones de la API:** :blue_circle:

* Película con mayor duración con filtros opcionales de AÑO, PLATAFORMA Y TIPO DE DURACIÓN.
* Cantidad de películas por plataforma con un puntaje mayor a XX en determinado año
* Cantidad de películas por plataforma con filtro de PLATAFORMA
* Actor que más se repite según plataforma y año.

Te espero ahí :D

https://detaapi-1-h9040310.deta.app/__deta_auth?token=eyJraWQiOiJzTjVnTk43cWFGVmpPYVwvc3oyVTJvdnNIMTZyNThQb2RQVFpRZWlBQUhNZz0iLCJhbGciOiJSUzI1NiJ9.eyJzdWIiOiJiNzhmZjJlMC1mNzg5LTRiODUtYjdjNS00MjMxM2MwY2FhOWUiLCJpc3MiOiJodHRwczpcL1wvY29nbml0by1pZHAuZXUtY2VudHJhbC0xLmFtYXpvbmF3cy5jb21cL2V1LWNlbnRyYWwtMV9WYUhoMEVvWDUiLCJjbGllbnRfaWQiOiIzMGpnaTM0MzlsbWRnN3V0dGUyN2dkbDlnYSIsIm9yaWdpbl9qdGkiOiI5NzhlZWM4My03NjViLTRkMGEtYjg2Yi02MmM3YWNiMTU2NWIiLCJldmVudF9pZCI6ImM3NGZlMWJlLTJmOWYtNDE4Ni04Mjc5LTAzNDc0OGM2MTllOCIsInRva2VuX3VzZSI6ImFjY2VzcyIsInNjb3BlIjoiYXdzLmNvZ25pdG8uc2lnbmluLnVzZXIuYWRtaW4iLCJhdXRoX3RpbWUiOjE2NzY4NTkwODQsImV4cCI6MTY3Njk0NTQ4MywiaWF0IjoxNjc2ODU5MDg0LCJqdGkiOiI3NDY2YzZlZS00YzMzLTQ2NmQtYmI3MS0wYjE4YWNmYmY0NTIiLCJ1c2VybmFtZSI6Im1hcnRpbmdpcmlib25lIn0.RrSRik9Pbew4LnHocyt4FKm1uwUht6d56tY6GWG_5fprg6278pcgFTVvAL4v43SxRCnIO5tdorrRM8Jkqa6hIiP--__vZ01zAonuPknp3pZS6CBo3MLP3-_G-tN4eLbrrysAGLsGRXyF7pEI68D5N854gslMTHrnj-Pe_Wko7mmlKGW-O6F8ks9pY1pURrEvceTcF2hz8AOP3Khn-3bpAMO514Yoog1KQWjKtQXqcmuXc1Q88yR_OI53HOa86W1-VLMezQd5gc2pMFesud4Z_qebc92cQf4hGWb6w5Y7wy3r2nNUX2R-WTBtxTRs_XQySd6TLaGEUPt4yRJoyk8iTg&redirect_uri=https%3A%2F%2Fdetaapi-1-h9040310.deta.app%2F

:warning: **Algunas aclaraciones sobre las consultas** :warning:

* :heavy_exclamation_mark: Tiene que estar todo escrito  en minuscula.

* :white_check_mark: Amazon, Netflix, Hulu y Disney son las plataformas que acepta.

* :x: No utilize caracteres hispanos.

:link: **Aca encontrara los links a las consultas**

:small_blue_diamond: https://detaapi-1-h9040310.deta.app/docs#/default/get_max_duration_get_max_duratio__year___platform___duration_type__get

:small_blue_diamond: https://detaapi-1-h9040310.deta.app/docs#/default/get_score_count_get_score_count__platform___scored___release_year__get

:small_blue_diamond: https://detaapi-1-h9040310.deta.app/docs#/default/get_count_platform_get_count_platform__platform__get

:small_blue_diamond: https://detaapi-1-h9040310.deta.app/docs#/default/get_actor_get_actor__platform___year__get

 ### **Herramientas utilizadas**

:small_orange_diamond: **[Python](https://www.python.org/)**: Lenguaje de programación, aplicado a lo ancho y largo del proyecto.

:small_orange_diamond: **[Pandas](https://pandas.pydata.org/)** : Pandas es una libreria escrita para el lenguaje Python para la manipulación y el análisis de datos.

:small_orange_diamond: **[Matplotlib](https://matplotlib.org/)**: Matplotlib es una libreria en Python  para crear visualizaciones de nuestros datos.

:small_orange_diamond: **[Seaborn](https://seaborn.pydata.org/)**: Seaborn es una libreria de visualización de datos de Python basada en matplotlib.

:small_orange_diamond: **[Scikit-learn](https://scikit-learn.org/stable/)**: Scikir-learn es una libreria basada en Python para crear modelos de apredinzaje libre como machine learning y deep learning.

:small_orange_diamond: **[FastAPI](https://fastapi.tiangolo.com/)** : Framework para la construcción de la API en Python

:small_orange_diamond: **[Uvicorn](https://www.uvicorn.org/)** : Permite controlar el funcionamiento de la API de manera local.

:small_orange_diamond: **[Deta](https://deta.space/)**
: plataforma online y gratuita, que nos permite realizar el deployment de nuestra API.

:small_orange_diamond: **[Gradio](https://gradio.app/)**: Gradio nos sirve para darle una interfaz al modelo de recomendación para que cualquiera pueda usarlo, en cualquier lugar.

:small_orange_diamond: **[Hagginface](https://huggingface.co/)**: Hagginface desarrolla herramientas para crear aplicaciones utilizando el aprendizaje automático.

**Modelo de recomendacion**

¿Es sabado a la noche, sus amigos salieron pero usted prefiere quedarse en casa viendo una pelicula o serie?

Este modelo de recomendación es para Usted!!! 

:link: https://huggingface.co/spaces/TheMith/MachineLearning_recomendacion 


Link al video: 

:red_circle: **AGRADECIMIENTOS** :red_circle:
Me gustaría agradecer a los menteros y la gente detras de toda la parte de HenryLabs, también a mis compañeros de cohorte que me han acompañado en todo este camino y estamos muy cerca de poder finalizarlo.

### Contacto
* GitHub: https://github.com/MartinGiribonee
* Mail: martingiribone27@gmail.com
