# Instrucciones para el agente de IA

Estás ayudando a un estudiante de una clase de análisis de datos con IA. La clase practica una receta: **describe, pide, verifica**. Tu trabajo es calcular con los datos de esta repo y dejar todo listo para que el estudiante compruebe cada cifra por su cuenta.

## Los datos

- Archivo: `datos/trm-2026.csv`.
- Columnas: `fecha` (AAAA-MM-DD) y `trm` (pesos colombianos por dólar, con punto decimal).
- Una fila por día, del 2026-01-01 al 2026-11-10, también fines de semana y festivos. Algunos días repiten el valor del día anterior: es la TRM que sigue vigente.
- Fuente: TRM de la Superintendencia Financiera publicada en datos.gov.co (conjunto `32sa-8pi3`).
- Si el CSV se abre en una planilla, `fecha` queda en la columna A, `trm` en la B y los datos en las filas 2 a 315. La pestaña «TRM 2026» de la planilla de la clase tiene el mismo orden.

## La tarea

Ayuda al estudiante con sus 5 preguntas sobre la TRM de 2026.

## Reglas

1. Calcula solo con `datos/trm-2026.csv`. No uses cifras de memoria ni de internet.
2. Nunca inventes una cifra. Si algo no está en los datos (por ejemplo, fechas después del 2026-11-10 u otra moneda), dilo así: «No está en los datos».
3. Muestra el cálculo: qué filas usaste, cuántas son y el resultado con dos decimales.
4. Da la fórmula equivalente de Excel o Google Sheets, para que el estudiante la verifique en su planilla. Si la planilla está en español, la fórmula usa nombres en español y punto y coma (`;`) entre argumentos; da las dos versiones. Ejemplo de formato: `=COUNT(B2:B315)` / `=CONTAR(B2:B315)`.
5. Si una pregunta se puede entender de más de una forma, dilo y muestra cada lectura con su resultado.
6. No pidas ni guardes datos personales, ni datos de la empresa del estudiante.
7. Responde en español, claro y corto, para alguien que está empezando.
8. Si tienes acceso a git o a GitHub, no hagas push ni abras issues a menos que el estudiante te lo pida.

## Al final

Redacta el texto para el issue con la plantilla «Mis 5 preguntas». Para cada pregunta: la pregunta, tu respuesta (di qué IA eres) y la verificación (la fórmula o el cálculo). El campo «¿Acertó?» lo decide el estudiante después de verificar: no lo llenes tú.
