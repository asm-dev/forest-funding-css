# Reforestación en Galicia - Diseño con CSS

Este repositorio contiene una página web sencilla de micromecenazgo o _crowdfunding_. La página está enfocada a lograr acciones medioambientales que permitan recuperar los bosques gallegos tras ser incendiados. 
> No se incluyen datos reales, se trata de una prueba de concepto educativa con fines puramente demostrativos.

La creación de esta web forma parte del programa de actividades del Máster en Desarrollo Web de la UEM. Si quieres conocer más sobre las razones detrás de su estructura HTML o ver cómo queda con algo de JS deberás visitar los siguientes enlaces:

1. [Estructura HTML](https://github.com/asm-dev/forest-funding-html)
2. [Funcionalidad JS](https://github.com/asm-dev/forest-funding-js)

La idea principal detrás del diseño propuesto con este CSS es crear una interfaz intuitiva y accesible que permita contribuir a una buena experiencia de navegación, potenciando con ello las donaciones de los usuarios.

&nbsp;

## Notas técnicas del diseño

Esta actividad refleja cómo las herramientas modernas de CSS, combinadas con un enfoque centrado en el usuario, pueden transformar una página web en una plataforma funcional y visualmente atractiva, contribuyendo con ello al éxito de iniciativas de _crowfunding_. 

Como dijo Steve Krug en _Don't Make Me Think_, el diseño web no es solamente cómo algo se ve o funciona, sino de lo que se siente al usarlo. En términos de usabilidad, hemos integrado elementos visuales y funcionales que guían al usuario hacia los objetivos clave, como realizar una donación o explorar proyectos. Por ejemplo, seleccionando el color de "acento" para los botones _Call To Action_. Aunque parezca una web simple, cada elemento del diseño ha sido pensado para conseguir conectar con los potenciales usuarios y reforzar así el propósito ambiental del sitio.

- **Divide y vencerás**. Se ha dividido el CSS en varios ficheros con el fin de mejorar la escabilidad y el mantenimiento del código.

- **Uso de variables**. Permiten mantener consistencia a lo largo de la página y reducir errores.

- **Implementación de CSS anidado**. El anidamiento posibilita organizar jerárquicamente las reglas, mejorando con ello la legibilidad.

- **Control preciso de posiciones**. Utilizar Flex y Grid permite jugar con las alineaciones de una manera precisa, adaptable y segura.

- **Empleo de transiciones y efectos**. Se han agregado varios pequeños detalles que contribuyan a mantener la atención del usuario al navegar por el sitio, por ejemplo un efecto en el hover de las cards.

- **El usuario primero**. Hemos de diseñar interfaces pensando en el usuario. La selección cromática está inspirada en los tonos de la naturaleza y el bosque, simbolizando el objetivo medioambiental del proyecto. En cuanto a la tipografía se optó por una fuente moderna y minimalista que permitiera conectar con una audiencia joven.

- **Un diseño adaptado a todas las pantallas**. Aunque no es _mobile first_, nos aseguramos de que para nada sea _mobile last_ gracias a un diseño responsive que usa medidas escalables como `rem` y _media queries_. Asegurar una navegación fluida en todos los dispositivos impacta positivamente en la accesibilidad y la usabilidad de nuestro sitio. Dos ejemplos de cambios en función de las dimensiones del dispositivo son:

  - El menú superior se transforma en menú hamburguesa para dispositivos móviles. 
  - En la sección de "Salvemos Crecente" se ha optado por mostrar todas las imágenes disponibles solo cuando el dispositivo supere ciertas dimensiones.

&nbsp;

Dispositivos móviles             |  Dispositivos de mayor tamaño
:-------------------------:|:-------------------------:
![captura-movil](https://github.com/user-attachments/assets/0cd744fe-ffc6-4557-8ffe-3c91dd30fd3e)  |  ![captura-ordenador](https://github.com/user-attachments/assets/0541c3ab-2dd7-4980-83de-cc14841bbcbd)
