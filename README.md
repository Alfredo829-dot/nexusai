# NexusAI web (v1.0.0)
Página única `index.html` (HTML + CSS + JS vanilla, sin dependencias ni CDNs). Español, modo oscuro, pensada para el celular.
- Varios chats con historial (IndexedDB; si no hay, localStorage). Borrar historial / chat / todo.
- 5 APIs OpenAI-compatibles con prioridad editable y fallback automático: Gemini, Groq, OpenRouter, Mistral, Cohere (URL y modelo por defecto, editables).
- Streaming SSE, respaldo sin stream, botón Detener, Reintentar, Copiar, bloques de código.
- BYOK: sin claves en el código. Las claves se guardan solo en este navegador (localStorage, o sessionStorage si apagas «Recordar claves») y solo se envían al proveedor elegido. Nunca se escriben en consola.
- `sw.js` (opcional, solo https) permite abrir sin conexión / instalar como app. `index.html` funciona solo, abierto desde cualquier hosting estático.
