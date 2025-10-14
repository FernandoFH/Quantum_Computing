## Certificación Profesional en Quantum Computing: Bases, Roadmap y Aplicaciones

### Perfil del participante

Ingenieros/as de diversas ramas, especialistas en Inteligencia Artificial, desarrolladores/as de software, responsables de desarrollos de nuevos negocios basados en tecnologías y todos/as aquellos que deseen conocer los alcances de esta nueva tecnología. 

### Objetivos

- Brindar los conocimientos suficientes para adentrarse en la tecnología de la Computación Cuántica y su potencial implicancia en la formación y/o trayectoria profesional del participante.
- Aportar los conceptos y principios fundamentales sobre cómo funciona una computadora cuántica y sus aplicaciones en la Industria y la Academia, como así también sus limitaciones
- Brindar herramientas para identificar problemas que pueden ser resueltos por la Computación Cuántica.
- Presentar el roadmap de la Computación Cuántica, su situación presente y futura.
- Aportar a la comprensión sobre cuáles son todos los requerimientos técnicos y de conocimiento necesarios para encarar diferentes proyectos de Computación Cuántica.

### Metodología

Durante la certificación se realizarán encuentros sincrónicos de desarrollo de contenido, presentación de materiales y se propondrán trabajos grupales. De forma asincrónica se compartirán materiales que los y las estudiantes deberán revisar y actividades que refuercen lo trabajado en los encuentros sincrónicos.

En las clases sincrónicas el docente realizará exposiciones de temas teóricos presentando los diferentes enfoques de la Computación Cuántica, y también se harán sesiones prácticas donde se presentará código en lenguaje Python para poder ser ejecutado tanto de manera local en las PCs de los alumnos, como en computadoras cuánticas reales.

### Conocimientos adquiridos al finalizar el programa

- Comprensión de los fundamentos que dan origen a la Computación Cuántica y sus aplicaciones en la industria y la academia.
- Capacidad para plantear casos de uso, gestionar proyectos de implementación y dimensionar su impacto en la industria y academia.
- Determinar cuándo la tecnología podrá resolver problemas reales y cuáles son sus limitantes.
- Capacidad para programar computadoras cuánticas reales y desarrollar programas que resuelvan problemas sencillos.

### Conocimientos mínimos para cursar el programa

Si bien el curso es para principiantes, se recomiendan conocimientos mínimos para adentrarse en el mundo de la Computación Cuántica en las áreas de:

- Matemática:
  - Probabilidad
  - Funciones Complejas
  - Cálculo Numérico 
  - Álgebra Lineal: operaciones con vectores y matrices

- Lenguajes de Programación
  - Conceptos básicos de lenguaje Python o similar

### Requisitos para aprobar el programa:

Asistencia igual o superior al 75%.

Aprobación de evaluación final. Se podrá elegir entre una de las dos opciones:

- Entrega de un trabajo teórico
- Entrega de un código en Python que resuelva un problema sencillo

### Plan de estudios

### Módulo 1. Conceptos fundamentales de la computación cuántica
- Qué es la computación cuántica
- Cuáles son los principios en los que se basa
- Cuál es el concepto de qubit
- Diferencias con la Computación Clásica
- Qué tipo de problemas resuelve

### Módulo 2. Aplicaciones en la industria
- Casos de Uso en las Industrias de:
  - Ciberseguridad
  - Salud y Genética
  - Finanzas
- Computación Cuántica para resolver problemas de Simulación y Optimización
- Por qué es necesario comenzar ya con el estudio y prototipado de las soluciones cuánticas

### Módulo 3. Introducción a las compuertas y circuitos cuánticos
- Qué son los circuitos cuánticos y cómo pueden generarse
- Qué son las compuertas cuánticas
- Qué herramientas disponemos para trabajar con circuitos cuánticos y sus diferentes aproximaciones

### Módulo 4. Introducción a los algoritmos cuánticos
- Introducción al Algoritmo de Deutsch
- Introducción al Algoritmo de Shor
- Introducción al Algoritmo de Grover
- Introducción al Algoritmo de Simon

### Módulo 5. Introducción a la ingeniería de software cuántico
- Principio de la programación para computadoras cuánticas
- Buenas prácticas
- Diferencias con la programación clásica
- Qué conocimientos se necesitan para desarrollar una aplicación o sistema cuántico
- Introducción al framework de programación cuántica: Qiskit

### Módulo 6. Trabajando con computadoras físicas reales
- Demostración de un programa realizado en Python que corra en máquinas cuánticas tanto en similares como de hardware real.
_______ 

### **Clase 1 – Introducción a la Computación Cuántica**: 

**El experimento de la doble rendija**

