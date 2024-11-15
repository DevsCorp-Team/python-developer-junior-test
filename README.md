# Prueba Técnica - Python Developer Junior

## Objetivo de la prueba

Esta prueba técnica tiene como objetivo evaluar tus habilidades fundamentales de programación en Python. A través de una serie de ejercicios prácticos, se evaluará tu comprensión de conceptos esenciales como el uso de estructuras de datos, control de flujo, manejo de entradas del usuario y depuración de código. Se espera que resuelvas los ejercicios de manera eficiente y con un código claro y bien estructurado.

## Instrucciones generales

1. **Duración de la Pueba:** 4 horas.
2. **Entrega de la prueba:** Debes entregar tu solución a través de un repositorio de GitHub que habrás clonado previamente (más detalles al final).
3. **Evaluación:** Se evaluará la correctitud de las soluciones, la calidad del código y la capacidad para resolver problemas de manera eficiente.
4. **Personas de apoyo:** Durante la prueba, tendrás acceso a una persona de apoyo para aclarar cualquier duda técnica o de interpretación de los ejercicios. No dudes en consultar si algo no está claro.
5. **Recomendaciones:**
    - Realiza un análisis previo de los ejercicios antes de empezar a codificar.
    - No te preocupes por optimizaciones excesivas, enfócate en resolver los ejercicios de manera correcta y clara.
    - Si no puedes completar todos los ejercicios, entrega lo que hayas hecho. Es preferible entregar una solución parcial pero correcta que intentar hacer todo de manera apresurada.

## Instrucciones para hacer el Fork y entregar la prueba técnica

Para entregar tu solución, sigue estos pasos:

## Pasos para hacer el fork y entregar tu solución:

