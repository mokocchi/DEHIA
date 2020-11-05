# DEHIA
Una plataforma para la creación de actividades de recolección de datos con intervención humana a ser ejecutados en un dispositivo móvil

Cada directorio originalmente era un repositorio con su mismo nombre que pueden encontrarse en este mismo usuario de GitHub.

En `Artículos relacionados` pueden encontrarse los artículos publicados en torno al objetivo de la tesina.

El código está organizado de la siguiente manera:

- El cliente web está en `prototipo-app-actividades` y se inicia con `yarn install` ; `yarn start` (previa instalación de yarn)
- El gateway está en `dehia_gateway` y se inicia con `docker-compose up` (previa instalación de docker y docker compose)
- Los microservicios están en `dehia_auth`, `dehia_define`, `dehia_collect` y `dehia_results`. Se inician con `docker-compose up`
- La aplicación móvil está en `prototipo-app-actividades` y se inicia con `react-native start`; `react-native run-android`
- En `dehia_mocks` hay mocks de reemplazo de los servicios define y auth, en caso de querer probar solamente el cliente
