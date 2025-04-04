# Presentaciones

IE1003 - Temas Especiales en Ingeniería I (Introducción al Diseño de Sistemas de Ingeniería)

## Asignaciones

| Tema | Apellido | Nombre | Capítulo | Directorio |
|---|---|---|---|---|
| Digitalización de la sociedad | Morales Quesada | José Fabian | 6. Digitalisation of Society | `presentations/3-digitalization` |
| Pensamiento sistémico | Alfaro Herrera | Brandon Andrey | 7. Systems Thinking: Practical Insights on Systems-Led Design in Socio-Technical Engineering Systems | `presentations/4-thinking` |
| Complejidad técnica y social | Cambronero Hernández | Gabriel Antonio | 8. Technical and Social Complexity | `presentations/5-complexity` |
| Comportamiento humano, roles y procesos | Blanco Arias | José Luis | 9. Human Behaviour, Roles, and Processes | `presentations/6-behavior` |
| Riesgo, incertidumbre e ignorancia | Valdés Céspedes | Johnnixia | 10. Risk, Uncertainty, and Ignorance in Engineering Systems Design | `presentations/7-risk` |
| Propiedades de los sistemas de ingeniería | Guzmán Carranza | Denzel Darío | 11. Properties of Engineering Systems | `presentations/8-properties` |
| Objetivos de diseño y necesidades | Esquivel Guadamuz | Andrés Josué | 12. Engineering Systems Design Goals and Stakeholder Needs | `presentations/9-goals` |
| Formulación de requisitos | Ulate Jarquín | Ángeles | 15. Formulating Engineering Systems Requirements | `presentations/10-requirements` |

El capítulo se refiere al libro *Handbook of Engineering Systems Design*. Esta es la principal referencia del curso. Es un libro en inglés donde están los capítulos que cada persona va a exponer en clase. En [este link](https://springerlink.proxyucr.elogim.com/referencework/10.1007/978-3-030-81159-4) es posible descargar el libro (PDF o ePUB) con las credenciales de la UCR en el SIBDI.

## Ver la presentación

- [Instalar Node.js](https://nodejs.org/en/download) en su computadora
- Instalar `pnpm` (un administrador de paquetes de JavaScript). En una terminal hacer:
```sh
npm install -g pnpm
```
- Clonar el repositorio de las presentaciones con Git:
```sh
git clone https://github.com/fabianabarca/idsi.git
```
- Ingresar al directorio del proyecto
```sh
cd idsi/
```
- Instalar las dependencias de paquetes (esto creará un directorio `node_modules` con una gran cantidad de archivos necesarios para la ejecución de las presentaciones con Slidev):
```sh
pnpm install
```
- Ejecutar Slidev con la presentación asignada:
```sh
pnpm slidev presentations/<directorio>/slides.md
```
donde `<directorio>` es la carpeta con la presentación asignada, por ejemplo: `7-risk`.

Con

```sh
pnpm slidev presentations/7-risk/slides.md
```

la terminal mostrará algo así como:

```sh
  ●■▲
  Slidev  v51.5.0 

  theme       @slidev/theme-default
  css engine  unocss
  entry       /Users/fabian/NextCloud/idsi/presentations/7-risk/slides.md

  public slide show   > http://localhost:3030/
  presenter mode      > http://localhost:3030/presenter/
  slides overview     > http://localhost:3030/overview/
  export slides       > http://localhost:3030/export/
  remote control      > pass --remote to enable

  shortcuts           > restart | open | edit | quit
```

y es posible visitar la presentación en el navegador en la URL http://localhost:3030/.

## Editar la presentación

Es necesario abrir el repositorio en su IDE (ambiente integrado de desarrollo) favorito, como VS Code, y editar el archivo `presentations/<directorio>/slides.md` asignado.

Cada vez que guarde el archivo, mientras el servidor local de Slidev está ejecutándose, se actualizará automáticamente la página con la presentación en el navegador.