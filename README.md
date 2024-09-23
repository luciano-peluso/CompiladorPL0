# Compilador en JAVA para PL0
Este es un compilador escrito en Java para el lenguaje de programación PL0. El proyecto implementa un compilador completo, que incluye las siguientes fases principales:

- Analizador Léxico: Se encarga de leer el código fuente y dividirlo en una serie de tokens.
- Analizador Sintáctico: Verifica que los tokens sigan las reglas gramaticales del lenguaje PL0.
- Analizador Semántico: Asegura que las declaraciones y expresiones tengan sentido lógico y contextual en el programa.
- Generador de Código: Genera código de máquina que puede ser ejecutado por una máquina virtual.
- Indicador error: Corta la compilación e indica el error correspondiente del código.

## Características
Implementación completa de un compilador para PL0.
Soporte para las construcciones básicas del lenguaje PL0: declaraciones de variables, procedimientos, y operaciones aritméticas y lógicas.
Verificación de errores léxicos, sintácticos y semánticos.
Generación de código de máquina.

## Estructura del Proyecto
El compilador está dividido en varias etapas, cada una con su propio módulo:

Analizador Léxico: Divide el código fuente en tokens (palabras clave, identificadores, operadores, etc.).
Analizador Sintáctico: Usa un árbol de análisis sintáctico para verificar que los tokens forman una estructura válida según la gramática de PL0.
Analizador Semántico: Asegura que los tipos de datos y las declaraciones de variables sean válidos en el contexto.
Generador de Código: Produce el código intermedio o máquina para la ejecución del programa.
