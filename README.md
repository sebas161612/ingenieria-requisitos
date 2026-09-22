# Ingeniería de Requisitos

Repositorio correspondiente al trabajo desarrollado durante el curso de **Ingeniería de Requisitos**.

En este repositorio se encuentran organizados los diferentes artefactos elaborados durante el desarrollo de los casos de estudio, aplicando prácticas de gestión, documentación, versionado y trazabilidad de requisitos.

## Estructura del repositorio

El repositorio se encuentra organizado por casos de estudio y, dentro de cada caso, por los diferentes tipos de artefactos desarrollados.

```text
/
├── Caso-1-Empresa-Operaciones-Aereas/
│   ├── Product-Vision-Board/
│   ├── Product-Backlog/
│   ├── Request-for-Change/
│   └── Matriz-Trazabilidad/
│
├── Caso-2-Simulador-Vehiculo/
│   ├── Modelos-Estructurales/
│   ├── Modelos-Comportamiento/
│   ├── SRS/
│   └── Test-Case/
│
├── Caso-3-Dietas-Al-Dia/
│   ├── Prototipo-Funcional/
│   └── Repositorio-Codigo/
│
└── Caso-4-Empresa-Mudanza/
    └── Modelos/
```

Cada artefacto cuenta con su propia carpeta, donde se encuentra el archivo correspondiente, un `README.md` con información sobre su ubicación y un `metadata.md` con información como el identificador, versión, estado, autor o revisor, fecha de cierre y artefactos relacionados.

Cuando un artefacto cuenta con versiones anteriores, estas se conservan dentro de una carpeta `Versiones`, permitiendo mantener evidencia de la evolución del artefacto.

## Navegación del repositorio

Para consultar un artefacto, se debe ingresar al caso correspondiente y posteriormente a la carpeta del tipo de artefacto. Cada carpeta de artefacto contiene un README que indica su ubicación y un archivo de metadatos con la información asociada.

Los artefactos relacionados también se encuentran identificados mediante sus respectivos IDs, permitiendo realizar seguimiento y facilitar la trazabilidad entre ellos.

## Control de versiones

Los artefactos se identifican mediante un **ID único** y una versión. La versión vigente corresponde al artefacto ubicado en la carpeta principal, mientras que las versiones anteriores, cuando existen, se conservan en la carpeta `Versiones`.

## Video

**Video de presentación del proyecto:**

> enlace video

## Lecciones aprendidas

### 1. ¿Qué práctica de ingeniería de requisitos funciona y por qué debería usarse?

**Respuesta:**

> No existe una sola práctica que garantice un proceso correcto, sino un conjunto de prácticas que, aplicadas de manera adecuada, permiten llevar a cabo una buena gestión de requisitos. Sin embargo, considero que una de las más importantes es mantener una comunicación clara con el cliente.
>
> En un primer momento, el cliente presenta una propuesta o una necesidad, y como ingenieros de requisitos es fundamental transformar esa propuesta en una definición clara y realista de lo que se espera del producto. Para ello, es necesario comprender correctamente sus necesidades, aclarar las expectativas y definir el alcance del producto. 
>
> Además, no se debe simplemente decir “sí” a todo lo que propone el cliente. Es importante analizar la viabilidad de sus propuestas y, cuando sea necesario, conversar con el cliente para aclarar, negociar o ajustar aquello que no sea realista. De esta manera, la comunicación con el cliente permite establecer requisitos más claros, realistas y alineados con las posibilidades del proyecto.

### 2. ¿Qué técnica de gestión de requisitos falló y cómo se podría detectar?

**Respuesta:**

> Una de las situaciones que puede fallar en la gestión de requisitos es subestimar las capacidades del proyecto. Muchas veces, con el objetivo de evitar problemas o desacuerdos con el cliente, se aceptan propuestas sin analizar correctamente si son viables. Esto también puede llevar a no plasmar correctamente en los requisitos las funcionalidades que realmente necesita el cliente.
>
> En esa misma línea, otra dificultad puede ser no comunicarse correctamente con el cliente. Como ingenieros de requisitos podemos comprender conceptos técnicos o complejos que el cliente posiblemente no maneje. Por esta razón, es importante aprender a comunicarnos utilizando un lenguaje que el cliente pueda comprender y que permita confirmar que ambas partes tienen la misma interpretación de lo que se necesita.
>
> Esto se puede detectar mediante revisiones periódicas de los requisitos con el cliente, verificando que las funcionalidades documentadas correspondan realmente a sus necesidades y que exista un entendimiento común sobre el alcance y las capacidades del proyecto.

### 3. ¿Qué haríamos diferente en el proceso de gestión de requisitos?

**Respuesta:**

> Considero que durante este proceso me hubiera gustado definir desde el principio una mejor herramienta de gestión de requisitos. Al comienzo no consideré que la elección de esta herramienta fuera tan importante y, por esa razón, no escogí una herramienta adecuada desde el inicio.
>
> Sin embargo, durante el desarrollo del proyecto comprendí que su importancia es enorme. Es fundamental contar con una herramienta que permita registrar y organizar toda la información de manera adecuada, definir claramente la columna vertebral del proyecto, mantener la trazabilidad y facilitar la colaboración entre las personas involucradas.
>
> Por esa misma razón, es importante escoger una herramienta que permita llevar una trazabilidad adecuada de los requisitos, facilitando el seguimiento de cada requisito a través de los diferentes artefactos y permitiendo identificar cómo evoluciona a lo largo del proyecto.