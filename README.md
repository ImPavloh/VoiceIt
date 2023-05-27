<div align="center">
  
![VoiceIt](https://i.imgur.com/DendqCA.png)
  
<a href="https://github.com/ImPavloh/VoiceIt" target="_blank"><img src="https://img.shields.io/github/license/impavloh/voiceit?style=for-the-badge&logo=github&logoColor=white"></a>
<a href="https://twitter.com/ImPavloh" target="_blank"><img src="https://img.shields.io/badge/Seguir-%231DA1F2.svg?style=for-the-badge&logo=twitter&logoColor=white"></a>
<a href="https://huggingface.co/spaces/ImPavloh/voiceit/tree/main" target="_blank"><img src="https://img.shields.io/badge/HuggingFace-%23E06011.svg?style=for-the-badge"></a>

**https://pavloh.com/#/voiceit**
</div>

# 🎙️ VoiceIt!

Este proyecto utiliza modelos pre-entrenados para cambiar la voz en archivos de audio. El servicio permite cargar archivos de audio en formato `.wav`, seleccionar un modelo de voz y generar un nuevo archivo de audio con la voz modificada.

# 📚 Información relevante 🚀

Puedes utilizar VoiceIt! online en **https://pavloh.com/#/voiceit** o utilizar tus recursos y alojar el proyecto localmente siguiendo los siguientes pasos.

### Requisitos

- Python >3.7
- Gradio
- FFmpeg
- FFprobe

### 🛠️ Instalación

1. Clona el repositorio:
`git clone https://github.com/impavloh/voiceit.git`

2. Cambia al directorio del proyecto:
`cd voiceit`

3. Crea una carpeta llamada "modelos" e importa modelos pre-entrenados para utilizar más tarde. En este caso puedes utilizar mis modelos: https://huggingface.co/spaces/ImPavloh/voiceit/tree/main/modelos


5. Instala las dependencias necesarias:
`pip install -r requirements.txt`

5. Ejecuta el script principal:
`python voiceit.py`

### 📝 Uso

1. Al ejecutar el archivo voiceit.py se abrirá un terminal con un enlace para poder acceder a la interfaz de VoiceIt!. Por ejemplo: `http://localhost:7860`

2. Selecciona un modelo de voz de la lista desplegable.

3. Carga un archivo de audio en formato `.wav` sin ruido, otras voces o música de fondo.

4. Haz clic en el botón "Cambiar voz" para generar un nuevo archivo de audio con la voz modificada.

5. Escucha el resultado en el reproductor de audio.

6. Puedes borrar los datos y reiniciar el proceso utilizando el botón "Borrar".

## ⚠️ Advertencia

- Los archivos de audio deben estar en formato `.wav`.
- Los archivos de audio deben contener solo una voz y estar libres de ruido o música de fondo.
- El tiempo de conversión dependerá de la duración del audio y del uso de la web (en caso de utilizarlo localmente dependerá de tus recursos)

## 📝 Licencia y términos de uso

Al utilizar este proyecto, aceptas la [licencia](https://github.com/ImPavloh/voiceit/blob/main/LICENSE) y los [términos de uso](https://github.com/ImPavloh/voiceit/blob/main/TERMINOS_DE_USO.txt).
