# Resumen de Comandos Básicos en Bash 🖥️

Este repositorio es un pequeño resumen con comandos básicos de Bash para la materia **Cso Módulo 1**. Vas a encontrar ejemplos simples para trabajar con archivos, arrays y estructuras de control en scripts.

## ¿Qué hay en este repo? 🤔

- **teoria_modulo_1.pdf**: Documento que contiene la teoría fundamental
- **acceso_rapido_bash.txt**: Apunte para estudiar o releer a la hora de hacer un ejercicio.
- **bash_scripting_summary.txt**: Un resumen rápido de comandos para manejar archivos y hacer otras cosas con Bash.
- **comandos_bash.txt**: Más ejemplos de comandos útiles para trabajar en Bash.

## ¿Para qué sirve todo esto? 🚀

Si estás empezando con Bash, estos archivos te pueden ayudar a entender y practicar con los comandos más básicos. Aquí algunos ejemplos:

### Ejemplos rápidos de uso:

1. **¿Cómo manejar archivos?**
   - Sacar la primera columna de un archivo:
     ```bash
     cut -d' ' -f1 archivo.txt
     ```

   - Contar las líneas de un archivo:
     ```bash
     wc -l archivo.txt
     ```

   - Buscar una palabra en un archivo:
     ```bash
     grep "palabra" archivo.txt
     ```

2. **Manejo de arrays en Bash:**
   - Crear un array:
     ```bash
     array=(elemento1 elemento2)
     ```

   - Acceder al primer elemento del array:
     ```bash
     echo ${array[0]}
     ```

3. **Estructuras de control (los típicos condicionales y loops):**
   - Usar un `for` loop para hacer algo con cada archivo `.txt`:
     ```bash
     for archivo in *.txt; do
         echo "Procesando $archivo"
     done
     ```

## ¿Qué más puedo hacer? 🎓

Puedes usar este resumen para practicar en la terminal, probar los comandos y empezar a crear tus propios scripts en Bash. ¡Es ideal para resolver ejercicios de clase o para tenerlo a mano durante los exámenes! 😄

## Contribuciones ✨

Si se te ocurre algo para mejorar o agregar, podés hacer un **pull request** o mandarme un mensaje con sugerencias.

---

¡Espero que te sea útil! ¡Suerte con la materia! 🚀
