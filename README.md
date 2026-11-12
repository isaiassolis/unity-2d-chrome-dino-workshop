![Encabezado del taller](docs/assets/workshop-banner.svg)

# Taller de desarrollo de videojuegos 2D · Chrome Dino

**Proyecto didáctico de Unity y C# utilizado como apoyo en un taller que impartí.** El ejercicio consiste en construir un juego de desplazamiento lateral inspirado en el dinosaurio de Chrome, para explorar las bases de programación y mecánicas 2D.

> **Contexto:** material de enseñanza y práctica; no es un producto comercial ni una versión oficial del juego de Chrome. La inclusión del proyecto documenta la experiencia de formación, no acredita resultados o número de participantes.

## Objetivos de aprendizaje

- Trabajar con escenas, GameObjects, componentes y prefabs en Unity.
- Programar movimiento, salto y detección de colisiones con C#.
- Usar animaciones y controlar estados del personaje.
- Generar obstáculos con intervalos aleatorios mediante corrutinas.
- Implementar puntuación, progresión de velocidad y reinicio de escena.

## Implementación que se puede explorar

| Script | Concepto |
| --- | --- |
| [PlayerJump.cs](Assets/Scripts/PlayerJump.cs) | Rigidbody2D, salto, detección de suelo y colisiones |
| [ObstacleSpawner.cs](Assets/Scripts/ObstacleSpawner.cs) | Generación aleatoria de obstáculos y corrutinas |
| [GameManager.cs](Assets/Scripts/GameManager.cs) | Puntuación, velocidad y estado de fin de partida |
| [Scroll.cs](Assets/Scripts/Scroll.cs) | Desplazamiento del escenario |
| [SueloInfinito.cs](Assets/Scripts/SueloInfinito.cs) | Reposicionamiento del suelo para simular continuidad |

## Abrir el proyecto

1. Instala Unity Hub y la versión **Unity 2023.2.20f1** indicada en [ProjectVersion.txt](ProjectSettings/ProjectVersion.txt).
2. Clona el repositorio: `git clone https://github.com/isaiassolis/unity-2d-chrome-dino-workshop.git`.
3. Abre la carpeta del proyecto desde Unity Hub.
4. En Unity, abre `Assets/Scenes/SampleScene.unity` y ejecuta con **Play**.
5. El script `PlayerJump.cs` implementa el salto con **barra espaciadora**; otros controles deben comprobarse en la escena.

No se ha realizado una compilación ni una prueba de ejecución como parte de esta actualización documental. Algunas mecánicas descritas en el README anterior requieren verificación en Unity.

## Alcance y materiales

El repositorio incluye el proyecto de Unity, scripts, prefabs, escenas y recursos gráficos. Es un **ejercicio didáctico**, no un juego terminado para distribución comercial. Los recursos externos conservan sus respectivas condiciones de uso; revisa las licencias de los assets antes de reutilizarlos o redistribuirlos.

**Proyecto relacionado:** [Taller de plataformas 2D · DrawFight](https://github.com/isaiassolis/unity-2d-platformer-workshop).

---

[Perfil profesional y otros proyectos de formación](https://github.com/isaiassolis)
