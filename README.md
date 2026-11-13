# Clase · Tus 5 preguntas verificadas

Repo de la clase del módulo 1. Aquí están los datos y las instrucciones para tu IA.

La portada, con las diapositivas, la guía y los datos, está en [`index.html`](index.html). En GitHub Pages queda en https://maarmapa.github.io/clase-cdia01/. El material de cada clase está en [`clases/`](clases/).

## La idea

No revises archivos a mano: dale los datos a tu IA y verifica lo que te responde.

La receta:

1. **Describe** qué quieres saber.
2. **Pide** a tu IA que lo calcule con estos datos.
3. **Verifica** el resultado con una fórmula o un cálculo tuyo.

## Los datos

`datos/trm-2026.csv`: la TRM (pesos colombianos por dólar) del 1 de enero al 10 de noviembre de 2026.

- Columnas: `fecha` (AAAA-MM-DD) y `trm` (con punto decimal).
- Hay una fila por día, también fines de semana y festivos. Algunos días repiten el valor del día anterior: es la TRM que sigue vigente.
- Fuente: TRM de la Superintendencia Financiera publicada en [datos.gov.co](https://www.datos.gov.co/) (conjunto `32sa-8pi3`).

Enlace directo al archivo: https://raw.githubusercontent.com/Maarmapa/clase-cdia01/main/datos/trm-2026.csv

Para descargarlo, abre `datos/trm-2026.csv` aquí en GitHub y usa el botón **Download raw file**.

## Conecta tu IA a los datos

Elige la forma que te sirva:

- **Solo el navegador.** Adjunta el CSV en ChatGPT, Gemini o Claude. Si tu chat puede abrir enlaces, también puedes pegarle el enlace directo.
- **Computador del trabajo.** Adjunta el CSV en Copilot. Si prefieres Excel, usa la planilla de la clase (el enlace está en la guía): un CSV abierto directo en Excel con configuración en español puede leer mal los decimales.
- **Tu stack.** Clona la repo o ábrela con tu agente (OpenCode, Claude Code o Copilot). Tu agente lee `AGENTS.md`; si no lo hace solo, pídele: «Lee AGENTS.md y ayúdame con mis 5 preguntas».

```bash
git clone https://github.com/Maarmapa/clase-cdia01.git
```

Si no usas git: botón verde **Code** › **Download ZIP**.

**Multimodal:** una captura de tu gráfico también sirve. Pégala en el chat y pregúntale a la IA qué ve. Después verificas con los datos.

## Comparte tus 5 preguntas

Abre un issue con la plantilla [«Mis 5 preguntas»](https://github.com/Maarmapa/clase-cdia01/issues/new?template=mis-5-preguntas.yml). Necesitas una cuenta de GitHub (es gratis).

Esto es para conversar en clase. La entrega oficial sigue siendo en el campus del curso.

## Importante

Esta repo es pública: cualquiera puede ver lo que escribas aquí. No pongas datos personales ni datos de tu empresa.
