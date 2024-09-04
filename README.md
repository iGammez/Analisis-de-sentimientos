**Características**

- **Interacción con la API de YouTube:** Utiliza la API de YouTube para obtener información detallada sobre videos.
- **Extracción de datos:** Recopila datos como el ID del video, comentarios, cantidad de vistas, likes, y más.
- **Salida en CSV:** Los datos recopilados pueden ser guardados en un archivo CSV para un análisis más detallado.

## Requisitos

Para ejecutar este script, asegúrate de tener los siguientes requisitos:

- Python 3.x
- Bibliotecas:
  - `google-api-python-client`
  - `scipy`

Puedes instalar estas dependencias utilizando pip:

```bash
pip install google-api-python-client scipy
```

## Configuración

1. **API Key de YouTube:**  
   Necesitarás una clave de API de YouTube válida para poder utilizar la API. Puedes obtenerla desde la [Consola de Desarrolladores de Google](https://console.developers.google.com/).

2. **ID del Video:**  
   Reemplaza el `video_id` en el script con el ID del video del que deseas recopilar datos.

## Uso

1. Clona el repositorio o descarga el script directamente.
2. Instala las dependencias necesarias.
3. Configura tu clave de API y el ID del video en el script.
4. Ejecuta el script:

```bash
python youtube_automatizado.py
```

5. Los datos se guardarán en un archivo CSV para su análisis posterior.

## Advertencia

- **Uso de la API:** Asegúrate de respetar los límites de la API de YouTube y no exceder el límite de cuotas.
- **Seguridad:** No compartas tu clave de API públicamente. Manténla segura y fuera de repositorios públicos.

## Contribuciones

Si deseas contribuir a este proyecto, siéntete libre de enviar un pull request o abrir un issue en el repositorio.

## Licencia

Este proyecto está licenciado bajo la MIT License. Consulta el archivo `LICENSE` para obtener más detalles.

---

¿Hay algún detalle específico que te gustaría agregar o modificar?
