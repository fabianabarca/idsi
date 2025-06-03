---
theme: default
title: Formulación de requisitos
info: Introducción al Diseño de Sistemas de Ingeniería
class: default
transition: fade-out
background: https://i.pinimg.com/736x/d6/89/b9/d689b968d35ac4e5702bfbb578bbd946.jpg
---

## Introducción al Diseño de Sistemas de Ingeniería
# Formulación de requisitos
### Ángeles Ulate Jarquín

---
layout: center
class: text-center bg-cover
---


# ¿Qué es más difícil?
¿Saber lo que queremos de un sistema o construirlo?

<div style="text-align: center;">
  <img src="https://i.pinimg.com/736x/a7/5a/f6/a75af6d4284d3e8c68c75723767596a2.jpg" alt="Imagen centrada" width="500">
</div>

---
layout: center
class: text-center
---

## 📌 Introducción

> La ciencia describe el mundo tal como es.
> 
> **La ingeniería busca transformarlo con intención.**

Los requisitos son el punto de partida.

<div style="text-align: center;">
  <img src="https://i.pinimg.com/736x/df/d2/d7/dfd2d74bace7acf2e758585cce6d754e.jpg" alt="400" width="400">
</div>


---

# ¿Qué son los requisitos?

* **Definición**: Descripciones de lo que debe hacer un sistema o cómo debe comportarse.

* Son guías que dirigen el diseño hacia lo que las **partes interesadas** esperan.
* Guían el diseño de sistemas sociotécnicos
* Utilizan verbos como "**deberá**" y "**debería**"
* **Ejemplo general**: “El sistema deberá transportar al menos 60 personas por unidad en hora pico.”

**Ejemplo aplicado**:
> “La app de buses **deberá** mostrar el tiempo con error < 1 minuto.”

---

## 🎯 Propósito

### ¿Para qué sirven los requisitos?

- Enmarcan problemas
- Coordinan actores
- Reducen alternativas

<div class="flex justify-center">
  <img src="https://i.pinimg.com/originals/ec/01/34/ec01346ffd3d24b27a8ac668113144a7.gif" alt="425" width="425" />
</div>

---

# Requisitos y causalidad

- Introducción al modelo **INUS**: condiciones insuficientes pero necesarias de un conjunto innecesario pero suficiente.
- **Ejemplo aplicado**: No basta solo con buses eléctricos, también se requiere:
  - Infraestructura de carga
  - Capacitación técnica
  - Apoyo regulatorio
  - Aceptación ciudadana

<div class="flex justify-center">
  <img src="https://i.pinimg.com/originals/99/b2/89/99b2892738ef83abeb4b7f6ad6801698.gif" alt="500" width="320" />
</div>

---

# Tipos de requisitos

| Tipo           | Definición                                 | Ejemplo en transporte público CR                                    |
| -------------- | ------------------------------------------ | ------------------------------------------------------------------- |
| Funcionales    | Qué debe hacer el sistema                  | “El sistema deberá aceptar pagos electrónicos y en efectivo.”       |
| No funcionales | Calidad, usabilidad, sostenibilidad        | “El servicio deberá tener una frecuencia menor a 10 minutos.”       |
| De rendimiento | Valores cuantificables                     | “La unidad deberá emitir menos de 50 gCO2/km.”                      |
| De proceso     | Cómo se desarrolla el sistema              | “El diseño deberá cumplir con normas INTECO y validación del MOPT.” |
| Restricciones  | Límites duros que no se pueden comprometer | “El bus no debe exceder 12 toneladas para ciertas rutas urbanas.”   |

---

# Gestión de requisitos

## ¡Actividades clave!

| Actividad      | ¿Qué implica?                     | Ejemplo con transporte CR                                  |
| -------------- | --------------------------------- | ---------------------------------------------------------- |
| Elicitación    | Identificar necesidades           | Encuestas a usuarios sobre horarios y rutas más necesarias |
| Análisis       | Validar y refinar lo recogido     | Clasificar necesidades como técnicas, sociales, económicas |
| Triaje         | Priorizar requisitos              | ¿Qué es más urgente: más unidades o paradas seguras?       |
| Especificación | Redactar requisitos precisos      | “Los buses deberán tener rampa desplegable automática”     |
| Verificación   | ¿El diseño cumple los requisitos? | Pruebas piloto con buses eléctricos en San José            |
| Validación     | ¿Resuelve el problema real?       | ¿Los usuarios están más satisfechos con la nueva flota?    |

---


## 📱 Ejemplo aplicado

> “La app **deberá** funcionar sin internet por 24 h.”

✅ Elicitado de usuarios
🔍 Analizado por ingeniería
📄 Especificado formalmente



<div class="flex justify-center">
  <img src="https://i.pinimg.com/originals/80/32/6c/80326c84c6e00910f63aa6260372ec25.gif" alt="300" width="420" />
</div>

---


## Naturaleza sociotécnica

- Involucra **múltiples partes interesadas** con objetivos distintos.
- Los requisitos se definen en la interacción proveedor–receptor.
- Conflictos y dependencias cruzadas son inevitables.
- Ejemplo local: usuarios desean más rutas nocturnas, operadores desean minimizar costos.


