+++
title = 'JavaScript'
date = 2024-10-04T13:28:10+02:00
draft = false
+++


# 📚 Guía Completa de JavaScript

JavaScript es un lenguaje de programación versátil y ampliamente utilizado para el desarrollo web. Esta guía te ayudará a entender los conceptos básicos y avanzados de JavaScript.

## 📖 Introducción

JavaScript es un lenguaje de programación interpretado, orientado a objetos y basado en prototipos. Es uno de los tres lenguajes principales de la web, junto con HTML y CSS.

## 🛠️ Instalación

Para ejecutar JavaScript en tu máquina local, necesitas instalar Node.js. Puedes descargarlo desde [nodejs.org](https://nodejs.org/).

## ✨ Sintaxis Básica

### Variables

Puedes declarar variables usando `var`, `let` o `const`.

```javascript
var nombre = "Juan";
let edad = 30;
const PI = 3.14;
```


### Tipos de Datos

JavaScript tiene varios tipos de datos, incluyendo:

- **Números**: `let numero = 100;`
- **Cadenas**: `let texto = "Hola Mundo";`
- **Booleanos**: `let esVerdadero = true;`
- **Objetos**: `let persona = { nombre: "Juan", edad: 30 };`
- **Arreglos**: `let numeros = [1, 2, 3, 4, 5];`

### Operadores

JavaScript soporta varios operadores, como:

- **Aritméticos**: `+`, `-`, `*`, `/`
- **Asignación**: `=`, `+=`, `-=`
- **Comparación**: `==`, `===`, `!=`, `!==`
- **Lógicos**: `&&`, `||`, `!`

## 🔄 Estructuras de Control

### Condicionales

Puedes usar `if`, `else if` y `else` para ejecutar código condicionalmente.

```javascript
if (edad > 18) {
  console.log("Eres mayor de edad");
} else {
  console.log("Eres menor de edad");
}
```

### Bucles

JavaScript soporta varios tipos de bucles, como `for`, `while` y `do...while`.

```javascript
for (let i = 0; i < 5; i++) {
  console.log(i);
}
```

## 🧩 Funciones

Puedes definir funciones usando la palabra clave `function` o como funciones de flecha.

```javascript
function saludar(nombre) {
  return `Hola, ${nombre}`;
}

const despedir = (nombre) => `Adiós, ${nombre}`;
```

## 🏗️ Programación Orientada a Objetos

### Clases

Puedes definir clases usando la palabra clave `class`.

```javascript
class Persona {
  constructor(nombre, edad) {
    this.nombre = nombre;
    this.edad = edad;
  }

  saludar() {
    return `Hola, mi nombre es ${this.nombre}`;
  }
}

let juan = new Persona("Juan", 30);
console.log(juan.saludar());
```

## 🌐 Manipulación del DOM

JavaScript se usa comúnmente para manipular el Document Object Model (DOM) en páginas web.

### Selección de Elementos

Puedes seleccionar elementos usando métodos como `getElementById`, `getElementsByClassName` y `querySelector`.

```javascript
let elemento = document.getElementById("miElemento");
```

### Modificación de Elementos

Puedes modificar el contenido y los atributos de los elementos seleccionados.

```javascript
elemento.textContent = "Nuevo contenido";
elemento.style.color = "red";
```

## 📦 Módulos

JavaScript soporta módulos para organizar y reutilizar código.

### Exportar e Importar

Puedes exportar e importar funciones, objetos o variables entre archivos.

```javascript
// archivo1.js
export const saludo = "Hola Mundo";

// archivo2.js
import { saludo } from "./archivo1.js";
console.log(saludo);
```

## 🧪 Pruebas

### Jest

Jest es un framework de pruebas para JavaScript.

```javascript
// archivo.test.js
test("sumar 1 + 2 es igual a 3", () => {
  expect(1 + 2).toBe(3);
});
```

## 🚀 Conclusión

JavaScript es un lenguaje poderoso y flexible que puedes usar para crear aplicaciones web interactivas. Esta guía cubre los conceptos básicos y avanzados para ayudarte a empezar. ¡Sigue practicando y explorando más sobre JavaScript!
