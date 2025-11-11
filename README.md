Perfecto 👍
Aquí tienes una **versión formal y académica** del README para tu materia de **Criptografía**.
Está pensada para que puedas subirla directamente a GitHub o incluirla en un informe del curso.
Usa un tono claro, estructurado y profesional, sin emojis ni decoraciones innecesarias.

---

# Proyecto de Criptografía – Implementación de Algoritmos Clásicos de Cifrado

## 1. Descripción general

El presente repositorio contiene la implementación y análisis de diversos **algoritmos clásicos de cifrado**, desarrollados como parte de la asignatura **Criptografía**.
El objetivo principal es comprender el funcionamiento de los métodos tradicionales de encriptación simétrica y su relevancia histórica en el desarrollo de los sistemas modernos de seguridad de la información.

Cada algoritmo fue implementado en el lenguaje **Python**, priorizando la claridad en la lógica de cifrado y descifrado, así como la facilidad para realizar pruebas con diferentes entradas y claves.

---

## 2. Algoritmos implementados

### 2.1 Cifrado César

El cifrado César consiste en desplazar cada letra del texto original un número fijo de posiciones dentro del alfabeto.
Es un algoritmo de sustitución monoalfabética que, aunque sencillo, ilustra los fundamentos de la criptografía por sustitución.

### 2.2 Cifrado Vigenère

El cifrado Vigenère es un método polialfabético que utiliza una palabra clave para determinar los desplazamientos aplicados a cada letra del texto.
Su principal aportación es la mejora en la resistencia frente a ataques de análisis de frecuencia.

### 2.3 Cifrado Hill

El cifrado Hill emplea operaciones algebraicas con **matrices modulares** para cifrar bloques de texto.
Este método permite un cifrado poligráfico, donde cada bloque de letras se representa como un vector y se multiplica por una matriz clave invertible módulo 26.

### 2.4 Cifrado Playfair

El cifrado Playfair utiliza una **matriz de 5x5** generada a partir de una palabra clave para cifrar pares de letras.
Se trata de un cifrado por sustitución digráfica que incrementa la complejidad frente a los cifrados monoalfabéticos.

### 2.5 Cifrado Vernam (One-Time Pad)

El cifrado Vernam o **One-Time Pad** utiliza una clave aleatoria del mismo tamaño que el mensaje.
Cada carácter del texto plano se combina con su correspondiente carácter de la clave mediante una operación XOR, lo que lo convierte en un sistema teóricamente irrompible si se cumplen las condiciones de aleatoriedad y uso único de la clave.

### 2.6 Máquina Enigma

Además de los algoritmos anteriores, se incluye un **reporte explicativo** sobre la **Máquina Enigma**, dispositivo mecánico de cifrado utilizado por Alemania durante la Segunda Guerra Mundial.
El análisis detalla su funcionamiento, la estructura de sus rotores y el impacto histórico de su descifrado por parte de los aliados.

---

## 3. Estructura del repositorio

```
📂 Criptografia/
├── cesar/
│   └── cesar.py
├── vigenere/
│   └── vigenere.py
├── hill/
│   └── hill.py
├── playfair/
│   └── playfair.py
├── vernam/
│   └── vernam.py
└── reportes/
    └── Maquina_Enigma.pdf
```

Cada subcarpeta contiene el código fuente correspondiente a un algoritmo, junto con comentarios descriptivos y ejemplos de uso.

---

## 4. Requisitos y entorno de ejecución

* **Lenguaje:** Python 3.x
* **Librerías necesarias:**

  * `numpy` (para operaciones matriciales en el cifrado Hill)
  * `string`
  * `random`

Instalación de dependencias:

```bash
pip install numpy
```

Ejecución de un ejemplo:

```bash
python hill/hill.py
```

---

## 5. Objetivos de aprendizaje

* Comprender los principios fundamentales de los cifrados clásicos.
* Aplicar conocimientos de matemáticas (álgebra lineal y modular) en el ámbito criptográfico.
* Identificar las debilidades de los sistemas de cifrado histórico.
* Reconocer la evolución de los métodos de encriptación hasta los modelos modernos.

---

## 6. Conclusiones

La implementación de estos algoritmos permitió analizar los fundamentos matemáticos y lógicos de la criptografía clásica.
A través de los ejercicios realizados, se evidenció la importancia de la clave en la seguridad del mensaje, así como la vulnerabilidad de los métodos de sustitución simples ante el análisis de frecuencia.
Finalmente, el estudio de la Máquina Enigma ofreció una perspectiva histórica relevante sobre cómo la criptografía ha influido en eventos de gran impacto mundial y en el desarrollo de la seguridad informática actual.

---

## 7. Créditos

**Materia:** Criptografía
**Profesor:** [Nombre del profesor]
**Institución:** [Nombre de la universidad o instituto]
**Fecha:** Noviembre 2025

**Integrantes del equipo:**

* [Nombre completo 1]
* [Nombre completo 2]
* [Nombre completo 3]

---

¿Quieres que te prepare una **versión en formato Markdown (.md)** lista para copiar y pegar en GitHub (con títulos, negritas y formato correcto)?
Puedo generarla directamente con todo el formato de GitHub para que se vea profesional.

