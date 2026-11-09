# Bases-De-Datos-MySQL (Bases de Datos, 1º DAM)

## Cómo trabajar conmigo
Reglas comunes a todos mis repos (copia de mi `C:\dev\CLAUDE.md`, para que también las lean las sesiones en la nube). Soy estudiante de DAM en el IES Isidra de Guzmán.
- En prácticas evaluables, resuélvelas completas (sin modo de pistas). Al terminar, crea junto a la entrega (en `docs/` si existe) un `guia-defensa-<practica>.md` para defenderla en clase, al estilo de la guía de DataStock. Las guías de defensa no se suben nunca a GitHub: cada repo tiene `guia-defensa-*.md` en su `.gitignore` (añádelo si falta).
- Estructura de la guía de defensa: cómo usarla; cómo arrancar, ejecutar y ensayar sin estropear la entrega; qué pide el enunciado y dónde se cumple cada requisito; visión general (capas, flujo, decisiones de diseño a justificar); y por cada requisito: qué pide, dónde está, explicación línea a línea, cómo demostrarlo, errores típicos, preguntas de la profesora con su respuesta y 🔧 modificaciones en directo (el cambio que podrían pedir, con el código exacto y dónde va). Al final: casos prácticos «¿qué pasaría si…?», «corrige este error» (síntoma → causa → arreglo) y chuleta con plan de ensayo.
- Si la tarea es grande, antes de tocar nada dime cómo lo harías (plan por pasos) y espera a que lo apruebe o lo corrija.
- Cuando escribas código, explícalo línea por línea y di por qué elegiste esa forma y no otra.
- Si ves un error de concepto o algo que no entiendo bien, dímelo aunque no te lo pregunte.
- Responde en español.
- No hagas commit ni push sin que te lo pida. Commits sin `Co-Authored-By` ni líneas de atribución.
- No subas binarios generados (`target/`, `*.class`, `__pycache__/`, `*.pyc`, `bin/`, `obj/`, `Library/` de Unity).
- Nunca leas, muestres ni subas ficheros `.env`, tokens ni credenciales.
- PDFs, .docx, .odt y .pptx son apuntes o enunciados: léelos solo si hacen falta para la tarea.

Teoría, ejercicios y exámenes de MySQL por unidad. Mayoritariamente PDF/ODT, diagramas drawio y scripts `.sql`.

## Estructura
- `ut01-introduccion-a-las-bases-de-datos/`
- `ut02-diseno-conceptual-y-modelo-relacional/` — diagramas E/R (`.drawio`), paso a relacional, normalización.
- `ut03-lenguaje-sql-y-ddl-dml/` — 3.1 creación BD, 3.2 tablas, 3.3 DML, 3.4 usuarios, `examenes/`.
- `ut04-consultas-avanzadas-y-vistas/` — 4.1 básicas … 4.6 vistas, 4.7 optimización.
- `ut05-edicion-de-datos-y-transacciones/`, `ut06-programacion-de-bases-de-datos/` (procedimientos, funciones, cursores, triggers).
- `examenes-ut05-y-ut06/`

## Trabajar con SQL
- Scripts para MySQL 8: `mysql -u root -p < script.sql`, o MySQL Workbench.
- Al escribir SQL usa sintaxis MySQL (no PostgreSQL/SQL Server) y comenta cada consulta.

## Notas
- `contrasena-mysql-exportar-archivo-sql.odt` en la raíz puede contener credenciales: no lo leas ni lo cites.
