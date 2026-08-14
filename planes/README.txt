PLANES DE CLASE — APP V2

ARCHITECTURA
Google Sheets = editor / fuente de datos
plan.html = interfaz única para todos los cursos
Canvas = embed de una URL distinta por curso

URLS
plan.html?curso=cco460
plan.html?curso=cco125
plan.html?curso=cmu350

CÓMO CONECTAR GOOGLE SHEETS
1. En Google Sheets, publique cada pestaña individualmente en la Web como CSV.
2. Copie la URL CSV de cada pestaña.
3. Abra config.js y péguela en csvUrl del curso correspondiente.
4. No hay que tocar app.js ni plan.html.

ENCABEZADOS ESPERADOS
Semana | Día # | Día | Fecha | Temas / Módulos | Tareas / Material | Notas

NOTA SOBRE CANVAS
Para un embed estable, aloje esta carpeta en un sitio HTTPS (por ejemplo GitHub Pages). Luego use la URL plan.html?curso=... en cada curso.

La app conserva datos locales de respaldo, por lo que también funciona antes de conectar Google Sheets.

SEMANA 1
La Semana 1 es la semana institucional que contiene el martes 11 de agosto (10–16 de agosto). El resaltado de “semana actual” usa esta misma referencia en todos los cursos.

CMU 350
Se ha creado la estructura inicial para CMU 350 ~ Análisis de Datos, lunes 12:30–2:00 pm, SM 104. Los contenidos quedan por definir.

MODO CANVAS / PRODUCCIÓN
------------------------
Para ocultar el enlace "Todos los cursos", use:
  plan.html?curso=cco460&embed=1
  plan.html?curso=cco125&embed=1
  plan.html?curso=cmu350&embed=1
También funciona mode=canvas.

INF 105
- Curso 100% asincrónico: se presenta por semanas, no por días de reunión.
- Canvas producción: plan.html?curso=inf105&embed=1
- Google Sheets: publique la pestaña INF 105 como CSV y pegue su URL en config.js.