El experimento de la doble rendija demuestra la dualidad onda-partícula de la luz y la materia.
Cuando se hace pasar un haz de partículas (como fotones o electrones) por dos rendijas, se observa en la pantalla un patrón de interferencia, típico de las ondas.
Sin embargo, si se intenta observar por cuál rendija pasa cada partícula, el patrón desaparece, y las partículas se comportan como corpúsculos individuales.
Este experimento revela la naturaleza probabilística y no determinista del mundo cuántico.

**Interferencia cuántica**

La interferencia cuántica ocurre cuando las funciones de onda de distintas partículas (o del mismo sistema en diferentes caminos posibles) interfieren entre sí, combinando sus probabilidades.
Esto explica por qué un sistema cuántico puede mostrar efectos de cancelación o refuerzo en ciertas mediciones, dependiendo de cómo se superponen las amplitudes de probabilidad.

_👉 En términos prácticos, esta interferencia es la base del paralelismo cuántico que aprovechan los algoritmos cuánticos._

**Superposición cuántica**

Una partícula en superposición cuántica puede existir simultáneamente en varios estados posibles hasta que se realiza una medición.
Por ejemplo, un electrón puede estar en dos posiciones distintas, o un qubit puede representar “0” y “1” al mismo tiempo.
Al medirse, el sistema “colapsa” a un único estado.

Este principio no tiene un análogo en la física clásica, y es una de las bases que permite el poder de cómputo exponencial de las computadoras cuánticas.

**Entrelazamiento cuántico**

El entrelazamiento cuántico es un fenómeno donde dos o más partículas comparten un estado cuántico común, de modo que la medición de una afecta instantáneamente a las demás, sin importar la distancia que las separe.

Einstein lo llamó “acción fantasmal a distancia”.

Aunque la correlación es instantánea, no permite transmitir información más rápido que la luz, preservando los principios de la relatividad.

_💡 Este fenómeno es esencial para la teletransportación cuántica, la criptografía cuántica y los protocolos de corrección de errores cuánticos._

**Quantum Gates**

Las compuertas cuánticas son los bloques fundamentales de los circuitos cuánticos, análogas a las puertas lógicas clásicas, pero operan sobre qubits mediante transformaciones unitarias.

Estas operaciones modifican el estado cuántico (amplitud y fase) del sistema.

![Quantum gate](./images/QuantumGates.png)

	•	Hadamard (H): crea superposición.
	•	Pauli-X, Y, Z: rotaciones en los ejes del espacio de Bloch.
	•	CNOT: genera entrelazamiento entre dos qubits.
	•	T y S gates: aplican rotaciones de fase.

**Workflow para resolver un problema en una computadora cuántica**

**_1. Mapear el problema a circuitos cuánticos y operadores_.** Traducir el problema clásico a una representación cuántica: definir qubits, compuertas y, si corresponde, el Hamiltoniano que describe la evolución del sistema.

**_2. Optimizar el circuito para el hardware objetivo_.** Reducir la profundidad del circuito, Minimizar la sensibilidad al ruido, Adaptar la topología del circuito al conjunto de compuertas nativas del dispositivo.

**_3. Ejecutar en el hardware objetivo (o simulador)_.** Ejecutar el circuito cuántico optimizado en el backend elegido (dispositivo físico o simulador cuántico).

**_4. Posprocesar los resultados_.** Aplicar mitigación de errores y analizar los resultados de las mediciones para extraer el resultado clásico final.


### **Clase 2 - Modelado de Problemas y Qubits**: 

🎯 Introducción

El desafío más importante en la computación cuántica actual es modelar correctamente los problemas para que puedan resolverse mediante circuitos cuánticos y operadores.

_La computación cuántica no reemplaza a la computación clásica: existen problemas que no son comparables ni resolubles mediante algoritmos cuánticos.
Su objetivo es complementar los métodos clásicos y ofrecer ventajas en áreas específicas._

⸻

**Quantum Bits (Qubits)**

Un qubit es la unidad básica de información cuántica, análogo al bit clásico, pero con una diferencia fundamental:
mientras un bit solo puede tomar valores 0 o 1, un qubit puede estar en una superposición de ambos estados al mismo tiempo.

Matemáticamente, un qubit se representa como:

|\psi\rangle = \alpha|0\rangle + \beta|1\rangle

Donde:
	•	\alpha y \beta son números complejos que indican las amplitudes de probabilidad de que el qubit esté en el estado 0 o 1.
	•	La condición |\alpha|^2 + |\beta|^2 = 1 asegura que las probabilidades sumen 1.

Esta capacidad de superposición permite el procesamiento paralelo de información, clave para el poder de la computación cuántica.

**Esfera de Bloch**

