<div align="center">

# 🧩 Modelo de Calidad de Software basado en ISO/IEC 25010

### *Aplicado al Comercio Electrónico: Seguridad, Eficiencia, Fiabilidad, Usabilidad y Accesibilidad*

**Asignatura: Procesos en Ingeniería del Software · Actividad de Laboratorio: Diseño y Desarrollo de un Modelo de Calidad**

[![Asignatura](https://img.shields.io/badge/Asignatura-Procesos%20en%20Ingenier%C3%ADa%20del%20Software-0052CC.svg)]()
[![Actividad](https://img.shields.io/badge/Actividad-Modelo%20de%20Calidad-004488.svg)]()
[![Estándar](https://img.shields.io/badge/Est%C3%A1ndar-ISO%2FIEC%2025010-3776AB.svg)]()
[![Norma](https://img.shields.io/badge/Norma-ISO%2FIEC%2025000%20SQuaRE-150458.svg)]()
[![Accesibilidad](https://img.shields.io/badge/Accesibilidad-WCAG%202.1-orange.svg)]()
[![Licencia](https://img.shields.io/badge/Licencia-MIT-green.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Entregado-success.svg)]()

**[Contexto](#-contexto-y-alcance) • [Contenido](#-contenido-del-repositorio) • [Herramientas](#-herramientas-utilizadas) • [Estructura](#-estructura-del-documento) • [Factores de calidad](#-factores-de-calidad-evaluados) • [Autor](#-autor)**

<img src="https://img.shields.io/badge/Producto-Comercio%20Electr%C3%B3nico-blue?style=flat-square" alt="Producto"/>
<img src="https://img.shields.io/badge/Dominio-Falabella%20Colombia-green?style=flat-square" alt="Dominio"/>
<img src="https://img.shields.io/badge/Tipo-Documento%20de%20Modelo%20de%20Calidad-red?style=flat-square" alt="Tipo"/>
<img src="https://img.shields.io/badge/Medición-WAVE%20%2F%20WCAG%202.1-lightgrey?style=flat-square" alt="Medición"/>
<img src="https://img.shields.io/badge/Idioma-Español-yellow?style=flat-square" alt="Idioma"/>

</div>

---

## 📋 Tabla de Contenidos

- [🎯 Contexto y Alcance](#-contexto-y-alcance)
- [📁 Contenido del Repositorio](#-contenido-del-repositorio)
- [🧰 Herramientas Utilizadas](#-herramientas-utilizadas)
- [📐 Estructura del Documento](#-estructura-del-documento)
- [🔁 Flujo de Derivación del Modelo](#-flujo-de-derivación-del-modelo)
- [🏭 Factores de Calidad Evaluados](#-factores-de-calidad-evaluados)
- [♿ Medición de Accesibilidad](#-medición-de-accesibilidad)
- [📚 Técnicas y Estándares Aplicados](#-técnicas-y-estándares-aplicados)
- [📄 Cómo Consultar el Documento](#-cómo-consultar-el-documento)
- [✅ Contenido Verificable del Documento](#-contenido-verificable-del-documento)
- [📝 Nota](#-nota)
- [👥 Autor](#-autor)

---

## 🎯 Contexto y Alcance

Este repositorio contiene el trabajo desarrollado para la asignatura **Procesos en Ingeniería del Software**, correspondiente a la **Actividad de Laboratorio: Diseño y desarrollo de un modelo de calidad**.

El trabajo diseña un **modelo de calidad de software** fundamentado en la familia de normas **ISO/IEC 25000 (SQuaRE)** y en el modelo de calidad del producto **ISO/IEC 25010**, particularizado para el dominio del **comercio electrónico**. Incluye además la medición del factor de accesibilidad sobre un sitio real (**Falabella Colombia**) mediante evaluación automatizada con **WCAG 2.1**.

> **Estándar:** ISO/IEC 25010 (modelo de calidad del producto), sobre la base de ISO/IEC 25000 (SQuaRE).
> **Dominio:** comercio electrónico.
> **Alcance:** cinco factores de calidad — Seguridad, Eficiencia de desempeño, Fiabilidad, Usabilidad y Accesibilidad — con métricas ISO/IEC 25023 y medición real de accesibilidad.

### 🌟 ¿Qué aporta este documento?

- 🎯 **Modelo de calidad acotado** a cinco factores clave del comercio electrónico: Seguridad, Eficiencia de desempeño, Fiabilidad, Usabilidad y Accesibilidad.
- 🧾 **Desarrollo de subcaracterísticas y métricas** por factor, siguiendo ISO/IEC 25023.
- ♿ **Medición real de accesibilidad** con WCAG 2.1 sobre la página de inicio de Falabella Colombia.
- 📊 **Interpretación de resultados** y recomendaciones de mejora derivadas de la medición.

---

## 📁 Contenido del Repositorio

<table align="center">
  <tr><th>Elemento</th><th>Descripción</th></tr>
  <tr><td><code>Desarrollo_Proyecto_Alejandro_De_Mendoza_Tovar.pdf</code></td><td>📘 Documento final: análisis del dominio, marco ISO/IEC 25010, desarrollo de los cinco factores de calidad con sus métricas, y medición del factor de accesibilidad con su interpretación</td></tr>
  <tr><td><code>README.md</code></td><td>📄 Este documento</td></tr>
  <tr><td><code>LICENSE</code></td><td>⚖️ Licencia MIT</td></tr>
  <tr><td><code>.gitignore</code></td><td>🚫 Mantiene en local los documentos editables (<code>.docx</code>, <code>.doc</code>), la carpeta de la actividad y los archivos temporales de Office</td></tr>
</table>

> ℹ️ El repositorio versiona **únicamente el PDF final**. Los enunciados, las versiones editables en Word (`.docx`) y cualquier material de la actividad quedan excluidos vía `.gitignore` y permanecen solo en local.

---

## 🧰 Herramientas Utilizadas

<div align="center">

![ISO/IEC 25010](https://img.shields.io/badge/ISO%2FIEC%2025010-modelo%20de%20calidad-00629B?style=for-the-badge)
![ISO/IEC 25000](https://img.shields.io/badge/ISO%2FIEC%2025000-SQuaRE-150458?style=for-the-badge)
![WCAG 2.1](https://img.shields.io/badge/WCAG%202.1-accesibilidad-orange?style=for-the-badge)
![WAVE](https://img.shields.io/badge/WAVE-WebAIM-6f42c1?style=for-the-badge)
![Mermaid](https://img.shields.io/badge/Mermaid-diagramas-FF3670?style=for-the-badge&logo=mermaid&logoColor=white)

</div>

| Componente | Uso |
|:---|:---|
| **ISO/IEC 25000 (SQuaRE)** | Marco general de la familia de normas de calidad de software |
| **ISO/IEC 25010** | Modelo de calidad del producto y selección de factores |
| **ISO/IEC 25023** | Subcaracterísticas y métricas de medición por factor |
| **WCAG 2.1** | Pautas de accesibilidad (niveles A y AA) usadas como referencia |
| **WAVE (WebAIM)** | Herramienta empleada para la medición efectiva de accesibilidad |
| **TAW** | Herramienta de referencia; no completó el análisis (sitio tipo SPA) |
| **Mermaid** | Diagramas de estructura y de derivación de este README |

---

## 📐 Estructura del Documento

```mermaid
flowchart TD
    A[1. Introduccion] --> B[2. Marco teorico ISO-IEC 25000 y 25010]
    B --> C[3. Seleccion de factores de calidad]
    C --> C1[3.1 Seguridad]
    C --> C2[3.2 Eficiencia de desempeno]
    C --> C3[3.3 Fiabilidad]
    C --> C4[3.4 Usabilidad]
    C --> C5[3.5 Accesibilidad]
    C --> D[4. Metricas por factor - ISO-IEC 25023]
    D --> E[5. Medicion del factor de accesibilidad - WCAG 2.1]
    E --> F[6. Interpretacion y recomendaciones]
    F --> G[7. Conclusiones]
    G --> H[8. Bibliografia]
```

---

## 🔁 Flujo de Derivación del Modelo

```mermaid
flowchart LR
    A[Norma ISO-IEC 25000 - SQuaRE] --> B[ISO-IEC 25010 - Modelo de Calidad del Producto]
    B --> C[Seleccion de Factores de Calidad]
    C --> D[Seguridad]
    C --> E[Eficiencia de desempeno]
    C --> F[Fiabilidad]
    C --> U[Usabilidad]
    C --> G[Accesibilidad]
    D & E & F & U & G --> H[Subcaracteristicas y Metricas - ISO-IEC 25023]
    G --> I[Medicion WCAG 2.1 - WAVE sobre Falabella Colombia]
    I --> J[Interpretacion y Recomendaciones de Mejora]
```

---

## 🏭 Factores de Calidad Evaluados

| Factor | Descripción |
|:---|:---|
| **Seguridad** | Confidencialidad, integridad, no repudio, autenticidad y responsabilidad |
| **Eficiencia de desempeño** | Comportamiento temporal, utilización de recursos y capacidad |
| **Fiabilidad** | Madurez, disponibilidad, tolerancia a fallos y recuperabilidad |
| **Usabilidad** | Reconocibilidad de la adecuación, aprendizabilidad, operabilidad, protección contra errores de usuario y estética de la interfaz |
| **Accesibilidad** | Principios WCAG 2.1: perceptible, operable, comprensible y robusto |

---

## ♿ Medición de Accesibilidad

La evaluación del factor de accesibilidad se realizó sobre la página de inicio de **Falabella Colombia**, tomando como referencia las pautas **WCAG 2.1 (niveles A y AA)**:

- **WAVE (WebAIM)** → herramienta empleada para la medición efectiva (evalúa el DOM renderizado).
- **TAW** → herramienta de referencia; no completó el análisis por tratarse de una aplicación de página única (SPA).

---

## 📚 Técnicas y Estándares Aplicados

| Elemento | Aplicación |
|:---|:---|
| **ISO/IEC 25000 (SQuaRE)** | Marco general de la familia de normas de calidad |
| **ISO/IEC 25010** | Selección y definición de los cinco factores de calidad |
| **ISO/IEC 25023** | Subcaracterísticas y métricas asociadas a cada factor |
| **WCAG 2.1** | Referencia normativa para la evaluación de accesibilidad |
| **WAVE (WebAIM)** | Medición automatizada sobre el sitio real evaluado |
| **TAW** | Herramienta de contraste (sin resultado completo por ser SPA) |

---

## 📄 Cómo Consultar el Documento

1. Descargar o abrir `Desarrollo_Proyecto_Alejandro_De_Mendoza_Tovar.pdf` desde este repositorio.
2. Seguir la estructura descrita en [📐 Estructura del Documento](#-estructura-del-documento): de la introducción a la bibliografía.
3. Revisar el desarrollo de cada **factor de calidad** (sección 3) con sus subcaracterísticas y métricas.
4. Consultar la **medición de accesibilidad** (sección 5) y su **interpretación y recomendaciones** (sección 6).

---

## ✅ Contenido Verificable del Documento

<details>
<summary><b>🔎 Ver elementos que incluye el PDF</b></summary>

| Elemento | Sección | Incluido |
|:---|:---|:---:|
| Introducción | 1 | ✔ |
| Marco teórico ISO/IEC 25000 y 25010 | 2 | ✔ |
| Factor: Seguridad | 3.1 | ✔ |
| Factor: Eficiencia de desempeño | 3.2 | ✔ |
| Factor: Fiabilidad | 3.3 | ✔ |
| Factor: Usabilidad | 3.4 | ✔ |
| Factor: Accesibilidad | 3.5 | ✔ |
| Métricas por factor (ISO/IEC 25023) | 4 | ✔ |
| Medición WCAG 2.1 con WAVE (Falabella Colombia) | 5 | ✔ |
| Interpretación y recomendaciones de mejora | 6 | ✔ |
| Conclusiones | 7 | ✔ |
| Bibliografía | 8 | ✔ |

</details>

---

## 📝 Nota

Este documento corresponde a una **actividad académica**. La medición del factor de accesibilidad se realizó con herramientas automatizadas (WAVE) sobre el sitio real de Falabella Colombia con fines exclusivamente formativos, sin relación oficial con la empresa ni carácter de auditoría certificada.

---

## 👥 Autor

<div align="center">

Trabajo desarrollado en el marco de la asignatura **Procesos en Ingeniería del Software**.

| Autor | Perfil |
|:---:|:---:|
| **Alejandro De Mendoza** | [![GitHub](https://img.shields.io/badge/GitHub-AlejoTechEngineer-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AlejoTechEngineer) |

</div>

---

<div align="center">

### 🧩 *Un software de calidad no se declara, se mide*

**Procesos en Ingeniería del Software · Modelo de Calidad ISO/IEC 25010 aplicado al Comercio Electrónico**

</div>
