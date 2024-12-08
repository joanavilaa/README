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

2. **Interfaz de Usuario:**
   - La simulación utiliza una perspectiva ortogonal.
   - Verá la Tierra girando sobre su propio eje mientras la Luna orbita alrededor de la Tierra y frente a la cámara.

3. **Controles:**
   - Mueva la cámara con las teclas `W`, `A`, `S`, `D` (movimiento hacia adelante, atrás y laterales).
   - Cambie el ángulo de visión con la rueda del ratón (teclas de arriba y abajo).
   - Salga del programa pulsando `Esc` o cerrando la ventana.

---

## **Notas Adicionales**
- Asegúrese de tener instaladas todas las dependencias necesarias antes de compilar.
- Si experimenta problemas, verifique las rutas de inclusión y los directorios de las librerías en las propiedades del proyecto.
- La simulación es educativa y está optimizada para aprender los conceptos básicos de OpenGL y visualización 3D.

---

**Disfruta del viaje espacial virtual! 🚀**
