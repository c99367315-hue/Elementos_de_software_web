1. Consulte y explique que significa a nivel de uso del internet: 
a. Servidor DNS 
b. IP 
c. Protocolo 
d. Nombre de dominio 
e. Directorio y nombre de archivo 

R//: 

a. Servidor DNS  
Un Servidor DNS (Domain Name System) es como una agenda telefónica de internet.  
Cuando escribes una página web (por ejemplo, google.com), el DNS traduce ese nombre a una dirección IP que las computadoras entienden.  
Sin el DNS, tendrías que memorizar números en lugar de nombres.

b. IP (Dirección IP)  
La IP (Internet Protocol) es un número único que identifica a cada dispositivo conectado a internet.  
Ejemplo: 192.168.1.1  
Es como la dirección de tu casa, pero para tu computadora o celular en la red.

c. Protocolo  
Un protocolo es un conjunto de reglas que permiten que los dispositivos se comuniquen entre sí en internet.  
Ejemplos comunes:  
- HTTP (para páginas web)  
- HTTPS (versión segura)  
Es como el idioma que usan las computadoras para entenderse.

d. Nombre de dominio  
El nombre de dominio es el nombre fácil de recordar de un sitio web.  
Ejemplo: www.google.com  
Es lo que escribes en el navegador para acceder a una página, en lugar de usar la IP.

e. Directorio y nombre de archivo  
Se refiere a la ubicación específica de un recurso dentro de un sitio web.  
Ejemplo: www.ejemplo.com/carpeta/archivo.html  
Directorio (carpeta): /carpeta/  
Nombre de archivo: archivo.html  
Es como la ruta dentro de una computadora donde se guarda un archivo.

2. Mencionamos dos roles importantes en el desarrollo de un producto web, pero hay 
otros roles involucrados, consulte y defina qué hace cada uno de los siguientes 
roles: 
a. Diseñador UI/UX 
b. Cloud Manager / Ingeniero de infraestructura en la nube 
c. Administrador de base de datos 
d. Project Manager / Director del Proyecto 

R//: 

a. Diseñador UI/UX
El Diseñador UI/UX combina dos enfoques. UX (User Experience) se encarga de la experiencia del usuario, investiga cómo interactúan las personas con el producto, define flujos de navegación, estructura la información y busca que el sistema sea fácil, útil e intuitivo. UI (User Interface) se enfoca en la parte visual, diseñando colores, tipografías, botones, iconos y la apariencia general de la aplicación. En resumen, hace que el producto sea fácil de usar y visualmente atractivo.

b. Cloud Manager / Ingeniero de infraestructura en la nube
Este profesional se encarga de la infraestructura en la nube utilizando plataformas como Amazon Web Services, Microsoft Azure o Google Cloud Platform. Sus funciones incluyen configurar servidores y servicios, garantizar disponibilidad y escalabilidad, gestionar la seguridad y copias de respaldo, optimizar costos y rendimiento, y automatizar despliegues. En resumen, asegura que la aplicación funcione correctamente en internet de forma segura y eficiente.

c. Administrador de base de datos
El administrador de base de datos o DBA gestiona las bases de datos del sistema. Se encarga de diseñar su estructura, garantizar la integridad y consistencia de los datos, realizar copias de seguridad, optimizar consultas para mejorar el rendimiento y gestionar accesos y seguridad. En resumen, protege y organiza los datos para que estén seguros, disponibles y bien estructurados.

d. Project Manager / Director del Proyecto
Es la persona encargada de coordinar todo el proyecto. Sus funciones incluyen planificar tareas, tiempos y recursos, coordinar al equipo de trabajo, controlar el presupuesto y el alcance, comunicar avances a clientes o interesados, e identificar y gestionar riesgos. En resumen, se asegura de que el proyecto se complete a tiempo, dentro del presupuesto y cumpliendo los objetivos.

3. ¿Qué significa que un lenguaje sea turing completo? 

R//:## ¿Qué significa que un lenguaje sea Turing completo?

Un lenguaje es **Turing completo** cuando tiene la capacidad de expresar cualquier cálculo que una máquina de Turing pueda realizar, siempre que disponga de suficiente tiempo y memoria.

### 🧠 Idea clave
El concepto proviene de la máquina de Turing, un modelo teórico propuesto por Alan Turing que define qué significa "computar" algo.

### ✅ Para que un lenguaje sea Turing completo debe poder:
- Realizar operaciones básicas (sumar, restar, comparar, etc.)
- Tener control de flujo (condicionales como `if`, y bucles como `while` o `for`)
- Manipular memoria (guardar y modificar datos)

### 📌 Ejemplos
Lenguajes como:
- Python  
- Java  
- C  

son Turing completos porque pueden implementar cualquier algoritmo.

### ⚠️ Importante
Ser Turing completo no significa que el lenguaje sea eficiente o práctico, sino que es lo suficientemente poderoso en teoría para resolver cualquier problema computable.

4. ¿Por qué CSS y HTML no son lenguajes de programación? 

R//: 

## ¿Por qué CSS y HTML no son lenguajes de programación?

HTML y CSS no se consideran lenguajes de programación porque no cumplen con las características fundamentales que definen a un lenguaje de programación.

### 1. No tienen lógica ni control de flujo

Los lenguajes de programación permiten tomar decisiones usando estructuras como `if`, `else` y bucles (`for`, `while`).

* HTML y CSS no pueden hacer esto.
* No pueden ejecutar acciones basadas en condiciones.

### 2. No pueden realizar cálculos complejos

Un lenguaje de programación permite trabajar con variables, operaciones matemáticas y algoritmos.

* HTML solo estructura contenido.
* CSS solo define estilos (colores, tamaños, posiciones).
* No es posible implementar algoritmos complejos con ellos.

### 3. No son lenguajes ejecutables

Los lenguajes de programación se ejecutan (compilados o interpretados) para producir un resultado.

* HTML es un lenguaje de marcado (estructura).
* CSS es un lenguaje de estilos (presentación).
* Ambos son interpretados por el navegador, pero no ejecutan programas.

### 4. Su propósito es diferente

* HTML (HyperText Markup Language) → define la estructura de una página web.
* CSS (Cascading Style Sheets) → define cómo se ve esa página.

En cambio, lenguajes de programación como JavaScript permiten:

* Manipular el contenido dinámicamente
* Responder a eventos
* Ejecutar lógica

### Resumen

* HTML → estructura
* CSS → diseño
* Lenguajes de programación → lógica y comportamiento


5. Defina con sus palabras qué es una etiqueta en HTML

R//: 

## ¿Qué es una etiqueta en HTML?

Una **etiqueta en HTML** es una palabra o conjunto de palabras encerradas entre signos de menor y mayor (`< >`) que se utiliza para **definir y estructurar el contenido de una página web**.

En otras palabras, las etiquetas le dicen al navegador qué tipo de contenido está mostrando y cómo debe interpretarlo o mostrarse.

### Ejemplos de etiquetas:
- `<p>` → indica un párrafo  
- `<h1>` → indica un título principal  
- `<img>` → indica una imagen  

### Estructura básica:
Las etiquetas generalmente funcionan en pares:

- Etiqueta de apertura: `<p>`
- Etiqueta de cierre: `</p>`

Entre ellas se coloca el contenido:

```html
<p>Este es un párrafo</p>