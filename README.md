![Encabezado del taller](docs/assets/workshop-banner.svg)

# Taller de Unity 2D — Chrome Dino

**Formación en desarrollo de videojuegos · Unity · C# · Física y mecánicas 2D**

Utilicé este proyecto como material práctico en uno de los **talleres de desarrollo de videojuegos que impartí**. El objetivo fue enseñar los fundamentos de Unity y C# a partir de un juego de desplazamiento lateral inspirado en la mecánica del dinosaurio de Chrome.

El ejercicio permite pasar de los conceptos básicos de escenas y componentes a un prototipo jugable con **salto, obstáculos, colisiones, puntuación y progresión de dificultad**.

## Qué trabajamos en el taller

- Crear escenas y organizar **GameObjects**, componentes y prefabs.
- Programar el movimiento de salto mediante **Rigidbody2D** y detectar el suelo.
- Identificar colisiones y gestionar el final de la partida.
- Generar obstáculos utilizando **corrutinas** e intervalos aleatorios.
- Simular un escenario continuo mediante desplazamiento y reposicionamiento del suelo.
- Llevar la puntuación y modificar la velocidad del juego.

## Código del ejercicio

| Script | Conceptos de programación |
| --- | --- |
| [PlayerJump.cs](Assets/Scripts/PlayerJump.cs) | Salto, Rigidbody2D, detección de suelo y colisiones |
| [ObstacleSpawner.cs](Assets/Scripts/ObstacleSpawner.cs) | Aparición de obstáculos, aleatoriedad y corrutinas |
| [GameManager.cs](Assets/Scripts/GameManager.cs) | Puntuación, velocidad y final de partida |
| [Scroll.cs](Assets/Scripts/Scroll.cs) | Movimiento del escenario |
| [SueloInfinito.cs](Assets/Scripts/SueloInfinito.cs) | Reposicionamiento del suelo para mantener continuidad |

## Cómo abrir el proyecto

1. Instala **Unity Hub** y la versión **Unity 2023.2.20f1**, registrada en [ProjectVersion.txt](ProjectSettings/ProjectVersion.txt).
2. Descarga o clona el repositorio:

   ```bash
   git clone https://github.com/isaiassolis/unity-2d-chrome-dino-workshop.git
   ```

3. Abre la carpeta desde Unity Hub.
4. Carga `Assets/Scenes/SampleScene.unity` y presiona **Play**.
5. Para saltar, utiliza la **barra espaciadora**, según la implementación de `PlayerJump.cs`.

## Mi participación

Preparé y utilicé este ejercicio como parte de mi experiencia como **instructor de programación y desarrollo de videojuegos**. El proyecto permite explicar, con código y mecánicas visibles, cómo se relacionan los elementos de un juego 2D.

El repositorio conserva el material de trabajo para que otras personas puedan **inspeccionar los scripts, estudiar su funcionamiento y experimentar con cambios**.

## Sobre el material

Es un **ejercicio educativo**, no una versión oficial de Chrome Dino ni un videojuego comercial. Los recursos gráficos de terceros deben utilizarse conforme a sus licencias y condiciones respectivas.

**Otro taller de Unity:** [DrawFight — Plataformas 2D](https://github.com/isaiassolis/unity-2d-platformer-workshop).

---

[Volver a mi portafolio profesional](https://github.com/isaiassolis)
