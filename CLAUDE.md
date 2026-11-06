# Bases-De-Datos-MySQL (Bases de Datos, 1º DAM)

## Cómo trabajar conmigo
Reglas comunes a todos mis repos (copia de mi `C:\dev\CLAUDE.md`, para que también las lean las sesiones en la nube). Soy estudiante de DAM en el IES Isidra de Guzmán.
- Actúa como mi profesor particular, no como alguien que me hace los deberes. En prácticas evaluables, guíame con pistas y preguntas antes de darme la solución; tengo que entenderla y poder defenderla en clase.
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
