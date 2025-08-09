# gaticonStandards – templateLaTeX

Plantilla en **LaTeX** organizada en múltiples archivos para facilitar el mantenimiento, arreglo y organización.

Repositorio: [https://github.com/marcosgatica2003/gaticonStandards](https://github.com/marcosgatica2003/gaticonStandards)

Versión: 9-08-2025

---

## 📂 Estructura de la plantilla

- main.tex # Archivo principal que compila el documento
- caratula.tex # Diseño de la carátula
- comandos.tex # Definición de comandos personalizados
- fancyConfig.tex # Configuración del estilo de página (fancyhdr)
- indiceConfig.tex # Configuración del índice
- packages.tex # Lista de paquetes \usepackage necesarios


---

## 📄 Descripción de archivos

### `main.tex`
Archivo principal del proyecto. Se encarga de incluir todos los demás `.tex` y construir el PDF final.

### `caratula.tex`
Define el diseño de la carátula del documento (título, autor, fecha, etc.).

### `comandos.tex`
Contiene comandos útiles definidos por el usuario para agilizar la escritura y el formateo en LaTeX.

### `fancyConfig.tex`
Configuración de **fancyhdr** para los encabezados y pies de página del documento.

### `indiceConfig.tex`
Configuración del índice general (`\tableofcontents`), adaptado al formato del template.

### `packages.tex`
Archivo donde se incluyen todos los paquetes requeridos con `\usepackage{}`.  
Permite centralizar la gestión de dependencias.

---

## 🚀 Uso

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/marcosgatica2003/gaticonStandards.git

2. Copiar los archivos del repositorio a su directorio del proyecto.
3. **Escribir el documento:** se recomienda hacer su propio archivo donde irá escribiendo su informe, y en main.tex incluirlo antes del \end{document} usando \input{}

## 📌 Notas
Asegúrate de tener instalados todos los paquetes requeridos que se indican en packages.tex.

