# Proyecto: Tierra y Luna en Movimiento

Este proyecto en C++ crea una simulación en perspectiva ortogonal donde se puede observar cómo la Tierra gira sobre sí misma y la Luna orbita alrededor de ella. El usuario puede moverse con el teclado y el ratón para explorar la simulación.

---

## **Requisitos del Sistema**
- Visual Studio 2022 (u otra versión compatible)
- Microsoft Windows 10/11
- Librerías necesarias:
  - OpenGL
  - GLFW
  - GLEW o GLAD
  - GLM

---

## **Instrucciones de Compilación**

1. **Abrir el proyecto:**
   - Descargue y abra el proyecto en Visual Studio 2022.

2. **Configurar las librerías:**
   - Asegúrese de que las librerías **OpenGL**, **GLFW**, y **GLM** estén correctamente configuradas en las propiedades del proyecto.
   - Vaya a `Propiedades del proyecto > VC++ Directories` y agregue las rutas de las librerías y sus respectivos directorios de inclusión.

3. **Seleccionar la configuración:**
   - Seleccione el modo de compilación en `Debug` o `Release` y elija la arquitectura adecuada (`x64`).

4. **Compilar:**
   - Presione `Ctrl + Shift + B` para compilar el proyecto.

---

## **Instrucciones de Ejecución**

1. **Ejecutar el proyecto:**
   - Presione `Ctrl + F5` o haga clic en el botón `Start` en Visual Studio.

2. **Principio Ejecución:**
   - Se le aparecerá en Perspectiva Ortogonal, si quiere cambiar de perspectiva, pulse 'P'.

3. **Observaciones:**
  - Una vez tenga configurada la perspectiva deseada, observará como la Tierra rota sobre si misma y sobre ti. La Luna orbitará alrededor de la Tierra.
  - Se puede observar las correctas texturas y iluminación correcta.

4. **Cámara FPS**
   - La sensibilidad se puede ajustar, ve al apartado de sensivity y cámbialo a su gusto. Nosotros usamos 800 DPI en el mouse.
   - Muévase con 'W' 'A' 'S' 'D', en todas las direccioenes y si quiere subir o bajar en el eje de las z, utilice teclas de arriba y abajo
   - Si desea salir del programa, o bien pulse ESC o pulse 'O' y finalemente la cruz.

---

Disfrute!
