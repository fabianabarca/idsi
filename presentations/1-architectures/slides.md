---
theme: seriph
title: Arquitecturas de Sistemas
info: Introducción al Diseño de Sistemas de Ingeniería
class: text-center
transition: fade-out
background: https://images.unsplash.com/photo-1637190623651-e6b10007a0b7
---

## Introducción al Diseño de Sistemas de Ingeniería

# Arquitecturas de sistemas

Fabián Abarca Calderón

---
layout: quote
---

## No hay viento favorable para quien no sabe adónde va

_Séneca_

---
layout: quote
---

## Todos los sistemas complejos que funcionan evolucionaron a partir de sistemas más simples que funcionaron

_Ley de Gall_

---
layout: intro
---

# Arquitecturas de sistemas

Los **sistemas complejos** requieren una minuciosa **planificación**. Las arquitecturas de sistemas ofrecen **insumos esenciales** para el diseño, la integración, las pruebas y cualquier otra etapa de su desarrollo.

---
layout: section
---

# Introducción

---
layout: image-left
image: https://images.unsplash.com/photo-1689535090647-30d91848abbf
---

## Objetivos

<br>

**_Arquitecturas de sistemas_**

- Explorar <span v-mark.red="1">definiciones</span>
- Reflexionar sobre su <span v-mark.red="2">importancia</span>
- Estudiar <span v-mark.red="3">conceptos claves</span>
- Conocer <span v-mark.red="4">métodos</span> y <span v-mark.red="4">herramientas</span> de desarrollo
- Discutir <span v-mark.red="5">tendencias</span> y <span v-mark.red="5">desafíos</span>

---
layout: section
---

## Arquitecturas de sistemas

# Definiciones

---
layout: two-cols-header
layoutClass: gap-16
---

# Definiciones de arquitectura de sistemas

Primera aproximación: _forma abstracta de la estructura del sistema_.

::left::

> Las arquitecturas de sistemas muestran los **conceptos** o **propiedades** fundamentales del sistema en su **entorno**, expresado en sus **elementos**, **relaciones** y en los principios de su **diseño** y **evolución**.
>
> --- _(ISO/IEC/IEEE 42010:2011)_

<br>

<div  class="grid grid-cols-2 gap-4">
<div >

- conceptos
- propiedades
- entorno
- elementos

</div>
<div >

- relaciones
- diseño
- evolución

</div>
</div>

::right::

> La arquitectura de un sistema es la declaración del **concepto**, la asignación de **función** física o de información a los elementos de **forma**, y la definición de **relaciones** entre los **elementos** y con el **contexto** que los rodea.
>
> --- _Crawley E, Cameron B, Selva D (2016) System architecture: strategy and product development for complex systems. Pearson_

<br>

<div  class="grid grid-cols-2 gap-4">
<div >

- concepto
- función
- forma

</div>
<div >

- relaciones
- elementos
- contexto

</div>
</div>

---
layout: section
---

## Arquitecturas de sistemas

# Importancia

---
layout: two-cols-header
---

## ¿Por qué, para qué?

::left::

- ¡Hay muchos grados de libertad!
- Las decisiones tempranas tienen un impacto significativo
  - Fijación de parámetros esenciales
  - Definición de categorías
  - Reducción paulatina de las variables

::right::

- Aclara las alternativas:
  - Dónde hay que elegir entre tecnologías
  - Dónde hay que innovar y crear
- Identifica funciones específicas y diferenciadas
  - Revela interacciones entre las partes
- Aumento de la complejidad con disminución del tiempo de diseño

---
layout: two-cols-header
---

## Ejemplo de funciones específicas y diferenciadas

<div class="text-center">

```mermaid
flowchart LR
  U([Función])
  O[Forma]

  U --> O
```

</div>

::left::

### Antes (_ornitóptero_)

Concentración de funciones

```mermaid
flowchart LR
  S([Sustentación])
  C([Control])
  P([Propulsión])
  A[Ala]

  S & C & P --> A
```

::right::

### Después (_aeroplano_)

Arquitectura modular

```mermaid
flowchart LR
  S([Sustentación])
  C([Control])
  P([Propulsión])
  A[Ala]
  T[Cola]
  M[Motor]

  S --> A
  C --> T
  P --> M
```

