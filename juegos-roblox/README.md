# Juegos Roblox

Proyecto para crear juegos de Roblox con ayuda de Claude.

## Estado

- [x] Investigar cómo puede Claude trabajar con Roblox Studio
- [ ] Preparar el computador (pasos de abajo)
- [ ] Elegir el primer juego
- [ ] Crear la skill de Roblox para Claude (opcional, Claude la puede hacer)

## Qué hacer cuando estés en el computador

### 1. Instalar lo necesario
1. Instala **Roblox Studio** e inicia sesión con tu cuenta de Roblox.
2. Instala la **app de escritorio de Claude** (claude.ai/download) e inicia sesión con tu cuenta.
   - Alternativa para usuarios más técnicos: **Claude Code** en la terminal.

### 2. Activar el MCP oficial de Roblox (lo más importante)
El MCP deja que Claude hable directamente con Roblox Studio: ejecutar código,
crear objetos, leer errores y probar el juego, sin tener que hacer clics.

1. Abre Roblox Studio y abre (o crea) un lugar (place).
2. Haz clic en el menú **…** → **Manage MCP Servers**.
3. Activa **Enable Studio as MCP server**.
4. Sigue la guía oficial para conectarlo con Claude:
   https://create.roblox.com/docs/en-us/studio/mcp.md
5. Reinicia la app de Claude y comprueba que aparecen las herramientas de Roblox Studio.

> Usa el MCP **oficial de Roblox**. Hay alternativas de la comunidad
> (por ejemplo `robloxstudio-mcp`), pero no son de Roblox y tendrían control sobre tu Studio.

### 3. (Opcional) Activar "Computer use"
Solo si quieres que Claude también pueda ver tu pantalla y hacer clics:
app de Claude → **Settings → This computer → Computer use**.
Con el MCP normalmente no hace falta.

### 4. Empezar
Abre una conversación nueva en la app de escritorio, con Roblox Studio abierto, y escribe algo como:

> "Lee el proyecto juegos-roblox de mi repositorio zer0-sudo/zer0-sudo.github.io.
> Quiero hacer un [obby / tycoon / simulator / ...]. Usa el MCP de Roblox Studio."

## Qué hace Claude y qué te toca a ti

| Claude | Tú |
|---|---|
| Todos los scripts (Luau) | Aprobar los permisos |
| Interfaces (GUI) | Publicar el juego desde tu cuenta |
| Mapas sencillos hechos con código | Todo lo que tenga Robux (Game Passes, precios) |
| Probar y corregir errores | Subir tus propios sonidos e imágenes |
| Buscar modelos en la Toolbox | Decidir si el juego es divertido |

## Ideas de juegos
1. **Obby**: checkpoints, temporizador, tabla de récords
2. **Tycoon**: botones de compra, dinero automático, guardado de progreso
3. **Simulator**: clics, niveles, mascotas, rebirths
4. **Minijuegos por rondas**: lobby, cuenta regresiva, mapas aleatorios
5. **Supervivencia por oleadas**: enemigos que te persiguen
