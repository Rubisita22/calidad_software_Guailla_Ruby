# 🧪 Calidad del Software

> Repositorio académico de la materia **Calidad del Software**

Este repositorio contiene ejercicios, prácticas, investigaciones y proyectos desarrollados durante la materia, enfocados en mejorar la **calidad, confiabilidad y mantenimiento del software**.

---

## 👨‍💻 Autor

*Nombre:* Rubyy

## 📚 Contenido

Durante la materia estudiaremos diferentes conceptos y técnicas relacionadas con la calidad del software:

* 🧪 Testing
* 🔬 Tests unitarios
* 🌐 Pruebas E2E
* 🐛 Gestión de errores
* 📊 Cobertura de código
* 🔄 Integración continua
* 📝 Buenas prácticas
* 🔍 Calidad y mantenimiento del código

---

## 🧪 Testing

El **testing** es el proceso de evaluar un software para comprobar que funciona correctamente y cumple con los requisitos establecidos.

Su objetivo principal es **detectar errores antes de que lleguen al usuario final**.

```text
Código → Pruebas → Detección de errores → Corrección → Software de calidad
```

---

## 🔬 Tests Unitarios

Los **tests unitarios (Unit Tests)** comprueban pequeñas partes independientes de una aplicación, como una función, método o componente.

Permiten verificar que cada unidad del código funciona correctamente de manera aislada.

### Ejemplo

```typescript
function sumar(a: number, b: number): number {
    return a + b;
}
```

Test:

```typescript
describe('sumar', () => {
    it('debería sumar dos números', () => {
        expect(sumar(2, 3)).toBe(5);
    });
});
```

### 🎯 Objetivo

* Detectar errores rápidamente.
* Comprobar funciones individuales.
* Facilitar el mantenimiento.
* Evitar que cambios nuevos dañen funcionalidades existentes.

---

## 🌐 Pruebas E2E

Las **pruebas End-to-End (E2E)** comprueban el funcionamiento de una aplicación desde el punto de vista del usuario.

Simulan acciones reales dentro de la aplicación, por ejemplo:

```text
Abrir aplicación
      ↓
Iniciar sesión
      ↓
Ingresar usuario y contraseña
      ↓
Presionar "Iniciar sesión"
      ↓
Verificar que se muestre el Dashboard
```

Las pruebas E2E permiten comprobar que **diferentes partes del sistema funcionan correctamente en conjunto**.

### Herramientas comunes

* Playwright
* Cypress
* Selenium

---

## 🔬 Tests Unitarios vs 🌐 E2E

| Característica        | Tests Unitarios     | Pruebas E2E                |
| --------------------- | ------------------- | -------------------------- |
| Alcance               | Una unidad          | Aplicación completa        |
| Velocidad             | ⚡ Rápidos           | 🐢 Más lentos              |
| Objetivo              | Verificar funciones | Verificar flujos completos |
| Simulación de usuario | ❌ No necesariamente | ✅ Sí                       |
| Ejemplo               | Probar una función  | Probar un inicio de sesión |
| Aislamiento           | Alto                | Bajo                       |

---

## 📊 Cobertura de Código

La **cobertura de código** indica qué porcentaje del código es ejecutado durante las pruebas.

Por ejemplo:

```text
Statements   90%
Branches     85%
Functions    95%
Lines        92%
```

Una cobertura alta puede ayudar a detectar código que no ha sido probado, aunque **tener 100% de cobertura no garantiza que el software esté libre de errores**.

---

## 🐛 Errores y Bugs

Un **bug** es un comportamiento incorrecto o inesperado del software.

El proceso básico para solucionarlo puede ser:

```text
Detectar
   ↓
Reproducir
   ↓
Analizar
   ↓
Corregir
   ↓
Probar nuevamente
```

---

## 🔄 Integración Continua

La **Integración Continua (CI)** consiste en integrar cambios de código frecuentemente y ejecutar automáticamente procesos como:

* Instalación de dependencias
* Tests unitarios
* Tests E2E
* Análisis de código
* Construcción del proyecto

Esto permite detectar problemas rápidamente.

---

## 📝 Buenas Prácticas

Algunas buenas prácticas para mejorar la calidad del software son:

* Escribir código claro y organizado.
* Utilizar nombres descriptivos.
* Evitar código duplicado.
* Crear pruebas automatizadas.
* Revisar los errores encontrados.
* Mantener una buena estructura del proyecto.
* Documentar funcionalidades importantes.
* Realizar revisiones de código.

---

## 🛠️ Herramientas

Durante la materia se pueden utilizar herramientas como:

| Herramienta    | Uso                        |
| -------------- | -------------------------- |
| Jest           | Tests unitarios            |
| Playwright     | Pruebas E2E                |
| Cypress        | Pruebas E2E                |
| ESLint         | Análisis de código         |
| Git            | Control de versiones       |
| GitHub         | Repositorio y colaboración |
| GitHub Actions | Integración continua       |

---

## 📁 Estructura del repositorio

```text
Calidad-del-Software/
│
├── unit-tests/
│   ├── ejercicios/
│   └── proyectos/
│
├── e2e/
│   ├── ejercicios/
│   └── proyectos/
│
├── cobertura/
│
├── investigaciones/
│
├── practicas/
│
└── README.md
```

---

## 🎯 Objetivo de la materia

El objetivo es aprender a **evaluar, probar y mejorar la calidad de las aplicaciones de software**, utilizando buenas prácticas y herramientas de testing que permitan desarrollar sistemas más **confiables, mantenibles y seguros**.

---

## 🚀 Tecnologías y herramientas

```text
Jest
Playwright
Cypress
Git
GitHub
GitHub Actions
```

---

## 👨‍💻 Autor

**Estudiante de Calidad del Software**

Repositorio académico para prácticas, ejercicios e investigaciones de la materia.
