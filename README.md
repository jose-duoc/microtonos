# 🎵 Simulador de Microtonos en Python

Un simulador interactivo en consola que permite gestionar y reproducir frecuencias sonoras (microtonos) utilizando la biblioteca nativa de Windows `winsound`. El script recrea una secuencia melódica basada en un sistema de asignación de recursos limitados.

---

## ✨ Características

* **Gestión de Recursos:** Dispones de un límite máximo de 25 microtonos para activar de forma simultánea o secuencial.
* **Reproducción de Sonido Activa:** Utiliza frecuencias reales en Hz y duraciones en milisegundos para generar ondas sonoras desde la consola.
* **Monitoreo en Tiempo Real:** Permite revisar cuántos recursos quedan disponibles y cuántos están "haciendo vibrar el ambiente".
* **Recuperación Dinámica:** Capacidad de liberar microtonos activos para volver a utilizarlos posteriormente.

---

## 🛠️ Requisitos de Sistema

Este proyecto está diseñado exclusivamente para **Windows**, ya que utiliza una librería nativa del sistema operativo.

* **Python 3.x**
* **Sistema Operativo:** Windows (requerido para el módulo `winsound`).

---

## 🚀 Instalación y Uso

1. **Clona este repositorio** en tu máquina local:
   ```bash
   git clone [https://github.com/TU_USUARIO/TU_REPOSITORIO.git](https://github.com/TU_USUARIO/TU_REPOSITORIO.git)
Navega a la carpeta del proyecto:Bashcd tu-repositorio
Ejecuta el simulador:Bashpython simulador.py
🎮 Cómo Funciona (Menú Principal)Al iniciar el programa de consola, te encontrarás con el siguiente panel de control:Ver cuántos microtonos quedan libres: Muestra el espacio disponible para nuevas activaciones.Activar microtonos: Digita la cantidad que deseas escuchar. El programa reproducirá una secuencia musical combinando frecuencias (Hz) y duraciones específicas.Recuperar microtonos: Devuelve los microtonos activos al pozo de disponibles (emite un pitido de confirmación).Monitorear el sonido actual: Indica cuántos microtonos están activos actualmente.Salir: Cierra el simulador de forma segura.📝 Nota sobre el CódigoEl script incluye un arreglo predefinido de frecuencias musicales que simulan una melodía estructurada:Frecuencias básicas: Desde los $440\text{ Hz}$ (Nota LA) hasta armónicos superiores como $1174\text{ Hz}$.Duraciones: Variables entre $180\text{ ms}$ y $800\text{ ms}$ para dar dinamismo al ritmo.
