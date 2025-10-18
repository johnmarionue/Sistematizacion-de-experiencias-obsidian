### ¿Qué Pasa Si Alguien No Sigue los Pasos Correctamente?

#### Escenario 1: Se olvidan de hacer pull antes de editar
- *Solución:* El plugin Obsidian Git generalmente lo detecta y les avisa
- *Prevención:* Con la opción "Auto pull on application start" activada, es menos probable

#### Escenario 2: Editan el mismo archivo a la misma vez
- *Solución:* Git es inteligente y puede fusionar cambios automáticamente si son en líneas diferentes
- *Si hay conflicto real:* Git les mostrará un mensaje claro y el plugin les guiará para resolverlo

#### Escenario 3: Alguien rompe algo sin querer
- *¡La ventaja de Git!:* Puedes revertir a cualquier versión anterior
- Ve a GitHub → Tu repositorio → Archivo afectado → *History* → Revert