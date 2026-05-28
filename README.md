# ⚔️ BattleCode Arena

¡Proyecto galardonado con el **3er Lugar** en la competencia interna de Fundamentos de Programación! 🏆

**BattleCode Arena** es una aplicación de consola interactiva desarrollada en C# (.NET 9.0). El proyecto transforma un requisito académico tradicional (una ruleta aleatoria para asignar retos de programacion a estudiantes) en un emocionante juego de rol (RPG) ambientado en una arena de combate digital.

---

## 📜 Lore del Juego
> *"Mucho antes de que se forjaran los lenguajes de programación… existió el Caos. Los errores eran monstruos salvajes que devoraban el código naciente. Aquí, los nombres no se escriben... Se compilan en la eternidad."*

Cada ronda evoca aleatoriamente a los participantes de la arena y les asigna roles sagrados:
*   **El Invoker:** El sabio encargado de forjar el desafío y dictar el tiempo límite.
*   **El Guerrero:** El valiente programador del teclado que debe ejecutar el código en tiempo real.
*   **El Sanador:** Un aliado que puede ser invocado para apoyar al Guerrero en momentos de crisis.

---

## 🚀 Características Principales

*   **Sistema de Ruleta Visual:** Animación en consola simulando la velocidad decreciente de una ruleta real para elegir de forma aleatoria y transparente a los participantes.
*   **Mecánicas de Juego Avanzadas:** 
    *   **Habilidades Especiales:** 15 habilidades únicas cargadas dinámicamente desde archivos con diferentes rarezas (Común, Rara, Legendaria) que otorgan ventajas lógicas o de tiempo.
    *   **La Maldición del Caos:** Un evento aleatorio (30% de probabilidad) que deshace los beneficios del Guerrero pero duplica sus recompensas si sobrevive.
*   **Persistencia de Datos:** Carga y guardado automático del estado de los alumnos, historial de encuentros (`historial_selecciones.txt`) y exportación del ranking de la arena (`ranking_final.txt`).
*   **Interfaz de Consola Estilizada:** Uso extensivo de colores (ANSI/ConsoleColor) y arte ASCII para sumergir al usuario en la experiencia del videojuego.

---

## 🛠️ Tecnologías Utilizadas

*   **Lenguaje:** C# 13
*   **Plataforma:** .NET 9.0 (Console Application)
*   **Conceptos lógicos aplicados:** Programación modular (métodos y funciones), manipulación y parsing de archivos de texto (`System.IO`), manejo de matrices/arreglos estructurados, expresiones regulares (`Regex`), y algoritmos de ordenamiento personalizados.

---

## 📦 Instalación y Ejecución

Para compilar y correr la arena en tu máquina local, asegúrate de tener instalado el SDK de .NET 9.0.

1. Clona este repositorio:
```bash
   git clone https://github.com/AliaJimenez/BattleCodeArena
