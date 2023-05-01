# NLP_Project_1

## Pipeline API

Para correr el API responsable de crear las respuestas del Pipeline se debe instalar Flash API:

`python -m pip install fastapi uvicorn[standard]`

Posteriormente navegar hasta la carpeta `/pipeline/API_pipeline` y ejecutar el comando 

`uvicorn main:app --reload`

a través de la URL `http://127.0.0.1:8000/Aqui va la review` podemos obtener un JSON con el sentimiento asociado