La esfera de Bloch es una representación geométrica tridimensional del estado de un qubit.
Permite visualizar cómo se comporta y evoluciona en el tiempo.
	•	El polo norte representa el estado |0\rangle.
	•	El polo sur, el estado |1\rangle.
	•	Cualquier punto sobre la superficie de la esfera representa un estado intermedio (superposición).

Las compuertas cuánticas actúan como rotaciones en esta esfera, modificando el ángulo o la fase del qubit.
Por ejemplo:
	•	La puerta Hadamard (H) coloca al qubit en superposición perfecta.
	•	Las puertas Pauli-X, Y, Z lo rotan alrededor de los ejes correspondientes.

**Tipos de Qubits**

Los qubits pueden implementarse físicamente de diferentes formas, según la tecnología y los principios físicos empleados.
Los más comunes son:

	1.	Trampas de Iones
		•	Utilizan iones cargados suspendidos en un campo electromagnético.
		•	Los estados cuánticos se controlan con láseres de alta precisión.
		•	Ventaja: alta fidelidad y estabilidad.
			•	Ejemplo: sistemas de IonQ o Honeywell Quantum.
			
	2.	Qubits Superconductores
		•	Se basan en circuitos eléctricos superconductores enfriados a temperaturas cercanas al cero absoluto.
		•	Los estados 0 y 1 corresponden a diferentes niveles de corriente o energía.
		•	Ventaja: escalables y compatibles con tecnologías de microfabricación.
			•	Ejemplo: IBM Quantum, Google Sycamore, Rigetti.
			
	3.	Qubits Fotónicos
		•	Usan fotones individuales como portadores de información.
		•	Son resistentes al ruido y pueden transmitir información a largas distancias.
		•	Son esenciales para comunicaciones cuánticas y el internet cuántico.
		
	4.	Qubits de Spin o de Silicio
		•	Basados en el spin (momento angular intrínseco) de electrones confinados en semiconductores.
		•	Permiten integración con tecnologías CMOS (chips convencionales).

**Procesamiento de la Información**

| Tipo de Computación | Naturaleza de los Datos | Procesamiento |
|----------------------|--------------------------|---------------|
| **Clásica** | Distribución discreta (0 o 1) | Secuencial y lógico |
| **Cuántica** | Distribución continua de probabilidades | Paralelo y probabilístico |

En la computación cuántica, los datos se procesan de manera **no determinista** y se manipulan mediante **operadores unitarios** que preservan la probabilidad total.

**Conceptos Clave:**

**🧩 Modelado Cuántico**

El proceso de traducir un problema clásico en un modelo cuántico (circuitos, operadores y Hamiltonianos).
Cada modelo debe ajustarse al hardware cuántico y optimizar la profundidad y coherencia del circuito.

**Utilidad, Ventaja y Supremacía Cuántica**

| Concepto | Descripción |
|-----------|-------------|
| **Utilidad Cuántica** | Se logra cuando un sistema cuántico puede **modelar un problema real** de interés práctico (por ejemplo, simular una molécula con 100 qubits). |
| **Ventaja Cuántica** | Cuando un computador cuántico **resuelve un problema más rápido o más eficientemente** que el mejor computador clásico disponible. |
| **Supremacía Cuántica** | Situación donde un computador cuántico **realiza una tarea imposible de replicar clásicamente** en un tiempo razonable (demostrada por Google en 2019 con el chip *Sycamore*). |


**Casos de Uso**

| Área | Aplicación Cuántica |
|------|----------------------|
| **Finanzas** | Optimización de portafolios y gestión de riesgo. |
| **Química** | Descubrimiento de nuevos fármacos mediante simulación molecular. |
| **Materiales** | Diseño de materiales con propiedades específicas (superconductores, catalizadores, etc.). |
| **Comunicaciones y Seguridad** | Internet cuántico, criptografía cuántica y protocolos de comunicación seguros. |

**Repetidores Cuánticos**

Los repetidores cuánticos son dispositivos que permiten extender la distancia de transmisión de información cuántica, algo que no puede lograrse con repetidores clásicos debido al teorema de no clonación (no se puede copiar un estado cuántico).

Funcionan mediante entrelazamiento y teletransportación cuántica, recreando el estado original a lo largo de múltiples nodos intermedios.
Son fundamentales para construir una red cuántica global o Quantum Internet.

**🔒 Seguridad Post-Cuántica**

La seguridad post-cuántica busca desarrollar algoritmos criptográficos resistentes a ataques de computadores cuánticos.
Los métodos clásicos (RSA, ECC) serían vulnerables ante algoritmos como Shor, que puede factorizar números grandes eficientemente.

Una de las áreas más prometedoras usa criptografía basada en retículos (lattice-based cryptography), considerada “anti-cuántica” por su resistencia comprobada.

**Librería recomendada:**
👉 liboqs (Open Quantum Safe) —  https://openquantumsafe.org/