---
layout: section
---

## Arquitecturas de sistemas

# Desarrollo

---

## Marcos estandarizados para arquitecturas de sistemas

La industria, instituciones gubernamentales y organizaciones multinacionales han creado métodos de desarrollo de arquitecturas para simplificar el proceso para las partes involucradas. Esto ha provisto:

- Lenguaje común
- Procesos definidos
- Acumulación de experiencia

<br>

<div class="text-center">

```mermaid
flowchart LR
 A[Necesidades de las partes]
 B[Requisitos del sistema]

 A <--> B
```

</div>

---
layout: two-cols-header
---

## Estándares de arquitecturas de sistemas

Existe una gran variedad de estándares de desarrollo de arquitecturas, pero todos ofrecen un núcleo similar.

::left::

### Componentes

- **Metodología**
  - Proceso de diseño
- **Puntos de vista**
  - Definición e intercambio de datos
- **Meta modelo**
  - Modelo de referencia para descripción
- **Glosario**
  - Definición de los términos utilizados

::right::

### Pasos

1. Identificación de las **necesidades** de las partes
2. Definición de alto nivel de los **requisitos**
3. Definición de la **arquitectura funcional**
4. Definición de la **arquitectura física**

Pasos de mayor a menor nivel de abstracción.

---
layout: iframe
url: https://www.opengroup.org/togaf
---

---
layout: two-cols
---

## ArchiMate

#### _Enterprise Architecture Modeling Language_

<br>

> La especificación de ArchiMate define un **lenguaje común** para describir la construcción y operación de los procesos de negocio, las estructuras organizacionales, los flujos de información, los sistemas informáticos y la infraestructura técnica.

<br>

- The Open Group Architecture Framework (TOGAF)
- Está concentrado en la abstracción

::right::

![ADM](https://pubs.opengroup.org/architecture/archimate3-doc/images/fig-ArchiMate-Full-Framework.png)

---
layout: two-cols
---

## ARC-IT

#### _Architecture Reference for Cooperative and Intelligent Transportation_

<br>

> Arquitectura común para planificar, definir e integrar sistemas inteligentes de transporte. ARC-IT es una arquitectura de referencia: proporciona una base común para que planificadores e ingenieros con diferentes enfoques puedan concebir, diseñar e implementar sistemas utilizando un **lenguaje común**.

<br>

- Departamento de Transportes, Estados Unidos
- Definición de _paquetes de servicio_
- Establece _flujos de información_

::right::

![ARC-IT](https://www.arc-it.net/images/archlayers/archlayers.jpg)

---
layout: two-cols
---

# Ciclo de desarrollo

::right::

![Architecture development cycle](https://www.opengroup.org/sites/default/files/ADM.png)

---
layout: section
---

## Arquitecturas de sistemas

# Tendencias

---
layout: two-cols-header
---

## Sistemas de Producto-Servicio

<div class="text-center">

```mermaid
flowchart TD
  P([Productos tangibles])
  S([Servicios intangibles])
  SPS(Sistemas Producto-Servicio)

  P & S --> SPS
```

</div>

::left::

- Combinación de productos y servicios
- Énfasis en la entrega de servicios
- Perspectiva social ampliada
- Intervenciones en sistemas existentes

::right::

- Límites del sistema flexibles
- Naturaleza colaborativa (sistema de sistemas)
- Interfaces complejas (servicios, sistemas, personas)
- Uso de modelos de características (_features_)

---
layout: image
image: https://www.researchgate.net/publication/224220942/figure/fig1/AS:669004100292622@1536514415649/A-sample-feature-model.png
backgroundSize: contain
---

---
layout: section
---

# Conclusiones

---
layout: center
---

**_Arquitecturas de sistemas_**

- Son fundamentales para la definición de sistemas duraderos y sostenibles
- Permiten la identificación, modelado y gestión de interfaces críticas
- Utilizan un conjunto de mejores prácticas, métodos y herramientas para su desarrollo
- Esenciales en un mundo cada vez más complejo

---
layout: end
---

## ¿Cómo crear una arquitectura para un sistema de información en el transporte público inteligente?
