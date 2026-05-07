# Práctica 5 – Transformación de Gramáticas y extensión del Simulador de Autómatas

## Descripción General

Esta práctica es una continuación directa de la Práctica 4, en la cual se desarrolló un simulador de autómatas finitos en esta fase se amplía el proyecto incorporando herramientas teóricas y visuales adicionales para mejorar el análisis de lenguajes formales.

El desarrollo se divide en dos partes principales: el uso de JFLAP para la transformación de gramáticas independientes del contexto y la extensión del software interactivo para incluir la visualización gráfica de autómatas.

--

## Relación con la Práctica 4

- Se reutiliza el simulador de autómatas (AFD, AFND y AFN-λ).
- Se mantienen funcionalidades como simulación, conversión y validación.
- Se amplía la interfaz con visualización gráfica.
- Se integra el uso de JFLAP como herramienta complementaria.

---

## Ejercicio 1: Transformación de Gramáticas en JFLAP

### Objetivo

Transformar una gramática independiente del contexto a:

- Forma Normal de Chomsky (FNC)
- Forma Normal de Greibach (FNG)

### Funcionalidades

- Ingreso de gramáticas en JFLAP.
- Transformación paso a paso.
- Validación mediante simulación.
- Exportación en formato `.jff`.

### Procedimiento

1. Definir la gramática en JFLAP.
2. Transformar a Forma Normal de Chomsky.
3. Transformar a Forma Normal de Greibach.
4. Validar ambas gramáticas.
5. Guardar los archivos generados.

--

## Ejercicio 2: Extensión del Software a visualización de Autómatas

Ampliar el simulador para permitir la visualización gráfica de autómatas.

### Funcionalidades agregadas

- Representación gráfica de estados y transiciones
- Visualización del recorrido del automata
- Resaltado de estados activos
- Soporte para AFD, AFND y AFN-λ
- Integración con archivos .jff

### Interfaz

- Estados iniciales y finales
- Transiciones diferenciadas incluyendo lambda
- Simulación visual de cadenas
- Interacción intuitiva con el usuario donde aparezcan tanto de lado izq como der

--
## Ejecución del Proyecto


Desde la carpeta del proyecto en el siguiente drive :https://drive.google.com/file/d/1MEhA-8zUQOs1fOfNHDppJ03Ba9-sNKAM/view?usp=sharing

`bash
cd afd_simulator_project
python src/main.py

Alumnos:
-Juarez Hipolito Marco Antonio
-Perez Flores Arale
-Roque Villegas Ivan 
