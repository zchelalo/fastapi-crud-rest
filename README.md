# fastapi-crud-rest
API REST de practica hecha con FastAPI.  
Almacena los datos en memoria para que despues puedas consultarlos mediante los distintios métodos HTTP.

## **Instalación:**  
Para probar la API debe tener instalado python, una vez con python instalado clone el proyecto:  
> *git clone https://github.com/zchelalo/fastapi-crud-rest.git*  
  
Despues de ello asegurese de estar dentro de la carpeta del proyecto y corra el siguiente comando:  
> *pip install -r requirements.txt*  
Es posible que si tiene mas de una versión de python falle y deba correr el siguiente comando en lugar del anterior:  
> *pip3 install -r requirements.txt*  
  
Una vez hecho esto deberá correr el servidor con uvicorn a traves del siguiente comando:  
> *uvicorn app:app*  
En caso de que quiera hacer un cambio y este se refleje automaticamente en el servidor deberá ejecutar el siguiente comando en lugar del anterior:  
> *uvicorn app:app --reload*  
  
Una vez hecho todo esto basta con probar la aplicación dirigiendose a cada endpoint con la URL *http://localhost:8000/* en la cual esta alojado nuestro servidor.  
  
## **Documentación:**  
Para poder ver la documentación a la vez que probar la API REST nos podremos dirigir a *http://localhost:8000/docs* una vez que nuestro servidor este activo.  
  
En esta ruta se podrán ver todos los endpoints de la API y podremos probar cada uno de ellos desde ahí mismo, siendo esto muy útil a la hora de testear.