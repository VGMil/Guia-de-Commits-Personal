🧩 Guía de Commits Personal
Esta guía describe la convención de mensajes de commit que busco usar en cada proyecto. Incorporar emojis para facilitar la lectura y clasificación de cambios en el historial.

✅ Formato General
<emoji> <tipo(scope)?>: <descripción breve en minúsculas>
tipo: puede ser feat, fix, chore, etc.
scope (opcional): indica el área del código afectada (ej. auth, api, ui).
descripción: clara y concisa, en presente y en minúscula.
✨ Ejemplos de Commits
✨ feat(auth): añadir inicio de sesión con Google
🐛 fix(api): manejar error 404 en fetch de productos
🎨 style(button): ajustar padding para mejor alineación
♻️ refactor(utils): simplificar función de formateo de fecha
📚 docs: actualizar documentación de instalación
🔥 chore: eliminar archivo de configuración obsoleto
🚀 perf(images): reducir tamaño de imágenes de portada
🔧 chore(lint): agregar reglas de ESLint para hooks
📌 Emojis Recomendados
Emoji	Tipo	Descripción rápida
✨	feat	Nueva funcionalidad
🐛	fix	Corrección de bugs
♻️	refactor	Refactorización de código
🎨	style	Cambios de estilo (no funcionales)
🧪	test	Nuevas pruebas o actualizaciones
📚	docs	Documentación
🔥	chore	Eliminaciones, limpieza
🚀	perf	Mejora de rendimiento
🔧	chore	Configuración o mantenimiento
📦	build	Empaquetado o dependencias
🚨	lint	Correcciones de linter
💄	ui	Cambios en la interfaz de usuario
🧠 Recomendaciones
Prefiere commits atómicos: un cambio por commit.
Usa el presente y evita descripciones genéricas como "cambios" o "actualización".