<div class="flex justify-center">
  <img src="https://i.pinimg.com/originals/fb/a4/97/fba4978ebe7b7b9c83b5dd830c06d367.gif" alt="300" width="420" />
</div>

---

## 🔁 Interacciones y efectos

Cambios en un elemento → afectan múltiples variables del sistema

<div class="flex justify-center">
  <img src="https://i.pinimg.com/originals/6a/32/7c/6a327caa4b5c102de396a1c3aaa20e98.gif" alt="425" width="425" />
</div>

---

# Reglas de formulación

- Usar verbos como **“deberá”** (obligatorio) o **“debería”** (deseable).
- Ser **verificables y específicos**.
- Evitar requisitos que limiten innecesariamente el diseño.
- Deben permitir la **descomposición jerárquica**.

<div class="flex justify-center">
  <img src="https://i.pinimg.com/originals/8b/6f/09/8b6f09ad8c27b4a987e4da02d1b6e6f7.gif" alt="300" width="420" />
</div>

---

# Documentación de requisitos

- Se registran en herramientas formales y contratos.
- Los requisitos programáticos y técnicos derivan de políticas generales.
- Ejemplo: requisitos de sostenibilidad de la NASA para telescopios → emisiones nulas, facilidad de reciclaje, autonomía.

<div class="flex justify-center">
  <img src="https://i.pinimg.com/originals/59/16/55/591655d75cb5468ad49e3163cfe61eca.gif" alt="300" width="420" />
</div>



---

# Métodos cuantitativos y verificación

- Importancia de la **verificabilidad desde la formulación**.
- Métodos:
  - Simulación
  - Prototipos físicos
  - Modelos analíticos

**Proceso**:
- Verificación: “¿Construimos el sistema correctamente?”
- Validación: “¿Es el sistema que realmente necesitábamos?”

<div class="flex justify-center">
  <img src="https://i.pinimg.com/originals/f5/27/0a/f5270acbc4b98112fcd520d2eea023de.gif" alt="700" width="220" />
</div>


---

# Cascada de objetivos y análisis isométrico

- **Cascada de objetivos**: descomposición de metas superiores en requisitos técnicos.
- **Análisis isométrico**: diferentes soluciones pueden cumplir los mismos requisitos de rendimiento.
- Permite **explorar el espacio de soluciones** y optimizar decisiones de diseño.

<div class="flex justify-center">
  <img src="https://i.pinimg.com/originals/62/c3/79/62c379ae3baad2a6f3810a8ad1a19d47.gif" alt="700" width="500" />
</div>


---

# Modelado y simulación

- Permite anticipar comportamientos del sistema antes de construirlo.
- Facilita la iteración y comparación de alternativas.
- Útil en transporte: ¿qué pasa si aumentamos frecuencias? ¿Si integramos bicicletas?


<div class="flex justify-center">
  <img src="https://i.pinimg.com/originals/93/2a/84/932a84e696fcb3591bdef749ead63952.gif" alt="700" width="500" />
</div>


---

## 🧩 Complejidad técnica y social

### 🧍‍♂️ Receptor:
- Enfrenta requisitos ambiguos, cambiantes

### 🧑‍💻 Proveedor:
- Lidia con múltiples dependencias técnicas

📌 Ejemplo: “Quiero un bus cómodo” → ¿Qué significa exactamente?

<div class="flex justify-center">
  <img src="https://i.pinimg.com/originals/a8/cf/1e/a8cf1ebf8691a8870e07c182648c0787.gif" alt="700" width="500" />
</div>

---

## 🚏 Caso aplicado: Transporte público en Costa Rica

- Sistema sociotécnico
- Requisitos funcionales: GPS, horarios sincronizados
- Requisitos no funcionales: accesibilidad, consumo, experiencia de usuario

<div class="flex justify-center">
  <img src="https://i.pinimg.com/originals/6f/55/10/6f5510e1d92776f9a6aa3133f8ff12a1.gif" alt="700" width="500" />
</div>


---

# Conclusiones


<br>
Un buen diseño comienza con entender bien el problema. 
Y entender el problema comienza con formular buenos requisitos.

<br>

- La formulación de requisitos es un **proceso dinámico, técnico y social**.
- Su correcta aplicación puede generar un transporte público más **justo, eficiente y humano**.
- Involucrar a todas las partes desde el inicio es **clave para el éxito** del sistema.


<div class="flex justify-center">
  <img src="https://i.pinimg.com/736x/31/31/f9/3131f9d0c465ad4ee95c99a6fee7738d.jpg" alt="700" width="300" />
</div>

---

### ¿Qué harías tú para mejorar el transporte?

- ¿Qué requisitos funcionales incluirías?
- ¿Qué aspectos sociales considerarías?


<div class="flex justify-center">
  <img src="https://i.pinimg.com/originals/61/1b/0d/611b0d248e0b1956a2759322d5ba7f50.gif" alt="700" width="700" />
</div>
