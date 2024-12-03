# Autor
**Christian Quinteros**

**lima-code-201n4**

**christian_quinteros@outloo.com**

**02/12/2024**

# Sobre el projecto

En “La Web Moderna” podrás leer los conceptos clave que todo Desarrollador de Software debe saber para crear aplicaciones web.

# eslintrc

1. "env"
Define los entornos en los que se ejecutará el código. Esto habilita configuraciones específicas para esos entornos.
	"browser": true: Habilita las variables globales del entorno del navegador (como window, document, etc.).
	•	"es2021": true: Especifica que el código usa características de ECMAScript 2021 (ES12).
2. "extends"
Especifica un conjunto de reglas predefinidas que ESLint usará como base.
	•	"eslint:recommended": Activa las reglas recomendadas por ESLint, que incluyen validaciones básicas de buenas prácticas y errores comunes.
3. "parserOptions"

Define las opciones para el analizador (parser) que ESLint usa para interpretar el código.
	•	"ecmaVersion": "latest": Indica que se utilizará la última versión de ECMAScript compatible con ESLint.
	•	"sourceType": "module": Especifica que el código usa módulos de JavaScript (import y export).

4. "rules"

Personaliza reglas específicas para el proyecto. Cada regla puede configurarse como:
	•	"off" o 0: Desactiva la regla.
	•	"warn" o 1: Muestra una advertencia.
	•	"error" o 2: Lanza un error.

Explicación de cada regla:
1.	"indent": ["error", 2]
	•	Enforce un indentado de 2 espacios.
	•	Si el código no cumple, lanza un error.
2.	"linebreak-style": ["error", "unix"]
	•	Obliga a usar saltos de línea estilo Unix (\n).
	•	Si se usan saltos de línea estilo Windows (\r\n), lanza un error.
3.	"quotes": ["error", "single"]
	•	Obliga al uso de comillas simples (') para las cadenas de texto.
	•	Si usas comillas dobles ("), lanza un error.
4.	"semi": ["error", "always"]
	•	Obliga a usar punto y coma (;) al final de cada sentencia.
	•	Si se omite, lanza un error.
5.	"no-unused-vars": "warn"
	•	Genera una advertencia si hay variables declaradas pero no utilizadas.
	•	No detiene la ejecución, pero señala la posible ineficiencia.
6.	"no-console": "warn"
	•	Genera una advertencia si se usa console.log u otras funciones de consola.
	•	Esto fomenta evitar el uso de logs en el código final.    

# Despliegue
[Texto del enlace](URL)