1. **Haz un fork de este repositorio:**
    - Visita el siguiente repositorio: [Enlace al repositorio de la prueba técnica](https://github.com/DevsCorp-Team/python-developer-junior-test.git).
    - Haz clic en el botón `Fork` en la esquina superior derecha de la página.
    - Esto creará una copia del repositorio en tu cuenta de GitHub.

2. **Clona el repositorio a tu máquina local:**
    - Después de hacer el fork, clona el repositorio a tu máquina local usando el siguiente comando en tu terminal:
        ```bash
        git clone https://github.com/tu-usuario-github/python-developer-junior-test.git
        ```
    - Esto descargará el repositorio a tu computadora para que puedas trabajar en los ejercicios.

3. **Realiza tus modificaciones:**
    - Abre el archivo `README.md` y revisa los ejercicios.
    - Crea un archivo Python para cada ejercicio en una carpeta llamada `ejercicios`. Por ejemplo:
        - `ejercicios/ejercicio_1.py` para el primer ejercicio.
        - `ejercicios/ejercicio_2.py` para el segundo.
        - `ejercicios/ejercicio_3.py` para el tercero.
    - Implementa las soluciones según las instrucciones dadas.
    - Asegúrate de que tu código esté bien organizado y tenga comentarios claros si es necesario.

4. **Haz commits de tus cambios:**
    - Después de completar cada ejercicio, guarda los cambios en tu repositorio local.
    - Haz un commit con el siguiente comando:
        ```bash
        git add .
        git commit -m "Solución del ejercicio 1"
        ```
    - Haz lo mismo para cada ejercicio.

5. **Sube tus cambios a GitHub:**
    - Después de hacer los commits, sube tus cambios al repositorio de GitHub con:
        ```bash
        git push origin main
        ```

6. **Entrega tu solución:**
    - Una vez que hayas subido todas tus soluciones a tu repositorio de GitHub, envía el enlace a tu repositorio como tu entrega final.
    - **No hagas un Pull Request**, ya que tu solución debe estar en tu repositorio personal.

# Estructura del Repositorio

Tu repositorio debe estar organizado de la siguiente manera para asegurar que tu trabajo sea fácil de entender y revisar:

```r
python-developer-junior-test/         <- Raíz del repositorio
│
├── README.md                         <- Este archivo con las instrucciones
│
├── ejercicios/                       <- Carpeta con los ejercicios resueltos
│   ├── ejercicio_1.py                <- Solución al ejercicio 1
│   ├── ejercicio_2.py                <- Solución al ejercicio 2
│   └── ejercicio_3.py                <- Solución al ejercicio 3
│
└── .gitignore                        <- (Opcional) Si necesitas excluir archivos
```

## Explicación de la estructura:
- `README.md`: Este archivo debe incluir las instrucciones completas de la prueba, tal como las ves aquí. Es recomendable no modificar este archivo, ya que contiene los detalles sobre cómo debe entregarse la prueba.
- `ejercicios/`: Debe ser una carpeta que contenga tus soluciones a los tres ejercicios en formato `.py`. Cada ejercicio debe estar en un archivo separado dentro de esta carpeta:
    - `ejercicio_1.py`: Aquí debe ir la solución al primer ejercicio (contar las vocales).
    - `ejercicio_2.py`: Aquí debe ir la solución al segundo ejercicio (fix the code).
    - `ejercicio_3.py`: Aquí debe ir la solución al tercer ejercicio (pirámide de asteriscos).
- `README.md`: Asegúrate de que las instrucciones estén correctamente documentadas aquí. Si decides agregar alguna sección adicional (como una explicación de tus decisiones de diseño o notas adicionales), puedes hacerlo en este archivo.

Si deseas agregar algún archivo adicional, como dependencias o configuraciones, puedes incluirlos en el directorio raíz, pero los archivos de código deben estar dentro de la carpeta `ejercicios/`.

# Ejercicios

## Ejercicio 1: Contar las vocales (10 puntos)

**Enunciado:** Escribe una función en Python que reciba un **string** como entrada y devuelva el número de vocales que contiene. Considera tanto las vocales en minúsculas como en mayúsculas.

**Ejemplo de entrada:**
```python
"Hola Mundo"
```

**Salida esperada:**
```python
4
```

**Requisitos adicionales:**
- La función debe ser insensible a mayúsculas y minúsculas.
- El código debe ser eficiente y fácil de entender.
- No se permite el uso de bibliotecas externas, solo funciones y estructuras estándar de Python.

**Criterios de evaluación:**
- **Correctitud:** ¿La función devuelve el número correcto de vocales?
- **Eficiencia:** ¿La solución es simple y no innecesariamente compleja?
- **Claridad:** ¿El código es claro y bien estructurado?

## Ejercicio 2: Fix the Code - Corrección de errores en código existente (15 puntos)

**Enunciado:** A continuación, tienes un fragmento de código que contiene varios errores. Algunos son de sintaxis y otros de lógica. Tu tarea es depurar y corregir el código para que funcione correctamente.

```python
def imprimir_pares(n):
    for i in range(1, n):
        if i % 2 = 0:
            print(i)
            
n = int(input("Ingresa un número: "))
imprimir_pares(n)
```

**Criterios de evaluación:**
- Identificación y corrección de errores de sintaxis.
- Capacidad para identificar errores lógicos en el código.
- Claridad y legibilidad del código corregido.

## Ejercicio 3: Pirámide de Asteriscos (20 puntos)

**Enunciado:** Escribe un programa que reciba un número entero `n` (mínimo 2) y luego imprima una pirámide de asteriscos. La pirámide debe tener `n` filas, y cada fila debe contener un número impar de asteriscos, comenzando con 1 en la primera fila y aumentando en 2 por cada fila sucesiva. La pirámide debe estar **centrada** en la consola.

**Ejemplo de la entrada:**
```python
n = 3
```

**Salida esperada:**
```python
  *
 ***
*****
```

**Requisitos adicionales:**
- El número de asteriscos por fila debe seguir la fórmula `2 * i - 1`, donde `i` es el número de la fila (empezando desde 1).
- Los espacios a la izquierda de los asteriscos deben ser calculados para centrar la pirámide. Es decir, el número de espacios antes de los asteriscos debe ser `n - i`.

**Criterios de evaluación:**
- Uso adecuado de bucles y estructuras de control.
- Correcto cálculo de los espacios y asteriscos en cada fila.
- Capacidad para formatear la salida de manera correcta (centrada).
- Claridad y legibilidad del código.

# Evaluación y Criterios

Cada ejercicio tiene un valor específico y será evaluado según los siguientes criterios:

## Correctitud (50%)
- La solución debe ser correcta y producir los resultados esperados.
- Se valorará la capacidad para resolver problemas con precisión y en el menor tiempo posible.

## Claridad y Buenas Prácticas (30%)
- El código debe ser legible, con nombres de variables y funciones descriptivos.
- Se valorará el uso de buenas prácticas de programación, como el uso de funciones y comentarios claros.

## Eficiencia (10%)
- La solución debe ser eficiente en cuanto a tiempo y espacio, aunque no se espera que el candidato realice optimizaciones avanzadas.

## Manejo de Errores (10%)
- En los ejercicios que lo requieran, se evaluará la capacidad de manejar excepciones y entradas inesperadas de manera robusta.

# Personas de Apoyo

Durante la prueba, tendrás acceso a una persona de apoyo para resolver dudas o aclaraciones relacionadas con los ejercicios. Si en cualquier momento tienes preguntas sobre lo que se espera en los ejercicios, no dudes en preguntar a la persona de apoyo.

Sin embargo, ten en cuenta que la persona de apoyo no proporcionará respuestas directas a los ejercicios, sino que solo te ayudará a interpretar correctamente las instrucciones o a aclarar conceptos si es necesario.
